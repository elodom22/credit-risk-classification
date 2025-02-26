# credit-risk-classification

## Overview
#### Employ various supervised machine learning techniques to train and evaluate a model based on loan risk. Evaluate a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

#### Data analysis consisted of splitting the data points into training and testing sets, followed by the creation of a logistic regression model using the original data set. The model’s performance was evaluated by generating a confusion matrix and classification report to identify how well the model predicts both healthy and high-risk loans. Features assessed within the data set to determine credit-worthiness include:

* Loan size
* Interest rate
* Borrower name
* Debt to income
* Number of accounts
* Derogatory marks
* Total debt
* Loan status

## Logistic Regression Model Results

* Healthy loans (0):
** Precision = 100%
** Recall = 99%
* High-risk loans (1) 
** Precision = 84%
** Recall = 94%
* machine learning model accuracy = 99%
 
## Summary
#### The logistic regression model predicts healthy loan labels with 100% precision and 99% recall. In regards to high-risk loans, the model makes predictions with 84% precision and 94% recall. One observation from the data is that the lower percentage values predicted from high-risk loans are due to the smaller data set of high-risk loans (2500) in comparison to the larger healthy-loan dataset (75036). The model may better predict high-risk loans with more affiliated high-risk loan data training. However, the model does make predictions with a high degree of accuracy (99%). Therefore, this machine learning model is recommended to determine borrower credit-worthiness for a lending company.
