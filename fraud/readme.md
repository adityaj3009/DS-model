# Fraud Detection Model 🕵️‍♂️💳

This project focuses on detecting fraudulent financial transactions using machine learning. A Random Forest Classifier was trained on a dataset of 6.3 million records to identify suspicious patterns and predict fraud.

## 📁 Dataset
- **Source**: Simulated financial transactions.
- **Size**: 6,362,620 rows × 10 columns.
- **Download CSV**: [Click here to download](https://drive.usercontent.google.com/download?id=1VNpyNkGxHdskfdTNRSjjyNa5qC9u0JyV&export=download&authuser=0)

## 🧠 Model Used
- **Random Forest Classifier**
  - Handles imbalance and large datasets well.
  - Doesn't require feature scaling (scaling still included).

## 🧹 Steps Performed
- Data cleaning (removed ID columns, checked missing/duplicate values)
- Feature encoding for categorical columns
- Correlation analysis to check multicollinearity
- Model training using Random Forest
- Evaluation with accuracy score

## 📊 Model Accuracy
- ✅ **Accuracy Score: 0.99**

## ✅ Result
A simple and effective model that can identify fraudulent transactions based on transaction type, amount, and balance behavior.

---

> Built by Aditya Jalgaonkar
