# credit-risk-classification


## Overview
A peer-to-peer lending services company has given a dataset `lending_data.csv` that contains their historical lending activity. Within the dataset, each row contains all the data for a single loan.  Columns of the dataset describe information for the loan such as loan size, interest rate, income of the loan borrower, derogatory marks, and total debt.  From this dataset, our objective was to build a model that can identify the creditworthiness of borrowers.
The two methods used for this model were Logistic Regression to create a model and Random Oversampling to compare with the original model.

## Results

Logistic Regression Model with Original Data
* Balanced Accuracy: 0.952
* Healthy Loans
  * Precision: 1.00
  * Recall: 0.99
  * F1-Score: 1.00
* High-Risk Loans
  * Precision: 0.85
  * Recall: 0.91
  * F1-Score: 0.88

| Confusion Matrix | Positive | Negative |
| :----: |:----:| :----: |
| True     | 18663 | 102 |
| False     | 56 | 563 |

Logistic Regression Model with Resampled (ROS) Training Data
* Balanced Accuracy: 0.994
* Healthy Loans
  * Precision: 1.00
  * Recall: 0.99
  * F1-Score: 1.00
* High-Risk Loans
  * Precision: 0.84
  * Recall: 0.99
  * F1-Score: 0.91

| Confusion Matrix | Positive | Negative |
| :----: |:----:| :----: |
| True     | 18649 | 116 |
| False     | 4 | 615 |

## Summary


