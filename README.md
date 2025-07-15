# OIBSIP_domain_task_no_3
## Problem Statement :
The used car market is vast, and accurately pricing a vehicle is essential for both sellers and buyers. The goal is to build a regression model that can predict the selling price of a used car based on features like its brand, manufacturing year, fuel type, kilometers driven, and more.

## Objective :
To develop a machine learning model that accurately predicts the selling price of used cars using historical data. This involves data preprocessing, model selection, training, evaluation, and comparison of different regression algorithms.

## Steps Performed :
1. Data Collection & Loading :
Imported the dataset (CSV format) containing car details and prices.

2. Data Exploration & Visualization :
Analyzed data distribution using histograms, boxplots, and correlation heatmaps.
Identified important features influencing the car price.
3. Data Preprocessing :
Handled missing values and outliers
Encoded categorical variables (Fuel Type, Seller Type, etc.)
Removed irrelevant columns like car names or registration number
Scaled numerical features where necessary (for SVR)
4. Model Building :
Trained and tested multiple regression models:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
Support Vector Regressor (SVR)
XGBoost Regressor

## Model Evaluation :
Compared model performance using:

R² Score
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)

## Visualization :
Feature importance bar chart
Residual error plots
Predicted
## Tools and Technologies Used :
Language: Python
Platform: Jupyter Notebook / Google Colab
Libraries:
pandas, numpy – data manipulation
matplotlib, seaborn – data visualization
sklearn – preprocessing, model building & evaluation
xgboost – advanced regression model

## Dataset Description :
Features:
Year (of manufacture)
Present Price (current ex-showroom price)
Kms Driven
Fuel Type (Petrol, Diesel, CNG)
Seller Type (Dealer / Individual)
Transmission (Manual / Automatic)
Owner (Number of previous owners)
Target:
Selling Price (price expected by seller)
Rows: 301

## Outcome :
Built a regression model that predicts car prices with high accuracy.
Identified key features influencing car prices: Year, Present Price, and Fuel Type.
Enhanced understanding of regression techniques and evaluation metrics.
Improved skills in data preprocessing and feature engineering.

## Conclusion :
This project demonstrates how machine learning can be applied to solve real-world problems like used car price estimation. The selected model (Random Forest) performed with an R² score of 97%, proving its effectiveness in capturing complex relationships in the dataset.
