# Credit-risk Classification

## Overview of the Analysis

A machine learning model was built to classify which potential loans should be considered high risk based on historical lending data from a peer-to-peer lending services company. In this data, there were 18765 examples of "healthy" loans and 619 examples of loans that were defaulted. The goal of this model is to identify which potential loans have a high risk of defaulting.
Analysis of the model was conducted in order to assess its viability and accuracy in achieving said goal. 
The model uses the following features in assessing the risk of default for a potential loan:
* Loan Size
* Interest Rate
* Borrower Income
* Debt-to-Income Ratio
* Number of Accounts
* Derogatory Marks
* Total Debt

The model predicted whether or not someone was likely to default on their loan based on historical data of people defaulting or not defaulting on their loans with all these metrics. 
In order to accomplish this task, the data was split between a training and testing set. The historical results of defaulting were kept in the training data and removed from the testing data (but kept elsewhere to later evaluate the model).
Then, a `Logistics Regression` model was trained on the training data set. Once training was done, the model was used to predict the results of the testing data set and then compared to the actual historical results. Finally, the model was evaluated for its accuracy and other metrics to see if it would be useful in classifying high risk loans.

## Results

* Logistic Regression Model:
    * This model had an overall accuracy of 99% in properly classifying high risk loans.
    * For "healthy" loans, the model had a 1.00 precision score, .99 recall score, and an F1 score of 1.00.
    * However, for high risk loans, the model had a .85 precision score, .91 recall score, and an F1 score of .88.

## Summary

The model is extremely accuracte when predicting "healthy" loans, but those loans make up the vast majority of the dataset. It is more important to be able to accurately predict the high risk loans that customers may default on because that loses money. 
For this reason, I do no recommend the use of this particular logistic regression model. While an accuracy (F1) score of 88% is still fairly strong for predicting high risk loans, I believe this margin of error is too great to justify use of this model. However, with more knowledge of the business profit margins, this accuracy rate could be potentially acceptable. However, I believe other models or more feature engineering could lead to a more succesful model, especially when it comes to accuractely predicting the risk of defaulting on a loan. 
