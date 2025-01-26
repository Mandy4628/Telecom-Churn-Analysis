# Telecom Customer Churn Prediction
This repository contains a machine learning project aimed at predicting customer churn in the telecom industry using Gradient Boosting. The project involves data preprocessing, hypothesis testing, and building predictive models to identify key factors influencing customer retention.

## Overview
Customer churn is a significant challenge in the telecom industry. This project explores how machine learning, specifically Gradient Boosting, can be used to predict churn and help businesses retain customers. By analyzing contract types, usage patterns, and other features, the model provides actionable insights for retention strategies.

## Key Objectives
-Understand the factors influencing customer churn.;
-Build a Gradient Boosting model to predict churn effectively.;
-Recommend strategies to reduce churn and improve customer retention.

## Dataset
The dataset contains anonymized information about telecom customers, including:

Demographics: Age, gender, marital status.;
Usage Patterns: Monthly data usage, long-distance charges.;
Contract Details: Contract type, monthly fees, total charges.;
Customer Status: Stayed, churned, or newly joined.

## Project Workflow
The project follows these steps:

### Data Preprocessing:
-Handled missing values and outliers.;
-Categorical variables were encoded using OneHotEncoder.;
-Scaled numeric data using StandardScaler.

### Feature Engineering:
-Created new features such as tenure categories and usage ratios.;
-Visualized feature distributions with histograms and boxplots.

## Hypothesis Testing:
Tested the impact of contract type and online security on churn using Chi-Square tests.

### Model Development:
-Built and evaluated a Gradient Boosting model.;
-Hyperparameter tuning using RandomizedSearchCV.

### Model Evaluation:
-Evaluated using metrics like accuracy, ROC-AUC, and F1-score.;
-Visualized feature importance and confusion matrices.

### Insights & Recommendations:
-Contract type and online security were identified as critical factors.;
-Discount strategies showed limited impact, suggesting more targeted approaches.

## Technologies Used
### Programming Language:
Python
### Libraries:
-Data Handling: pandas, numpy;
-Visualization: matplotlib, seaborn;
-Modeling: scikit-learn;
-Statistical Testing: scipy, statsmodels

## Model Performance
-Gradient Boosting Model;
-Accuracy: 80%;
-ROC-AUC Score: 0.926;
-Mean Absolute Error: 0.35;
-Feature importance revealed that contract type and online security are key predictors of churn.
 
