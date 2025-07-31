# Loan Approval Prediction – MLOps Project

## Overview
This repository showcases a hands-on, modular approach to building and deploying a Loan Approval Prediction system using MLOps best practices. It covers the full machine learning lifecycle from data preprocessing and model training to deployment, monitoring, and CI/CD integration making it ideal for learners and practitioners aiming to master MLOps. 

## Tech Stack
- Languages: Python, Jupyter Notebook
- Frameworks: Flask, FastAPI, Streamlit
- MLOps Tools: MLflow, DVC, GitHub, Jenkins, Docker, Kubernetes
- Monitoring: Prometheus, Grafana, WhyLogs
- Cloud: AWS

## Repository Structure
```
mlops/
├── Build-ML-App-FASTAPI/              # FastAPI-based ML app
├── Build-ML-App-Flask/                # Flask-based ML app
├── Build-ML-App-Streamlit/            # Streamlit-based ML app
├── Continuous-Monitoring-Prometheus-Grafana/
├── Deploy-Applications-Docker-Compose/
├── Docker-for-ML/
├── Getting-Started-with-AWS/
├── Git-For-MLOps/
├── Kubernetes-101/
├── Linux-Basics/
├── ML-Monitoring-WhyLogs/
├── MLFlow-Manage-ML-Experiments/
├── Packaging-ML-Model/
├── Python-For-DataScience-MLOps/
├── Python-for-mlops/
├── YAML-Basics/
├── ml-ci-cd-jenkins/
├── .gitignore
└── README.md
```

## Setup Instructions
``` bash
Clone the repository
git clone https://github.com/ispr08/mlops.git
cd mlops

(Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate

Install required packages
pip install -r requirements.txt
```

## Project Highlights

-  Multiple deployment frameworks: Flask, FastAPI, Streamlit
-  Model packaging and versioning with MLflow and DVC
-  CI/CD pipeline setup using Jenkins
-  Real-time monitoring with Prometheus, Grafana, and WhyLogs
-  Cloud integration walkthrough with AWS
-  Containerization and orchestration using Docker and Kubernetes

## Model Training & Deployment

Each subfolder contains modular implementations. Refer to the respective README or scripts inside:

```bash
cd Build-ML-App-FastAPI
python app.py
```

## Monitoring Setup
- Prometheus & Grafana: Located in `Continuous-Monitoring-Prometheus-Grafana/`
- WhyLogs: For data drift and model performance tracking






