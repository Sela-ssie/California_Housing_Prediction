# California_Housing_Prediction

# Project Overview
Predicting California housing prices using advanced regression techniques, feature engineering, and model tuning. This project builds and evaluates a machine learning model to predict median house values using housing-related features. It explores the impact of socio-economic and geographic factors on home prices and builds a robust ML pipeline with cross-validation and hyperparameter optimization using XGBoost.

# Dataset
Source: [California Housing Dataset](https://www.kaggle.com/datasets/camnugent/california-housing-prices)
Features include income, population, proximity to the ocean, and more.

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

# File Structure
House_Price_Prediction/
│
├── data/
│   ├── raw/
|       ├── housing.csv
│   ├── processed/
│       ├── housing_cleaned.csv
|       ├── housing_final_features.csv
|       ├── x_train.csv
|       ├── x_test.csv
|       ├── y_train.csv
|       ├── y_test.csv
|
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_feature_engineering.ipynb
│   ├── 03_model_training.ipynb
│   ├── 04_hyperparameter_tuning.ipynb
│   ├── 05_final_results.ipynb
│
├── models/
|   ├── xgb_model.pkl
│   └── xgb_best_model.pkl
│
├── visuals/
│   ├── actual_vs_predicted.png
│   ├── error_distribution.png
│   ├── feature_importances.png
│   ├── residual_plot.png
│
├── requirements.txt
├── README.md
└── .gitignore


# Requirements
```bash
pip install -r requirements.txt