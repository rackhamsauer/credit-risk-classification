# credit-risk-classification

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
The purpose of the analysis was to create a data model that predicts the credit worthiness of borrowers from peer to peer lending data.
* Explain what financial information the data was on, and what you needed to predict.
The data included how much the loan value was for, interest rate, the borrower income, their debt to income ration, number of accounts they had, any derogatory marks, their total debt.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
I was trying to predict if they would default on their loan.
* Describe the stages of the machine learning process you went through as part of this analysis.
Test/train, fit, predict process.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
Logistic Regression
## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

              precision    recall  f1-score   support

           0       1.00      1.00      1.00     18759
           1       0.87      0.95      0.91       625

    accuracy                           0.99     19384
   macro avg       0.94      0.97      0.95     19384
weighted avg       0.99      0.99      0.99     19384

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

Precision:The model's performance metrics indicate that it is predicting healthy loans (0) with very high accuracy but is slightly less accurate in predicting risky loans (1).
Precision: Precision measures the accuracy of positive predictions. For healthy loans, the precision is 1.00, which means that when the model predicts healthy loans, it is almost always correct. For risky loans, the precision is 0.87, indicating that when the model predicts risky loans, it is correct about 87% of the time.
Recall: Recall measures the ability of the model to find all the relevant cases within a dataset. For healthy loans, the recall is 1.00, indicating that the model is able to identify almost all instances of healthy loans. For risky loans, the recall is 0.95, meaning that the model is able to capture about 95% of the instances of risky loans.

Accuracy: Accuracy measures the overall correctness of the model across all classes. The accuracy of this model is 0.99, indicating that it correctly predicts the class for approximately 99% of the instances in the dataset.


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

In summary, the model performs well for healthy loans but slightly less accurately for risky ones. However, with an overall accuracy of 99%, it seems to be a very effective model overall.

With 99% accuracy I would recommend this model. I used peers, tutors, chat gpt, stack overflow and previous assignments to complete this work.
