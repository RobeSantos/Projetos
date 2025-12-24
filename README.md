# Simple Linear Regression: Age vs Weight Prediction

## Project Overview


This project aims to analyze the relationship between age and weight using Simple Linear Regression, building a predictive model capable of estimating a person’s weight based on their age.
Despite its simplicity, this project demonstrates essential concepts of data analysis, statistical modeling, and model evaluation, making it a strong example of an end-to-end Data Science workflow.

## Problem Description

The main objective of this project is to:
  Analyze the relationship between age and weight
  Build a linear regression model to predict weight based on age

This analysis is important for:
  Understanding growth and development patterns throughout childhood and adolescence
  Demonstrating how reliable predictions can be built even with a small dataset
  Applying linear regression in a practical, interpretable, and reproducible way

## Dataset Challenges & Solution

One of the main challenges of this project is the limited amount of available data.

To address this issue, a balanced oversampling function was implemented:
  It increases the number of samples per age group
  Maintains the original data distribution
  Enables more robust model training and better generalization
  This approach ensures the regression model is not biased toward underrepresented age values.

## Methodology

The project follows these steps:

  Exploratory Data Analysis (EDA)
    Visual inspection of age vs weight relationship
    Detection of patterns and trends
  
  Data Augmentation
    Balanced oversampling to increase sample size
  
  Modeling
    Simple Linear Regression
  
  Model Evaluation
    Performance evaluated on training and test datasets

## Model Evaluation Metrics

The final model is evaluated using the following metrics:

  R² (Coefficient of Determination)
  Measures how well the model explains the variability of the target variable.
  
  MAE (Mean Absolute Error)
  Indicates the average magnitude of prediction errors.
  
  RMSE (Root Mean Squared Error)
  Penalizes larger errors and provides a robust measure of prediction accuracy.
  
These metrics ensure that the model delivers accurate, consistent, and interpretable predictions on both training and testing data.
