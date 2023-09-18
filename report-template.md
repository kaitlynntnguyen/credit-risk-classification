# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
  The purpose of the analysis is to determine credit worthiness of potential borrowers
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
  The financial information used to determine this included the borrower's loan amount (loan_size), interest rate (interest_rate), income (borrower_income), debt to income ratio (debt_to_income), number of accounts open (num_of_accounts), late payments (derogatory_marks), total debt (total_debt), and loan status (loan_status). This predicts how trustworthy the borrower is and how likely they are to pay back their loan.
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
Load the data
Prepare and organize the data into labels and features.
Split the data to training and testing set
Train the model
Test the model (log resgression)
Resample and retest the data (log resgression)
Evaluate the model

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


