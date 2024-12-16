# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

This analysis aimed to predict whether a loan is healtyh or high-rik using a supervised machine learning model, The dataset consisted of 77,500 records about loan and borrower information, with 2500 loans classified as high-risk. The data was split into labels (loan status) and features (seven columns), then divided into training and testing datasets. A logistic regression model with the 'lbfgs' solver was most suitable for binary classification, the model was trained on training data, and predictions were evaluated by comparing them to te test labels.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

Accuracy: 0.99185
Balanced Accuracy: 0.95205
Precision
Healthy: 1.00
High-Risk: 0.85
Recall
Healthy: 0.99
High-Risk: 0.91
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

 The logistics regression model seems to predict healthy loans well, but it misclassifies about 10% of high risk loans as healthy, there are not many high-risk loans in the data so maybe dding more could help. Preventing high-risk loans might be more importantsince defaults could not more than the interest from healthy loans.
If you do not recommend any of the models, please justify your reasoning.
