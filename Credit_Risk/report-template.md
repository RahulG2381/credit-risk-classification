# Module 12 Report Template

## Overview of the Analysis

Purpose:
The purpose of this analysis was to develop machine learning models to predict loan risk based on financial information. The dataset used in this analysis contained information on various financial attributes of loans, and the goal was to predict whether a loan is healthy (label 0) or high-risk (label 1).

Key variables:
The key variables of interest were the loan labels, where label 0 represented healthy loans and label 1 represented high-risk loans. 
A brief exploration of the dataset revealed the distribution of these labels:

Healthy loans (label 0) had a count of 18,759.
High-risk loans (label 1) had a count of 625.

The machine learning process involved several stages, including data preprocessing, model training, model evaluation, and performance assessment. 

Methods used: Logistic Regression was selected as the primary algorithm for this analysis due to its suitability for binary classification tasks.

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:


## Results

* Logistic Regression Model:
    * Accuracy: 99%
    * Precision (Label 0 - Healthy Loans): 100%
    * Precision (Label 1 - High-Risk Loans): 87%
    * Recall (Label 0 - Healthy Loans): 100%
    * Recall (Label 1 - High-Risk Loans): 95%
    
## Summary

The logistic regression model performed exceptionally well in predicting both healthy and high-risk loans. It achieved perfect precision, recall, and accuracy for healthy loans, indicating that it effectively identified all healthy loans without any false positives or false negatives. Additionally, the model demonstrated high precision and recall for high-risk loans, suggesting its reliability in distinguishing high-risk loans while minimizing misclassifications.

Given the high performance of the logistic regression model across all metrics, it seems to be the most suitable model for predicting loan risk in this scenario. However, it's essential to consider the problem context and requirements. For example, if the focus is primarily on identifying high-risk loans to mitigate potential losses, the model's performance on label 1 (high-risk loans) may be of greater importance. 

In conclusion, the logistic regression model offers a robust solution for predicting loan risk based on financial information, demonstrating high accuracy and reliability across both healthy and high-risk loan categories.





