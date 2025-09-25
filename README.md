# Customer Churn Prediction for E-commerce
Predicting which customers will stop purchasing, based off of behaviorial and demographic data.

## Overview
This project aims to identifying customers who are likely to churn based off of behaviorial, demographic, and transactional features. Churn risk is predicted using classification models, providing useful business insights and decision-making

## Key Features
- End-to-End ML Pipeline (EDA -> Feature Engineering -> Modeling)
- Balanced Handling of Class Imbalance using SMOTE
- Multiple Models Compared Against (Logistic Regression, Random Forest, XGBoost)
- Buissness-oriented engineered features (e.g. Recent Engagement Flag, Per-Order Incentives)
- Evaluation with AUC-ROC, PR_AUC, Recall, Confusion Matrix, Brier Score
- Model Interpretability with Correlation Insights & Feature Analysis

## Tools
- Python (Pandas, Numpy, Matplotlib)
- Scikit-learn, XGBoost, imbalanced-learn
- Jupyter Notebook

## Project Structure
- eda.ipynb - Exploratory Data Analysis
- feature_engineering.ipynb - Feature Creation, Encoding, Handling Missing Values
- modeling.ipynb - Pipelines, Model Comparison, Evaluation
- data/ - Files used for Modeling
- models/ - Saved Models 
- README.md - Project Documentation

## Results
| Metric       | Logistic Reg | Random Forest | XGBoost |
|--------------|--------------|---------------|---------|
| PR-AUC       | 0.48         | 0.89          | 0.92    |
| Brier Score  | 0.09         | 0.02          | 0.01    |
| AUC-ROC      | 0.87         | 0.99          | 0.99    |
| Calibrated   | Yes          | Yes           | Yes     | 



