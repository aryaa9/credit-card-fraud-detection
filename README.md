# 💳 Credit Card Fraud Detection

## 🔍 Overview

This project aims to build a robust and effective Credit Card Fraud Detection system using various machine learning models. The dataset used for this project contains transactions made by credit cards in September 2013 by European cardholders. The dataset is highly unbalanced, with only 0.172% of transactions being fraudulent. The primary goal of this project is to accurately detect fraudulent transactions while minimizing false positives.

## 🗂️ Dataset

The dataset was sourced from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud). It contains 284,807 transactions, with 492 frauds. Due to confidentiality issues, the dataset contains only numerical input variables that are the result of a PCA transformation.

- **🕒 Time**: Number of seconds elapsed between this transaction and the first transaction in the dataset.
- **📊 V1 - V28**: The principal components obtained with PCA.
- **💲 Amount**: Transaction amount.
- **🚨 Class**: The target variable, with 1 indicating fraud and 0 indicating non-fraudulent transactions.



## 🔎 Exploratory Data Analysis (EDA)
The project begins with a comprehensive EDA, where we:

Visualize the distribution of the target variable.
Plot the distribution of transaction amounts.
Create a correlation heatmap to understand feature relationships.
## 🧠 Machine Learning Models 

1️⃣ Logistic Regression

   F1 Score: 0.72
   
2️⃣ Random Forest Classifier

   F1 Score: 0.86
   
3️⃣ XGBoost Classifier
   F1 Score: 0.86
   
## 🚀 Advanced Model: LightGBM
   F1 Score: 0.88
Notes: LightGBM was implemented to improve model performance by handling the imbalanced dataset more effectively.

## 🏁 Results
After implementing and testing various models, the LightGBM model achieved the highest F1 score of 0.88, making it the best-performing model for this project.
