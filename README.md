# Credit-Card-Approval-Prediction

## Overview
This project aims to predict whether a client is eligible for credit card approval or not, which is a common risk management method in the financial industry. The project uses various features such as gender, car ownership, annual income, education level, and occupation type, among others, to make predictions. The data used in the project was downloaded from Kaggle and includes credit history records of clients, including their status (past due, overdue, paid off, or no loan) and months of balance. By analyzing this data and developing a predictive model, the project can assist financial institutions in making informed decisions regarding credit approvals, reducing risks, and maximizing profitability.

## About Data set:
The data set comprises two different data records; one contains the applicant’s record while the other contains the credit record of the applicant.
The data used in the project was downloaded from Kaggle : https://www.kaggle.com/code/saurav12suman/credit-card-approval/input

## Modeling:
The following are the algorithms used in this project:
- Logistic Regression
- Decision Tree Classification
- Random Forest Classification
- Support Vector Machines
- K-Nearest Neighbours
- XG boost

##Model Comparison Before and after SMOTE

<img width="554" alt="image" src="https://user-images.githubusercontent.com/112019616/222548911-68d9dff8-6357-49ca-8a7a-eb1ffa365035.png">



##Conclusion
We have used 6 models to predict bad and a good client. Our data was imbalanced, so we performed SMOTE for oversampling and we then compared before and after sampling. We see before sampling Logistic regression, Random forest and Support Vector Machines had the best accuracy with 78.8%,  but after sampling it seemed to increase XGBoost accuracy by 9%, from 75.7% to 84.05%. 

