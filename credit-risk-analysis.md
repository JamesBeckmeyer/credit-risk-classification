## Overview of the Analysis

  In this analysis, we attempt to predict the healthiness of loan using machine learning. We hope to identify high-risk loans from a pool. The values we are using to calcualte risk are:
  
  Loan Size
  Interest Rate
  Borrower Income
  Debt to Income Ratio
  Number of Accounts
  Deragatory Marks
  Total Debt
  Ultimate Loan Status

  We used a logisitic regression model for this analysis. We took the pool of loans and split them into a training group to teach the model, and then a testing group to confirm the model's accuracy. We tested two models, the first using just scaled data, the second using over-sampled data. 

## Results

Below are the ultimate results.

* Machine Learning Model 1:
  * Healthy Loan F1-score: 100%
  * Healthy Loan Precision: 99%
  * Healthy Loan Recall: 100%
  * High Risk Loan F1-score: 91%
  * High Risk Loan Precision: 98%
  * High Risk Loan Recall: 84%
  * Balanced Accuracy Score: 98.9%

* Machine Learning Model 2:
  * Healthy Loan F1-score: 100%
  * Healthy Loan Precision: 99%
  * Healthy Loan Recall: 100%
  * High Risk Loan F1-score: 91%
  * High Risk Loan Precision: 99%
  * High Risk Loan Recall: 83%
  * Balanced Accuracy Score: 99.34%

## Summary

  Both models provide a large amount of accuracy for the overall, but the recall rate on high risk loans indicates that ~16% to ~17% of said loans may be classified as healthy in either model. Any users of the model need to keep this in mind. A high risk lending appetite would appreciate these models as they are likely to not leave any healthy loans on the table. A low risk lending appetite may see more default prone loans than they may hope for. Either grouping should use these models as supplemental resources.  
