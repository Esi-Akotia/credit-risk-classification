# credit-risk-classification

## Credit Risk Analysis Report

### Overview

#### Purpose of the Analysis:
The purpose of this analysis is to develop a machine learning model that can accurately predict the creditworthiness of borrowers using financial information from historical lending data.

#### Financial Information and Prediction Target:
The data consists of various financial attributes of borrowers, such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The task is to predict the likelihood of a loan being high-risk (label '1') or healthy (label '0') based on this information.

#### Variables Overview:
* loan_status (Target Variable): Binary variable indicating whether a loan is healthy (0) or has a high risk of defaulting (1).
* Other features: Various financial attributes of borrowers.

#### Stages of Machine Learning Process:

1. Data preprocessing: Reading and exploring the dataset, separating features and target variable, handling any missing or categorical data.
2. Model selection: Choosing appropriate machine learning algorithms for binary classification tasks.
3. Model training and evaluation: Training models on the training dataset and evaluating their performance using metrics like accuracy, precision, and recall.
4. Model comparison: Comparing the performance of different models to identify the most suitable one.

#### Methods Used:
* Logistic Regression: A commonly used algorithm for binary classification tasks due to its simplicity and interpretability.

### Results
#### Machine Learning Model 1: Logistic Regression
* Accuracy: 99%
* Precision (0): 100%
* Precision (1): 86%
* Recall (0): 100%
* Recall (1): 91%

### Summary
#### Model Performance:
* The logistic regression model demonstrates outstanding performance, achieving high accuracy, precision, and recall scores for both healthy and high-risk loans.
* It correctly predicts the vast majority of both healthy and high-risk loans, as indicated by the high precision and recall scores.

#### Recommendation:
The logistic regression model seems to perform best based on its high accuracy and balanced precision-recall scores.
Performance may vary depending on the problem being addressed, but in the context of credit risk analysis, it is crucial to accurately predict both healthy and high-risk loans. The logistic regression model achieves this balance effectively.
Hence, I recommend utilizing the logistic regression model for predicting credit risk in future lending decisions.