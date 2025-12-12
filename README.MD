# Predicting Car Prices using Machine Learning

**Group 4:** Clément VURPILLOT, Andréa ZANIN, Antoine URSEL

## 1. Project Overview
This project aims to predict used car prices based on the Craigslist dataset.
**Business Goal:** Help sellers set competitive prices and help buyers identify good deals (fraud detection).

## 2. Methodology
* **Data Cleaning:** Handling outliers (prices > $500k), missing values, and irrelevant columns.
* **Preprocessing:** One-Hot Encoding for categorical features, StandardScaler.
* **Models:** Linear Regression, Decision Tree, Random Forest, CatBoost, LightGBM.
* **Optimization:** GridSearch for hyperparameter tuning.

## 3. Results
* **Best Model:** LightGBM Regressor
* **Performance:** R² Score ≈ 0.82 | MAE ≈ 3650$

## 4. How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Run the notebook: `notebooks/Final_Notebook.ipynb`