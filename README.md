# Predictive Home Pricer [![Sean-Breach](https://circleci.com/gh/Sean-Breach/PredictiveHomePricer.svg?style=shield)](https://circleci.com/gh/Sean-Breach/PredictiveHomePricer)

## Project Overview

In this project, I have applied the skills acquired in [Udacity's Cloud DevOps Engineer Program](https://www.udacity.com/course/cloud-dev-ops-nanodegree--nd9991) for the _Microservices at Scale using Kubernetes_ course to operationalize a Machine Learning Microservice API. 

>Given a pre-trained, `sklearn` model that has been trained to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios, and so on. You can read more about the data, which was initially taken from Kaggle, on [the data source site](https://www.kaggle.com/c/boston-housing). This project tests your ability to operationalize a Python flask app—in a provided file, `app.py`—that serves out predictions (inference) about housing prices through API calls. This project could be extended to any pre-trained machine learning model, such as those for image recognition and data labeling.

### Project Tasks 

>Your project goal is to operationalize this working, machine learning microservice using [kubernetes](https://kubernetes.io/), which is an open-source system for automating the management of containerized applications. In this project you will:
>* Test your project code using linting
>* Complete a Dockerfile to containerize this application
>* Deploy your containerized application using Docker and make a prediction
>* Improve the log statements in the source code for this application
>* Configure Kubernetes and create a Kubernetes cluster
>* Deploy a container using Kubernetes and make a prediction
>* Upload a complete Github repo with CircleCI to indicate that your code has been tested

>You can find a detailed [project rubric, here](https://review.udacity.com/#!/rubrics/2576/view).

>**The final implementation of the project will showcase your abilities to operationalize production microservices.**

---

## Seting up the Environment

* Create the virtualenv `python3 -m venv /.devops` and activate it `source ~/.devops/bin/activate`  
* Run `make install` to install the necessary dependencies into the venv

### Running Flask Application `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`

### Kubernetes Steps

* Setup and Configure Docker locally
  * [Docker Desktop](https://www.docker.com/products/docker-desktop)
  * Use Native Bash or [Git Bash](https://www.techoism.com/how-to-install-git-bash-on-windows/) for Windows to work with Docker CLI
* Setup and Configure Kubernetes locally
* Create Flask app in Container
* Run via kubectl
