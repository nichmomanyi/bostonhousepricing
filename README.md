# 🏠 House Price Prediction — Regression Analysis

A machine learning project that predicts house prices using regression models, served via a Flask API, containerized with Docker, and deployed to Heroku through an automated GitHub Actions CI/CD pipeline.

## 📊 Overview

This project applies regression analysis to the Boston Housing dataset to predict median house prices based on features such as crime rate, number of rooms, property tax rate, and more. It includes:

- Data exploration and preprocessing
- Model training with cross-validation (KFold)
- Residual and skew diagnostics
- A Flask web app for serving predictions
- Full containerization and automated cloud deployment

## 🧰 Tech Stack

- **Language:** Python 3.7
- **ML libraries:** scikit-learn, pandas, numpy
- **Visualization:** matplotlib
- **Web framework:** Flask + Gunicorn
- **Containerization:** Docker
- **CI/CD:** GitHub Actions
- **Hosting:** Heroku (Container Registry)
