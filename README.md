# Car Price Prediction Project
## Overview
This project aims to assist a Chinese automobile company in entering the US market by analyzing the factors that significantly influence car prices. A machine learning approach is utilized to build regression models that predict car prices based on various independent variables. The goal is to provide actionable insights inorder to manipulate the design of the cars, the business strategy etc. to meet certain price levels. 
## Problem Description
The company seeks to understand:
* Significant variables that influence the pricing of cars in the American market.
* How well these variables predict car prices.
## Business Goal
* Develop a predictive model to help the company:
* Understand the dynamics of car pricing in the US market.
* Adjust car design and business strategies to meet pricing targets.
## Dataset
The dataset consists of car-related features collected from market surveys across the American market.
##  Data Loading and Preprocessing 
Imported the dataset.
Preprocessing of dataset which includes handling missing values, duplicates and outlier detection.

## Model Implementation
Five regression algorithms were implemented:
* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Gradient Boosting Regressor
* Support Vector Regressor
## Model Evaluation 
The models were evaluated using:
* R-squared (R²)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* Mean Absolute Error (MAE)
  
The Random Forest Regressor emerged as the best-performing model with the highest R² score.

## Feature Importance Analysis 
Identified significant variables influencing car prices:
* Engine Size
* Curb Weight
## Hyperparameter Tuning
Hyperparameter tuning improved the performance of the Random Forest Regressor.
## Results and Insights
The Random Forest Regressor achieved the best results due to its ability to handle non-linear relationships and interactions between variables.
Significant features affecting car price:
Engine Size
Curb Weight
Management can leverage these insights to optimize car design and pricing strategies for the US market.
