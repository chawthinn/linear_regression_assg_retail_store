# Regression Model Analysis

In this project, we aim to build various regression models to predict orders using both the retail and store data. The steps involve analyzing the data, performing data preprocessing, feature engineering, and building different types of regression models. Below are the tasks we will complete:

## Tasks

1. **Simple Linear Regression Model**: 
   - Build a simple linear regression model.
   
2. **Linear Regression using SGD**: 
   - Build a linear regression model using Stochastic Gradient Descent (SGD) and adjust the learning rate hyperparameter.

3. **Linear Regression using Ridge**: 
   - Build a linear regression model using Ridge regularization and adjust the regularization hyperparameter.

4. **Linear Regression using LASSO**: 
   - Build a linear regression model using LASSO regularization and adjust the regularization hyperparameter.

5. **Linear Regression using ElasticNet**: 
   - Build a linear regression model using ElasticNet and adjust the L1_ratio hyperparameter.

For each model, we will evaluate the following metrics on both training and test datasets:
- **MSE** (Mean Squared Error)
- **RMSE** (Root Mean Squared Error)
- **R²** (R-Squared)

## Files

- `retail_data_W23.csv`: Contains retail data.
- `retail_orders_W23.csv`: Contains retail order data.
- `store.csv`: Contains store data.

## Instructions

Make sure to run the provided Python notebooks end-to-end and convert them into HTML files before submitting.

## Installation

To run the analysis, ensure the following Python packages are installed:

```bash
pip install pandas scikit-learn numpy matplotlib
