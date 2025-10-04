# Credit Card Fraud Detection

## 📌 Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques.  
The goal is to build a reliable model that distinguishes between **normal transactions (0)** and **fraudulent transactions (1)** while addressing the issue of data imbalance.

## 📂 Dataset
- The dataset used contains credit card transactions labeled as:
  - `0` → Normal transaction  
  - `1` → Fraudulent transaction  
- Since fraud cases are rare, the dataset is highly imbalanced. To address this, techniques such as **undersampling / oversampling / balanced sampling** were applied.

## ⚙️ Installation & Requirements
Make sure you have the following installed:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
