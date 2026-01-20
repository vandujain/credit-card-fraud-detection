# Credit Card Fraud Detection using Machine Learning

## Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques.  
The model classifies transactions as **fraudulent** or **legitimate** based on historical data.

---

## Problem Statement
Credit card fraud causes major financial losses.  
The goal of this project is to build a machine learning model that can identify fraud transactions accurately from highly imbalanced data.

---

## Dataset
- Credit Card Transactions Dataset  
- Target column: `Class`  
  - 0 → Normal transaction  
  - 1 → Fraud transaction  
Dataset link : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
---

## Tools & Technologies
- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## Project Structure
credit-card-fraud-detection/
│
├── notebooks/
│ └── Credit_Card_Fraud_Detection.ipynb
├── models/
│ └── credit_card_model.pkl
├── README.md


---

## Steps Performed
1. Data loading  
2. Data preprocessing  
3. Feature scaling  
4. Train-test split  
5. Model training  
6. Model evaluation  
7. Model saving  

---

## Model Used
- Logistic Regression / Random Forest

---

## Evaluation Metrics
- Precision  
- Recall  
- F1-score  
- ROC-AUC  

---

## Results
- Successfully detected fraudulent transactions
- Improved recall for fraud class
- Reduced false negatives

---
