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

##🚀 Usage
Clone this repository:

bash
Copier le code
git clone https://github.com/EddaoudyAya/Credit-Card-Fraud-Detection.git
Navigate to the folder and open the Jupyter Notebook:

bash
Copier le code
jupyter notebook "credictcarddetection (1).ipynb"
Run the notebook step by step:

Data loading & preprocessing

Exploratory Data Analysis (EDA)

Handling imbalance

Model training & evaluation

Results & conclusion

🗂️ Project Structure
bash
Copier le code
Credit-Card-Fraud-Detection/
│
├── data/                   # Raw and processed datasets
│   └── creditcard.csv
├── notebooks/              # Jupyter notebooks
│   └── credictcarddetection (1).ipynb
├── models/                 # Trained models saved as .pkl
├── visuals/                # Plots and graphs
├── README.md
└── requirements.txt
🧠 Features & Methodology
Data Preprocessing: cleaning, scaling, and balancing.

Exploratory Data Analysis (EDA): visualization of transaction distributions.

Models Tested:

Logistic Regression

Decision Tree

Random Forest

Support Vector Machine (SVM)

XGBoost

Evaluation Metrics:

Accuracy

Precision, Recall, F1-score

ROC-AUC

📊 Results
The notebook provides a comparison of models and highlights the most effective approach for detecting fraudulent transactions while minimizing false negatives.

Example Result Visual

🔮 Future Work
Explore deep learning techniques such as LSTMs and Autoencoders.

Deploy the model into a real-time fraud detection system.

Experiment with advanced resampling strategies like SMOTE.

Integrate the model with web applications or dashboards for real-time monitoring.

💡 Key Takeaways
Fraud detection requires careful handling of imbalanced datasets.

Ensemble methods like Random Forest and XGBoost often outperform single models.

Evaluation should focus on precision, recall, and F1-score, not just accuracy.

📚 References
Credit Card Fraud Detection Dataset - Kaggle

Géron, Aurélien. Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow

Chollet, François. Deep Learning with Python

👩‍💻 Author
Eddaoudy Aya
Engineering Student in Data Science, Big Data & AI

Email: eddaoudy.aya@etu.uae.ac.ma

GitHub: github.com/EddaoudyAya

LinkedIn: Aya Eddaoudy
