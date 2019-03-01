# Project-1
Sales Prediction Algorithm for Enrollment of Candidate

The objective was to predict the probability of enrollment of the candidate. Logistic regression,
Decision trees and Random forest machine learning algorithm were implemented using Python (numpy, pandas, sklearn,
seaborn packages). The ROC score obtained was 98% and accuracy of model was 96%.

The data was highly unstructured with lot of missing values. Using the relevant statistics it was taken care. Unwanted columns were eliminated during the initial data preprocessing.
New features were also created based on the business requirement.
For example:-First call date and last call date didnt make any sense as feature. But difference between them turned out to be significant feature.

Feature importance was done and top 10 features were identified which had significant effect on enrollment.
Finally, ensemble model was implimented were non technical sales person could enter the details of candidate and predict the probability of enrollment so that suitable course of action can be chalked. 
