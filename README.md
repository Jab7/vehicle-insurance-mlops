# Vehicle Insurance Response Prediction - End-to-End MLOps Pipeline

## Overview

This project implements an end-to-end machine learning pipeline for predicting customer response to vehicle insurance offers. The system covers the complete ML lifecycle including data ingestion, validation, transformation, model training, evaluation, version management, API deployment, and monitoring.

The project follows a modular MLOps architecture designed to improve reproducibility, maintainability, and deployment readiness of machine learning workflows.

---

## Key Features

### Data Pipeline

* Automated data ingestion from MongoDB Atlas
* Schema-based data validation
* Feature preprocessing and transformation
* Class imbalance handling using SMOTEENN

### Model Development

* Random Forest based classification pipeline
* Automated model evaluation using multiple performance metrics
* Custom model registry for model version management
* Artifact tracking and reusable preprocessing workflows

### Deployment

* FastAPI-based prediction service
* Dockerized application deployment
* Environment-based configuration management
* Cloud deployment support

### Monitoring & Operations

* CI/CD workflows using GitHub Actions
* Redis-based caching support
* Prometheus metrics collection
* Grafana dashboard integration
* Structured logging and exception handling

---

## Project Architecture

Data Source (MongoDB Atlas)
↓
Data Ingestion
↓
Data Validation
↓
Data Transformation
↓
Model Training
↓
Model Evaluation
↓
Model Registry
↓
FastAPI Prediction Service
↓
Docker Deployment
↓
Monitoring & CI/CD

---

## Technology Stack

### Machine Learning

* Python
* Scikit-learn
* Pandas
* NumPy

### Backend & APIs

* FastAPI
* Pydantic

### MLOps

* Docker
* GitHub Actions
* CI/CD Pipelines
* Model Registry

### Data Storage

* MongoDB Atlas

### Monitoring

* Prometheus
* Grafana

### Deployment

* Render

---

## Repository Structure

```text
src/
├── components/
│   ├── data_ingestion.py
│   ├── data_validation.py
│   ├── data_transformation.py
│   ├── model_trainer.py
│
├── pipeline/
│   ├── training_pipeline.py
│   └── prediction_pipeline.py
│
├── data_access/
├── entity/
├── configuration/
└── utils/

app.py
Dockerfile
requirements.txt
README.md
```

---

## Skills Demonstrated

* End-to-End Machine Learning Pipelines
* Data Validation & Feature Engineering
* Model Version Management
* API Development using FastAPI
* Docker Containerization
* CI/CD Automation
* Monitoring & Observability
* MLOps Best Practices

---

## Future Improvements

* MLflow-based experiment tracking
* Advanced model comparison framework
* Automated retraining workflows
* Kubernetes deployment
* Cloud-native model serving
