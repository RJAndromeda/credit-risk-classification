# Module 20: Credit Risk Classification

## Overview of the Analysis

A logistic regression analysis of lending data was undertaken in this challenge. 

* The purpose of the analysis was to build and evaluate a model that can identify the creditworthiness of borrowers.
* The financial information included the borrower's loan size, interest rate of the loan, their income, debt-to-income, the number of accounts they hold, any negative marks listed (derogatory marks), their total debt, and finally, loan status. From this historical data, we should be able to predict the likelihood of a borrower holding a healthy, or an at-risk of defaulting loan. 
* The Loan Status (loan_status) was the dependent variable; the other information (loan_size, interest_rate, borrower_income, debt_to_income, num_of_accounts, derogatory_marks, total_debt) were the independent variables. 
* The stages of the machine learning process undertaken were: reading in the data and splitting it into training and testing sets using train_test_split; fitting the LogisticRegression  model using the training data (x_ and y_train); and finally, evaluated performance by using the X_test data and the fitted model, then generating a confusion matrix and printing a classification report and analysing the results.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

The balanced accuracy scores and the precision and recall scores  for the Machine Learning Model - Logistic Regression:

* * Accuracy of model is 0.99, or 99%

  * Healthy Loan Precision and Recall are both 1, or 100%

  * The At Risk Loan precision is 0.87, recall is 0.89

    

## Summary

The logistic regression model works well in this situation. The precision and recall results for healthy loans excellent, and the at-risk prediction performs strongly, though not quite as strongly as the healthy loan.

It would be suitable to use this model to predict the creditworthiness of borrowers. The model predicts with a sufficient degree of accuracy to suit the needs of a company looking for an assessment of at-risk borrowers for remedial action.

As in most cases, if a higher degree of action were required for a final decision on the status of the loan, a model producing a higher degree of precision and accuracy would be recommended, above 90%, rather than this model. 

However, for this case, the model is recommended, because the performance is dependent on predicting creditworthiness, rather than providing a judgement. The model performs with an accuracy percentage of 99%, and a recall percentage of 89% for predicted at-risk loans, which would be an acceptable performance for the task.

