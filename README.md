# Credit-Risk-Classification

In this Challenge, I’ll use various techniques to train and evaluate a model based on loan risk. I’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

## Overview Analysis
This dataset consist of 77,536 data points, and was divided into training and testing sets. The training set was use to create an initial logitic regression model named Logistic Regression Model 1. Logistic Regression Model 1 was use in the testing data set to evaluate the level risk (if is high or low)of loans extended to borrowers.

In this analysis we use the following factors to examine the data
- Loan size
- Interest rate
- Borrower's income
- Debt to income ratio
- Number of accounts
- Derogatory marks
- Total debt



  #### The variable has been label as
              0 = Health Loan 
              1 = High Risk Loan

## Results
1. Accuracy Score: 99%
2. Precisions Score: (0) Healthy loans at 100% and (1)High risk loans at 84%
3. Recall Score: (0) Healthy loans at 99% and (1) High risk loans at 94%


## Summary

In conclusion I don't think this is the best model to use because precision results was only at 84%. When it come to taking out a loan, one thing the lenders was to be sure about is getting payed back. Althogh Healthy loans was at a 100%, the Risk loan being at 84% it prove that this model is not the best to use to make the best decisions. 
