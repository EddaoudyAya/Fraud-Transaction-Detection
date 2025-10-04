# Credit Card Fraud Detection

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-0.24-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## 📌 Overview
This project focuses on detecting **fraudulent credit card transactions** using machine learning techniques.  
The goal is to build a reliable model that distinguishes between **normal transactions (0)** and **fraudulent transactions (1)** while addressing **data imbalance**.

## 📂 Dataset
- The dataset contains credit card transactions labeled as:
  - `0` → Normal transaction  
  - `1` → Fraudulent transaction  
- Fraud cases are rare, making the dataset highly imbalanced.  
- Techniques applied to handle imbalance include **undersampling, oversampling, and balanced sampling**.  
- Source: [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## ⚙️ Installation & Requirements
Install the required Python packages:


```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
Tip: Use a virtual environment to manage dependencies.


