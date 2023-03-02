# Credit-Card-Approval-Prediction

## Overview
This project aims to predict whether a client is eligible for credit card approval or not, which is a common risk management method in the financial industry. The project uses various features such as gender, car ownership, annual income, education level, and occupation type, among others, to make predictions. The data used in the project was downloaded from Kaggle and includes credit history records of clients, including their status (past due, overdue, paid off, or no loan) and months of balance. By analyzing this data and developing a predictive model, the project can assist financial institutions in making informed decisions regarding credit approvals, reducing risks, and maximizing profitability.

## About Data set
The data set comprises two different data records; one contains the applicant’s record while the other contains the credit record of the applicant.
The data used in the project was downloaded from Kaggle : https://www.kaggle.com/code/saurav12suman/credit-card-approval/input

## Modeling
The following are the algorithms used in this project:
- Logistic Regression
- Decision Tree Classification
- Random Forest Classification
- Support Vector Machines
- K-Nearest Neighbours
- XG boost

## Model Comparison Before and after SMOTE

<img width="554" alt="image" src="https://user-images.githubusercontent.com/112019616/222548911-68d9dff8-6357-49ca-8a7a-eb1ffa365035.png">



## Conclusion
In conclusion, the project aimed to predict whether a client is eligible for credit card approval or not, using various features. The project encountered an issue with imbalanced data and addressed it using SMOTE for oversampling. Six models were used to predict client eligibility, and the project found that XGBoost had the highest accuracy after oversampling. After performing cross-validation, logistic regression and random forest classification were found to have the highest accuracies. Overall, the project demonstrated that using various models and techniques can effectively predict credit card eligibility and address imbalanced data issues

