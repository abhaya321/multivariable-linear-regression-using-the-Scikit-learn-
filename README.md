# Multivariable Linear Regression with Scikit-learn

## Overview
This project implements multivariable linear regression using the Scikit-learn library to predict house prices from the Boston Housing dataset. It covers:

- Data loading and preprocessing
- Handling missing values
- Feature scaling using StandardScaler
- Train-test splitting
- Model training using LinearRegression
- Polynomial feature expansion (optional)
- Model evaluation using Mean Squared Error (MSE) and R² score
- Visualization of actual vs predicted values

## Dataset
Boston Housing dataset downloaded from Kaggle or sklearn.

## How It Works
1. Load dataset and handle missing values.
2. Scale features using StandardScaler.
3. Split data into training and testing sets.
4. Train LinearRegression model on training data.
5. Predict house prices on test data.
6. Evaluate the model performance with MSE and R².
7. (Optional) Generate polynomial features to capture non-linear relationships.
8. Plot predictions against actual values to visualize performance.

## How to Run
- Ensure Python environment with scikit-learn, pandas, matplotlib, numpy.
- Run the script or notebook file sklearn_linear_regression.py.
- Review printed evaluation metrics.
- Inspect plots for model prediction quality.

## Key Files
- sklearn_linear_regression.py (main script with sklearn implementation)
- Dataset CSV file (e.g., boston_housing.csv)

## Learnings
- Using sklearn for efficient and accurate regression.
- Importance of feature scaling.
- Basics of polynomial regression.
- Model evaluation metrics.
- Visualization techniques to understand model fit.
