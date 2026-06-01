# fraud-detection-system-xgboost

# Fraud Detection System using XGBoost

## Project Overview

This project develops a machine learning-based fraud detection system to identify fraudulent financial transactions. The solution uses the IEEE-CIS Fraud Detection dataset and applies advanced machine learning techniques to address class imbalance and improve fraud detection performance.

## Business Problem

Financial fraud results in significant losses for organizations and customers. Early detection of suspicious transactions helps reduce financial risk, improve customer trust, and support regulatory compliance.

## Dataset

Dataset: IEEE-CIS Fraud Detection Dataset

Target Variable:

* isFraud

  * 0 = Legitimate Transaction
  * 1 = Fraudulent Transaction

Dataset Characteristics:

* Transaction-level financial records
* Highly imbalanced fraud classes
* Numerical and encoded categorical features
* Large-scale tabular dataset

## Project Workflow

1. Data Loading and Inspection
2. Exploratory Data Analysis (EDA)
3. Missing Value Analysis
4. Feature Engineering
5. Class Imbalance Handling using SMOTE
6. Train-Test Split
7. XGBoost Model Training
8. Hyperparameter Optimization
9. Model Evaluation
10. Fraud Probability Scoring
11. Model Interpretability

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* XGBoost
* Imbalanced-Learn
* Matplotlib
* Seaborn

## Model

Algorithm:

* XGBoost Classifier

Class Imbalance Handling:

* SMOTE (Synthetic Minority Oversampling Technique)

## Evaluation Metrics

* AUC-ROC: 0.7757
* AUC-PR: 0.1930
* Brier Score: 0.07695
* Precision
* Recall
* F1-Score
* Confusion Matrix

Confusion Matrix:

[[94395 7853]
[1998 1617]]

## Key Features

* Fraud prediction using transaction data
* Probability-based fraud scoring
* Class imbalance handling
* Threshold tuning support
* Explainable model outputs
* Reproducible machine learning pipeline

## Installation

pip install -r requirements.txt

## Run

python main.py

## Future Improvements

* SHAP-based explainability
* Real-time fraud scoring API
* Ensemble learning approaches
* Advanced feature engineering
* Model deployment using FastAPI

## Author

Treesa Mariam Kurian
