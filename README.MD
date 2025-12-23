# Predicting Used Car Prices using Machine Learning

**Group 4:** Clément VURPILLOT, Andréa ZANIN, Antoine URSEL

## 1. Project Overview
We want to predict used car prices based on a Craigslist dataset we found on kaggle
**Business Goal:** Help sellers set competitive prices and help buyers identify good deals (+ fraud detection).

## 2. Methodology
* **Data Cleaning:** We deleted outliers (prices > $500k), missing values, and irrelevant columns.
* **Preprocessing:** used of One-Hot Encoding for categorical features, StandardScaler.
* **Models:** Linear Regression, Decision Tree, Random Forest, CatBoost, LightGBM.
* **Optimization:** use of GridSearch for the hyperparameter tuning.

## 3. Results
* **Best Model:** LightGBM Regressor
* **Performance:** R² Score ≈ 0.82 | MAE ≈ 3650$

