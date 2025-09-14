# Project 6: Predicting Future Store Sales with AI

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1lAFG5iSh_FSW5LdqnEqFFaOrTXVGv0i0)

## Objective
Forecast future sales for retail locations using historical transaction, promotion, and calendar data.

## Pipeline
- Time-aware feature engineering (lag features, moving averages, promo windows)
- Holiday & seasonal encoding
- Baseline naive / moving average comparison
- Gradient Boosting / XGBoost / LightGBM models
- Cross-validation with time series splits
- Error analysis by store / product segment

## Files
- `6_Predicting_Future_Store_Sales_with_AI.ipynb` – Forecasting workflow

## Extensions
- Prophet or ARIMA hybrid models
- Hierarchical forecasting (store → region → total)
- MLOps: retraining schedule & model monitoring ideas

## Outcome
An extensible forecasting framework to support inventory planning, promotion strategy, and revenue optimization.
