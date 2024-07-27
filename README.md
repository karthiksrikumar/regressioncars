# Car Purchasing Analysis

## Overview

This project analyzes car purchasing data to understand the relationships between various numerical features and the amount spent on cars. The analysis includes data preprocessing, visualization, and modeling using Linear Regression and Lasso Regression.

## Requirements

Ensure you have the following Python libraries installed:

- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `scikit-learn`

You can install the necessary libraries using pip:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn
Data
The dataset is assumed to be in a CSV file named car_purchasing.csv. It includes various features related to car purchases.

Steps:
###Load Data

Read the dataset from a CSV file using pandas.
Data Preprocessing

Convert text data to numerical features.
Rename columns for clarity.
Select only numerical columns for analysis.
###Visualization

Plot a heatmap of the correlation matrix to understand feature relationships.
Generate binned histograms to analyze the relationship between age, salary, and net worth with car purchase amount.


### Linear Regression:
Standardize features.
Train a Linear Regression model and evaluate its performance using R-squared.
Lasso Regression:
Train a Lasso Regression model with regularization.
Perform Grid Search to find the best alpha parameter.
Evaluate and compare model performance on training and test sets.
Cross-Validation:
Evaluate model performance using cross-validation.
