Overview:

Purpose of this Analysis:

The purpose of this analysis is to create and evaluate the accuracy of a data model that predicts the credit worthiness of potential borrowers based on the below factors.
loan_size
interest_rate
borrower_income
debt_to_income
num_of_accounts
derogatory_marks
total_debt
loan_status


A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.

As per the analysis

For Healthy Loan
precision : 1.00 and  recall of 0.99 

For High Risk loan
precision : 0.85 and recall of 0.91 

overall accuracy of 0.99

Confusion matrix:
Predicted 0	Predicted 1
Actual 0	18663	102
Actual 1	56	563

Summary
The above result is based on a testing data of 18,765 healthy loans and 619 high risk loans. As the model has a high accuracy (99%), we would recommend the model to the company. The F1-score for the healthy loan is near perfect while that of the high risk loan is 88%, the model would help to mitigate the risk from high risk loans significantly.

