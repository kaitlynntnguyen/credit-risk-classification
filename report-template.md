# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

  The purpose of the analysis is to determine credit worthiness of potential borrowers.
  The financial information used to determine this included the borrower's loan amount (loan_size), interest rate (interest_rate), income (borrower_income), debt to income ratio (debt_to_income), number of accounts open (num_of_accounts), late payments (derogatory_marks), total debt (total_debt), and loan status (loan_status). This predicts how trustworthy the borrower is and how likely they are to pay back their loan.
Using these factors, the model will predict whether a loan is healthy or if it has a high risk of defaulting. The dataset includes 75,000 healthy loans, and 2500 risky loans. The first part of the process is to load the data and split it into training groups and testing groups. 75% of the data is used to train the model, and then we can use the remaining 25% of the data to make predictions, then test whether those predictions were accurate. With this dataset, we will use Logistic Regression, then we will try it again with resampled training data.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
accuracy score : 95% accurate
Precision: 100% precise in predicting '0 healthy loans' 
           84% precise inpredicting '1 high-risk loans'
Recall: 99% correctly classified '0 healthy loans' 
        91% correctly classified '1 high-risk loans'


* Machine Learning Model 2:
accuracy score : 99% accurate
Precision: 100% precise in predicting '0 healthy loans' 
          84% precise in predicting '1 high-risk loans'
Recall: 99% correctly classified '0 healthy loans'
        99% correctly classified '1 high-risk loans'

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
The second model with the resampled data performed slightly better than the first model. It is about 7% more accurate at detecting high risk loans. It is more important to be able to predict the O's (high risk loans) because those are less common and pose a greater threat to lenders. 


