# 💳 Credit Card Fraud Detection

## 📌 Project Overview

This project demonstrates the use of machine learning techniques to detect fraudulent credit card transactions. Using a dataset with anonymized features and class imbalance, the goal is to build a predictive model that can accurately classify transactions as fraudulent or legitimate.

## 🎯 Objectives

- Apply machine learning to detect fraudulent activity in credit card transactions.
- Handle highly imbalanced data effectively.
- Evaluate performance using appropriate metrics beyond accuracy.

## 📊 Dataset

- **Source:** Kaggle – Credit Card Fraud Detection Dataset  
  [Link](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- **Records:** 284,807 transactions
- **Fraudulent Transactions:** 492 (0.172%)
- **Features:**
  - `Time`, `Amount`, `Class` (target: 1 = fraud, 0 = legit)
  - `V1` to `V28` (anonymized PCA-transformed features)

## 🛠️ Tools & Libraries

- `pandas`, `numpy` for data manipulation
- `matplotlib`, `seaborn` for visualization
- `scikit-learn` for machine learning
- `imbalanced-learn` for SMOTE and resampling

## 🧠 Key Techniques

- Data preprocessing and normalization
- Handling class imbalance with:
  - **SMOTE (Synthetic Minority Over-sampling Technique)**
- Model Training with:
  - Logistic Regression
  - Random Forest
  - XGBoost
- Evaluation Metrics:
  - Confusion Matrix
  - Precision, Recall, F1-Score
  - ROC-AUC Score

## 📈 Results Summary

The XGBoost and Random Forest classifiers performed best, with ROC-AUC scores above 0.95 after applying SMOTE. These models demonstrated strong potential in real-time fraud detection scenarios, minimizing false positives while identifying most fraud cases.

## 🚀 How to Run

1. Install dependencies:
2. Run the notebook file

✅ Future Enhancements
Deploy model as an API for real-time detection
Integrate with visualization dashboard
Experiment with deep learning approaches (e.g., autoencoders)
   
