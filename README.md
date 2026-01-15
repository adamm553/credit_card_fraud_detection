# Credit Card Fraud Detection Project

Project is also available in polish.

## 1. Project Overview
The goal of this project is to build a machine learning pipeline to detect fraudulent credit card transactions. Using a dataset of European cardholder transactions, the project explores various classification algorithms to identify highly imbalanced fraud cases (only 0.17% of total transactions).

## 2. Dataset Description
The dataset contains credit card transactions. 
- **Total Transactions:** 284,807
- **Fraudulent Transactions:** 492 (0.172%)
- **Features:** 28 PCA-transformed features (V1-V28), 'Amount', and 'Time'.
- **Target Variable:** `Class` (1 for Fraud, 0 for Legitimate).

## 3. Methodology
The project follows these key steps:
1. **Exploratory Data Analysis (EDA):** Analyzing transaction patterns and feature distributions.
2. **Data Preprocessing:** Feature scaling (Amount) and removing non-predictive features (Time).
3. **Modeling:** Implementing and comparing five different classification models:
   - K-Nearest Neighbors (KNN)
   - Random Forest
   - Naive Bayes
   - Logistic Regression
   - Support Vector Machine (SVM)

## 4. License
The dataset used in this project is released under the Open Database License (ODbL) v1.0. The original data was collected and analysed by a collaboration of Worldline and the Machine Learning Group (https://www.google.com/search?q=http://mlg.ulb.ac.be) of ULB (Université Libre de Bruxelles) on big data mining and fraud detection. More details on the license can be found on the Kaggle Dataset Page.
