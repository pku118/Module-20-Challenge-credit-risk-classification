# Module-20-Challenge-credit-risk-classification


## Overview of the Analysis

- The goal was to build a model that can identify the creditworthiness of borrowers and predict the loan status as a healthy loan or high-risk loan.
- This analysis was to evaluate using model based on loan risk using the financial information dataset of historical lending activity from a peer-to-peer lending services company.

Stages in the machine learning process include:

1. Splitting the data into training and testing sets
2. Create a Logistic Regression Model with the Original Data and save the predictions
3. Evaluate the model's performance using the accuracy score, confusion matrix, and classification report.

Some of the methods used included creating a Logistic Regression model and using RandomOverSampler to resample the data so it was not imbalanced.

## Results

* Machine Learning Model 1: (Original Data)

  * Model 1 had a balanced accuracy score of 0.95. The 0 (healthy loan) had a precision score of 1.00 and a recall score of .99 while the 1 (high-risk loan) had a precision score of 0.85 and a recall score of .91.
  * This model is less accurate when predicting high-risk loans when compared to the healthy loan based on the lower precision and recall scores
  * The model has imbalanced data so the scores would need to be resampled in order to get an accurate model

## Summary

The initial Logistic Regression model had very nice-looking accuracy scores, however, the data was imbalanced as there were far more 0 (healthy loans) than there were 1 (high-risk loans). Due to the imbalance I would reccommend a resampling of the data to improve the results.
