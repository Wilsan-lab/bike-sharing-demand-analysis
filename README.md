# 🚲 Bike Sharing Demand Prediction

## 📌 Project Overview

This project analyzes bike-sharing demand and develops machine learning models to predict the number of bike rentals.

The project covers the complete machine learning workflow, including data preparation, exploratory data analysis, feature engineering, model training, model evaluation, model explainability, and deployment of a prediction interface.

## 🎯 Objectives

- Analyze patterns in bike-sharing demand.
- Explore the relationship between weather, time, and rental demand.
- Engineer useful features for prediction.
- Train and compare multiple regression models.
- Evaluate model performance using RMSE, MAE, and R².
- Explain model predictions using different explainability techniques.
- Develop a prediction interface using Flask.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- SHAP
- Flask

## 🤖 Machine Learning Models

The following regression models were evaluated:

1. Linear Regression
2. Ridge Regression
3. Random Forest Regressor
4. Optimized Random Forest Regressor
5. XGBoost Regressor

## 📊 Model Performance

XGBoost achieved the best performance among the evaluated models:

| Model | RMSE | MAE | R² |
|---|---:|---:|---:|
| Linear Regression | 109.41 | 83.48 | 0.637 |
| Ridge Regression | 109.41 | 83.47 | 0.637 |
| Random Forest | 39.19 | 24.56 | 0.953 |
| Optimized Random Forest | 39.08 | 24.49 | 0.954 |
| **XGBoost** | **37.19** | **24.12** | **0.958** |

Based on these results, XGBoost was selected as the final model.

## 🔍 Model Explainability

The project also explores different techniques for understanding model predictions, including:

- Feature Importance
- Actual vs Predicted Analysis
- Surrogate Tree
- Partial Dependence and ICE Plots
- SHAP Beeswarm Plot
- SHAP Bar Plot

## 🚀 Deployment

A prediction interface was developed using Flask to demonstrate how the trained model can be used for predictions.

## 📁 Project Structure

```text
bike-sharing-demand-analysis/
│
├── BSD(ML).ipynb
├── train.csv
├── README.md
├── LICENSE
└── .gitignore
