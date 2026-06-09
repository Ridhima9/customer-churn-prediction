# Customer Churn Prediction & Explainability

Developed an end-to-end machine learning pipeline to predict customer churn and identify the key factors influencing customer attrition. The project leverages XGBoost for predictive modeling and SHAP for explainable AI, enabling businesses to proactively identify at-risk customers and improve retention strategies.

## Tech Stack

Python, Pandas, Scikit-learn, XGBoost, Optuna, SHAP, Matplotlib

## Features

* Processed and analyzed 100K+ customer records
* Handled class imbalance using SMOTE
* Performed Optuna-based hyperparameter tuning
* Compared Logistic Regression, Random Forest, and XGBoost models
* Applied SHAP for model interpretability and feature analysis

## Results

* ROC-AUC: **0.925**
* F1-Score: **0.820**
* XGBoost achieved the best performance among all evaluated models

### Top Churn Drivers

1. Contract Type
2. Tenure
3. Monthly Charges

## Visualizations

* Model Comparison
* Confusion Matrix
* SHAP Feature Importance
* SHAP Summary Plot

## Business Impact

The model helps organizations identify customers likely to churn and understand the reasons behind their decisions, enabling targeted retention campaigns and data-driven business strategies.
