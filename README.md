# DSAI4201-project

Heart Disease Prediction System
Farah Abu-Shariha - 60104384 

## About the Project:
This project builds a machine learning system that predicts whether a patient has heart disease based on clinical measurements. The goal is to support early detection using data that is already collected during standard medical checkups, such as blood pressure, cholesterol, and chest pain type.
The dataset used is the UCI Heart Disease Dataset, which combines 920 patient records from four hospitals: Cleveland Clinic, Hungarian Institute of Cardiology, University Hospital Zurich, and Long Beach VA Medical Center.
Three models were trained and compared — Logistic Regression, Random Forest, and Support Vector Machine. Random Forest performed best and was selected as the primary model. The system also includes cross-validation, hyperparameter tuning with GridSearchCV, and a demo that predicts disease probability for new patients.

## Files in this Repository:
Heart_Disease_60104384.ipynb — the full project notebook 

heart_disease_uci.csv — the dataset (must be in the same folder as the notebook)


report - 60104384.docx — the project report


## How to Run: 
Download both Heart_Disease_60104384.ipynb and heart_disease_uci.csv and place them in the same folder

Open the notebook in Jupyter or Google Colab

Run all cells from top to bottom

## Requirements:
pandas
numpy
matplotlib
seaborn
scikit-learn
joblib

## Install with: 
pip install pandas numpy matplotlib seaborn scikit-learn joblib
