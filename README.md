# Module 12 Report Template
Machine learning techniques used to identify/analyze potential positive customers using different types of loans and other factors from the data provided by the lending services company.
## Overview of the Analysis
Factors considered:
•	the size of the loan
•	its interest rate
•	the borrower's income
•	the debt to income ratio
•	the number of accounts the borrower held
•	derogatory marks against the borrower
•	the total debt
The datat set is 77k+ long. It was split into training and testing sets. The training set was used to build an initial logistic regression model using the logisticRegression module from scikitlearn. Testing dataset was then applied. 

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

Logistic Regression Model:
•	Precision Score: 92% --> This means 92% of predicted positives were correct
•	Recall Score: 95% --> this means that the model was 95% precise in measuring true positive values our of all positive predictions made.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

I recommend using this model to predict, as it has over 95% in predicting the outcome of the repayment of loans. The accuracy range can be modeled by other lenders in ensure they identify the borrowers that will allow them remain/profit in this business.


