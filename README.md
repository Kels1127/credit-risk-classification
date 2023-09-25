# credit-risk-classification

## Overview of the Analysis

The purpose of the analysis is to develop a model using the historical data in order to identify and distinguish between credit worthy and high risk loan applicants. Finally, once developed, the model’s performance is assessed for potential use on future loan applicant data.

This analysis tool uses a dataset of historical lending activity from a lending services company to build a model that can identify the creditworthiness of borrowers based on factors such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts held, number of derogatory marks, total debt, and, lastly, loan status.

The stages of the machine learning process analysis I utilized are:
  -  Data Collection and Preparation
  -  Model Selection
  -  Model Training
  -  Model Prediction
  -  Model Utilization

## Results

Machine Learning Model 1 - Logistic Regression:
  -  Accuracy: 0.9442676901753825
  -  Precision: 1.0 / 0.87
  -  Recall scores: 1.0 / 0.89

Machine Learning Model 2 - Logistic Regression w/ ReSampled Data:
  -  Accuracy: 0.9959744975744975
  -  Precision: 1.0 / 0.87
  -  Recall scores: 1.0 / 1.0

## Summary
Both precision for the logistic regression model, original and fit with oversampled data, were great at detecting healthy loans (1.0) and less accurate at detecting high-risk loans (0.87).

Based on the findings of Machine Learning Model 1 compared to Machine Learning Model 2, I considered recommending using Model 2, Logistic Regression with Resampled Data but I cannot overlook the fact that this dataset is severely imbalanced:  
  -  0 (credit-worthy)	75036
  -  1 (credit risk)	2500

And therefore I recommend further supervised machine learning modeling on a larger and more balanced dataset.
