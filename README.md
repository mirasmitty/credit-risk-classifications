# credit-risk-classifications

## Overview of the Analysis

The purpose of this analysis was to develop machine learning models to assess credit risk for loan applications. The dataset contained financial information such as loan size, interest rate, borrower income, and debt-to-income ratio, among others. The goal was to predict whether a loan is healthy (0) or high-risk (1). The target variable, "loan_status," was imbalanced, with 75,036 healthy loans and 2,500 high-risk loans. The analysis involved splitting the data into training and testing sets, fitting logistic regression models with both original and resampled data, and evaluating their performance.

## Results

* Machine Learning Model 1:
  * Accuracy Score: 0.9925
  * Balanced Accuracy Score: 0.9680
  * Precision (0): 1.00
  * Recall (0): 0.99
  * Precision (1): 0.84
  * Recall (1): 0.94

* Machine Learning Model 2:
  * Accuracy Score (Resampled): 0.9937
  * Balanced Accuracy Score (Resampled): 0.9936
  * Precision (0) (Resampled): 1.00
  * Recall (0) (Resampled): 0.99
  * Precision (1) (Resampled): 0.84
  * Recall (1) (Resampled): 0.99

## Summary

Based on the results, both machine learning models performed well in predicting healthy and high-risk loans. However, Model 2, which used oversampled data, demonstrated slightly higher accuracy and balanced accuracy scores compared to Model 1. Additionally, Model 2 showed an improvement in recall for high-risk loans from 0.94 to 0.99, indicating its effectiveness in identifying most high-risk cases. Therefore, Model 2 is recommended for use by the lending company as it provides a more comprehensive assessment of credit risk, reducing the likelihood of missing potential high-risk loans and minimizing financial losses associated with defaults.
