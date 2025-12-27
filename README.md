# 🎓 Student Performance Prediction System

## 📌 Project Overview
This project focuses on predicting whether a student will **Pass or Fail** based on academic and behavioral factors using **Machine Learning**.  
The system helps in **early identification of at-risk students**, enabling timely academic intervention.

A **Streamlit web application** is built to provide an interactive and user-friendly interface for real-time predictions.

---

## 🎯 Problem Statement
To analyze student performance data and build a predictive model that can accurately classify students as **Pass** or **Fail** using features such as:
- Study hours
- Attendance rate
- Past exam scores
- Final exam score

---

## 📂 Dataset Description
The dataset contains the following columns:

| Feature | Description |
|------|------------|
| Study_Hours_per_Week | Average weekly study hours |
| Attendance_Rate | Percentage of attendance |
| Past_Exam_Scores | Scores in previous exams |
| Final_Exam_Score | Final exam score |
| Pass_Fail | Target variable (Pass / Fail) |

- Dataset is clean and numerical
- No missing values
- Class imbalance present

---

## 🔍 Exploratory Data Analysis (EDA)
- Histograms showed **negative skewness** in most features
- Pairplots revealed **positive relationships** between features and performance
- Correlation heatmap showed **Final Exam Score** as the strongest predictor
- Target variable was **imbalanced**, requiring special handling

---

## ⚙️ Data Preprocessing
- Target variable encoding (Pass = 1, Fail = 0)
- Feature scaling using **StandardScaler**
- Class imbalance handled using **SMOTE**
- Stratified train-test split

---

## 🤖 Models Used
The following models were trained and evaluated:
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- Decision Tree

### 🏆 Final Model
- **Tuned Support Vector Machine (SVM)**
- Hyperparameter tuning using **GridSearchCV**
- Achieved:
  - Accuracy: **100%**
  - Precision, Recall, F1-score: **1.00**
  - ROC-AUC: **1.0**

---

## 🚀 Deployment
A **Streamlit web application** was developed for real-time prediction.
