# Credit-risk Classification

## Overview of the Analysis

A machine learning model was built to classify which potential loans should be considered high risk based on historical lending data from a peer-to-peer lending services company. The goal of this model is to identify which potential loans have a high risk of defaulting.
Analysis of the model was conducted in order to assess its viability and accuracy in achieving said goal. 
The model uses the following features in assessing the risk of default for a potential loan:
*Loan Size
*Interest Rate
*Borrower Income
*Debt-to-Income Ratio
*Number of Accounts
*Derogatory Marks
*Total Debt

The model predicted whether or not someone was likely to default on their loan based on historical data of people defaulting or not defaulting on their loans with all these metrics. 
In order to accomplish this task, the data was  split between a training and testing set. The historical results of defaulting were kept in the training data and removed from the testing data (but kept elsewhere to later evaluate the model).
Then, a `Logistics Regression` model was trained on the training data set. Once training was done, the model was used to predict the results of the testing data set and then compared to the actual historical results. Finally, the model was evaluated for its accuracy and other metrics to see if it would be useful in classifying high risk loans.
   
In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
