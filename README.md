# MiniProject SC1015

## About
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on a bank's marketing campaign to acquire deposits from customers. Please view the source code in order from:

1. [Data Cleaning](https://github.com/WeijunCheah/MiniProject/blob/main/1.%20CleanedDataset.ipynb)
2. [Exploratory Data Analysis(EDA)](https://github.com/WeijunCheah/MiniProject/blob/main/2.%20EDA.ipynb)
3. [Random Forest and Logistic Regression](https://github.com/WeijunCheah/MiniProject/blob/main/3.%20RF_LogR.ipynb)
4. [XGBoost](https://github.com/WeijunCheah/MiniProject/blob/main/4.%20XGBoost.ipynb)
5. [Detailed Conclusion](https://github.com/WeijunCheah/MiniProject/blob/main/5.%20Comparison%20%26%20Conclusion.ipynb)

## Description
- The amount of budget bank companies spend on their marketing campaign increases every year, hence we would like to make use of the budget effectively.
- To increase the effectiveness of the Bank Marketing Campaign by focusing on target clients.
- We aim to analyze the factors influencing customers' decisions to subscribe to term deposits, as well as to predict customer behaviour in future similar marketing campaigns.

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
- The next marketing campaign can focus on potential customers that work as blue collars, married, have house loan and have personal loan to increase the likelihood of suscribing to a term deposit.

## What did we learn from this project
- Handling imbalanced data using SMOTE method
- Concepts about F1 score, Accuracy and AUC score
- Application of different models in solving binary classification problems
- How to collaborate on a project using Github
- Decomposition of problems into smaller components

## Contributors
- @WeijunCheah
- @Tingfeng03

