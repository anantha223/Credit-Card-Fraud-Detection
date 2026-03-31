**Credit Card Fraud Detection**
**📌 Overview**

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. It analyzes transaction patterns to identify anomalies and prevent financial fraud.

**🎯 Problem Statement**

Credit card fraud is a major issue due to highly imbalanced data where fraudulent transactions are rare.
The goal is to:

Accurately detect fraud
Minimize false negatives (missed frauds)
Improve transaction security
**🏗️ Project Architecture**
Raw Transaction Data
        ↓
Data Preprocessing
(Missing Values, Cleaning)
        ↓
Feature Scaling
(StandardScaler)
        ↓
Handling Imbalance
(SMOTE / Undersampling)
        ↓
Model Training
(Logistic Regression / Random Forest)
        ↓
Model Evaluation
(Precision, Recall, ROC-AUC)
        ↓
Fraud Detection Output
(Fraud / Non-Fraud)
**📊 Dataset**
Contains anonymized credit card transactions
Features include transaction amount, time, and encoded variables
Highly imbalanced dataset (fraud cases are very low)
**⚙️ Approach**
1. Data Preprocessing
Cleaned dataset
Checked for missing values
2. Feature Scaling
Normalized transaction data for better model performance
3. Handling Imbalance
Applied SMOTE / undersampling techniques
4. Model Training
Trained classification models:
Logistic Regression
Random Forest
5. Model Evaluation
Used metrics:
Precision
Recall
F1-score
ROC-AUC
**📈 Results**
Successfully identified fraudulent transactions
Achieved high recall to detect maximum fraud cases
Reduced false negatives significantly
**🚀 Features**
End-to-end ML pipeline
Handles imbalanced data
Multiple model comparison
Real-world financial use case
**🛠️ Tech Stack**
Python
Pandas, NumPy
Scikit-learn
Matplotlib, Seaborn
**▶️ How to Run**
pip install -r requirements.txt
python main.py
