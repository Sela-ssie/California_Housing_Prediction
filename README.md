# California_Housing_Prediction

# Project Overview
Predicting California housing prices using advanced regression techniques, feature engineering, and model tuning. This project builds and evaluates a machine learning model to predict median house values using housing-related features. It explores the impact of socio-economic and geographic factors on home prices and builds a robust ML pipeline with cross-validation and hyperparameter optimization using XGBoost.

# Dataset
Source: [California Housing Dataset](https://www.kaggle.com/datasets/camnugent/california-housing-prices)
Features include income, population, proximity to the ocean, and more.

# Tech Stack
Python (numpy, pandas, scikit-learn)
Jupyter Notebook
XGBoost

# EDA Highlights
Strong positive correlation between median income and house value

# Model
Model: XGBoost Regressor
RMSE (final): **$44617**
Evaluation: Residual plots, actual vs predicted scatter, cross-validation

# Visuals
Actual vs Predicted Prices
Residual Plot
Residual Distribution
Feature Importances

# Requirements
```bash
pip install -r requirements.txt
