# Project 7: Preventing Customer Churn with Feature Transformation

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1BdAoVpdG2iOjat_tlQlDTN3b5GLlTELR)

## Objective
Predict and reduce customer churn by engineering informative behavioral and lifecycle features from raw usage data.

## Strategy
- Define churn label (time-based or inactivity threshold)
- Data aggregation (sessions, orders, support tickets, tenure)
- Feature transformations (ratios, rolling windows, recency/frequency/monetary metrics)
- Model training (Logistic Regression, Gradient Boosting, XGBoost)
- Class imbalance mitigation (resampling or cost-sensitive learning)
- Evaluation: ROC-AUC, Precision-Recall, lift / gain chart

## Files
- `7_Preventing_Customer_Churn_with_Feature_Transformation.ipynb` – End-to-end churn modeling pipeline

## Extensions
- Survival analysis (time-to-churn modeling)
- Uplift modeling for retention campaigns
- SHAP explanations to drive retention actions

## Outcome
A feature-focused churn prediction framework enabling proactive retention strategies and KPI tracking.
