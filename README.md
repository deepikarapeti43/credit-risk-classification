# credit-risk-classification

Machine learning techniques are used to analyze a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

Overview of the Analysis
In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

Explain the purpose of the analysis.
The purpose of this analysis is to develop a predictive model to assess the risk associated with loans. By using machine learning model it can accurately differentiates the loans whether its healthy or high-risk.

Explain what financial information the data was on, and what you needed to predict.
The dataset contains financial information related to loan_size,interest_rate,borrower_income,debt_to_income,num_of_accounts,derogatory_marks,total_debt,loan_status. The target variable we needed to predict is the loan status, which indicates whether a loan is healthy (0) or high-risk (1).

Provide basic information about the variables you were trying to predict (e.g., value_counts).

Describe the stages of the machine learning process you went through as part of this analysis.

Data Preparation: We began by loading the dataset and prepared the data by creating feature and target variable and by using train split model created train data and test data.

Model Training: By using training data fitted the logistic regression model and saved the predictions on testing data.

Model Evaluation: We evaluated the performance of the logistic regression model by generating a confusion matrix and printing a classification report. This allowed us to find out the healthy and high-risk loans.

Briefly touch on any methods you used (e.g., LogisticRegression, or any other algorithms).

LogisticRegression:- By using this method it finds out whether loan is healthy or high risk based on various factors like (loan_size,interest_rate,borrower_income,debt_to_income)

predict:- After training the logistics it takes new loan as input and predicts the output as healthy or high risk.

confusionmatrix:- Once predictions were made it creates the matrix to show the count of True Negatives,False Positives,True Positives and False Negatives.

classification report:- By using predictions it creates the precision,recall,f1-score and support to correctly classify healthy and high-risk loans

Results
Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

Machine Learning Model 1:
Description of Model 1 Accuracy, Precision, and Recall scores.

Accuracy: It represents the overall correctness of predictions made by Model 1. It tells us the proportion of correctly classified instances (both healthy and high-risk loans) out of all instances.

Precision: It measures the proportion of true positive predictions (correctly predicted high-risk loans) among all instances predicted as high-risk by Model 1. It tells us how many of the predicted high-risk loans were actually high-risk.

Recall scores: It measures the proportion of true positive predictions (correctly predicted high-risk loans) among all actual high-risk loans in the dataset. It tells us how many of the actual high-risk loans were correctly identified by Model 1

Summary
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

Which one seems to perform best? How do you know it performs best?
Logistic regression model performs best for predicting loan risk, accuracy, precision, and recall.

Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the 1's, or predict the 0's? )
Yes, It's important to find out the 0's and 1's to tell the high risk and healthy loans.

If you do not recommend any of the models, please justify your reasoning.
