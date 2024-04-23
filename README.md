# MiniProject SC1015

## About
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on a bank's marketing campaign to acquire deposits from customers. Please view the source code in order from:

1. [Data Cleaning](https://github.com/WeijunCheah/MiniProject/blob/main/1.%20CleanedDataset.ipynb)
2. [Exploratory Data Analysis(EDA)](https://github.com/WeijunCheah/MiniProject/blob/main/2.%20EDA.ipynb)
3. [Random Forest and Logistic Regression](https://github.com/WeijunCheah/MiniProject/blob/main/3.%20RF_LogR.ipynb)
4. [XGBoost](https://github.com/WeijunCheah/MiniProject/blob/main/4.%20XGBoost.ipynb)
5. [Detailed Conclusion](https://github.com/WeijunCheah/MiniProject/blob/main/5.%20Comparison%20%26%20Conclusion.ipynb)
6. [Dataset Used](https://github.com/WeijunCheah/MiniProject/tree/086f9332496ed2a62206ed4b46bc9341e468c9b3/CSV%20Dataset)

## Description
- The amount of budget bank companies spend on their marketing campaign increases every year, hence we would like to make use of the budget effectively.
- Increase the effectiveness of the Bank Marketing Campaign by focusing on target clients to avoid unecessary spending.
- We aim to analyze the common features of customers that subscribe to term deposits, as well as to predict whether a customer would made a deposit in future similar marketing campaigns by looking at their demographics.

## Problem Statement
- What are the characteristics of the potential customers that would likely to make a term deposit?
- Which machine learning model has the best performance?
  
## Dataset
We are using the [Bank Target Marketing](https://www.kaggle.com/datasets/seanangelonathanael/bank-target-marketing/data) from kaggle. This dataset contains various attributes related to customer demographics, their previous interactions with the bank, and the outcomes of the marketing campaign conducted.
  
## Model Used
- Logistic Regression
- Random Forest
- XGBoost

## Result and Interpretation
Significant key features identified by the models
- work as blue collars
- married
- have house loan
- have personal loan
  
The above features of the customer can be explained from the aspects of financial stability, risk aversion, long-term planning and stability in life-stage.

## Conclusion
- Dropping unnecessary columns can reduce complexity of a model
- Through resampling of the highly imbalanced data, the performance metrics of models increase
- Random Forest can handle non-linear relationships between features effectively while minimising the risk of overfitting
- The F1 score of XGBoost is low because the model struggles in classifying the positive and negative instances due to the imbalanced dataset or the hyperparameters used might not be the best.
- The top 4 features obtained from Logistic Regression is different compared to that of Random Forest and XGBoost because Logistic regression assesses feature importance based on the magnitude of coefficients assigned to each variable which may overlook complex nonlinear patterns.
- The next marketing campaign can focus on potential customers that work as blue collars, married, have house loan and have personal loan to increase the likelihood of suscribing to a term deposit.

## What did we learn from this project
- Handling imbalanced data using SMOTE method
- Tuning of the hyperparameters to improve the model's performance
- Concepts about F1 score, Accuracy and AUC score
- Application of different models such as Logistic Regression, Random Forest and XGBoost in solving binary classification problems
- How to collaborate on a project using Github
- Decomposition of problems into smaller components

## Contributors
- @WeijunCheah - Data Cleaning, EDA, XGBoost, Conclusion
- @Tingfeng03 - Data Cleaning, Logistic Regression, Random Forest

## References
- https://www.nickmccullum.com/python-machine-learning/logistic-regression-python/
- https://www.datacamp.com/tutorial/understanding-logistic-regression-python
- https://machinelearningmastery.com/smote-oversampling-for-imbalanced-classification/
- https://www.statology.org/random-forest-in-r/
- https://www.datacamp.com/tutorial/random-forests-classifier-python
- https://www.datacamp.com/tutorial/xgboost-in-python
- https://machinelearningmastery.com/develop-first-xgboost-model-python-scikit-learn/
