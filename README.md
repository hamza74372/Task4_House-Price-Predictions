Predicting House Prices – California Housing Dataset
📌 Objective
The goal of this task is to build a regression system that can predict house prices using the California Housing Dataset. The task involves data preprocessing, implementing machine learning models (including Linear Regression from scratch), evaluating model performance, and visualizing feature importance.

🔢 Dataset
We used the fetch_california_housing() dataset provided by scikit-learn, which contains features such as:

Average number of rooms

Median income

Population

House age

and more

✅ Steps Performed
1. Data Preprocessing
Loaded the dataset using fetch_california_housing()

Scaled numerical features using StandardScaler

Split the dataset into training and testing sets

2. Model Implementation
Linear Regression (from scratch) using Gradient Descent

Random Forest Regressor using scikit-learn

XGBoost Regressor using xgboost

3. Model Evaluation
Evaluated each model using:

RMSE (Root Mean Squared Error)

R² Score

4. Feature Importance Visualization
Used feature_importances_ from Random Forest

Used built-in plot from XGBoost for importance visualization

📊 Results
Model	RMSE	R² Score
Linear Regression	XX.XX	X.XX
Random Forest	XX.XX	X.XX
XGBoost	XX.XX	X.XX

(Fill in your actual results from the notebook)

📁 Files Included
Task4_HousePricePrediction.ipynb – The main Colab notebook

README.md – This file explaining the task

Visualizations (included as screenshots or in notebook)

🔗 How to Run
Open the notebook in Google Colab

Run each cell step-by-step

All dependencies are handled within the notebook
