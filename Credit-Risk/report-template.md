# Module 12 Report Template

## Overview of the Analysis
* Purpose of the Analysis: The purpose of this analysis was to develop machine learning models to predict credit risk. Specifically, we aimed to predict whether a loan is a healthy loan (0) or a high-risk loan (1).

Financial Information: 
* The data used for analysis included various financial features, with the target variable being "loan_status."

Variables: 
* The target variable loan_status had two classes: 0 (healthy loan) and 1 (high-risk loan).

Machine Learning Process Stages:
* Data preprocessing, including splitting the data into training and testing sets.
* Creating and training two logistic regression models (Model 1 and Model 2).
* Evaluating the models using metrics like balanced accuracy, precision, recall, confusion matrices, and classification reports.


## Results

Machine Learning Model 1:
* Balanced Accuracy Score: 0.9443
* Precision for Class 0 (Healthy Loan): 1.00
* Precision for Class 1 (High-Risk Loan): 0.87
* Recall for Class 0: 1.00
* Recall for Class 1: 0.89


Machine Learning Model 2:
* Balanced Accuracy Score: 0.9960
* Precision for Class 0: 1.00
* Precision for Class 1: 0.87
* Recall for Class 0: 1.00
* Recall for Class 1: 1.00


## Summary

Model Performance: 
* Both models perform exceptionally well in predicting healthy loans (Class 0), with high precision and recall. Model 2, however, excels in predicting high-risk loans (Class 1) with perfect recall, indicating that it doesn't miss any high-risk loans.

Recommendation: 
* Model 2 outperforms Model 1 in terms of balanced accuracy and recall for high-risk loans. This suggests that Model 2 is more reliable for identifying high-risk loans, which is crucial for minimizing potential financial losses. Therefore, I recommend using Model 2 for credit risk prediction.

Problem Dependency: 
* The performance of the model depends on the problem's context. If the primary concern is to accurately identify high-risk loans to mitigate financial risks, Model 2 is the preferred choice. However, if balance between precision and recall for both classes is crucial, Model 1 may be considered as it maintains good performance for both classes.
