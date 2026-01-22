![Python](https://img.shields.io/badge/Python-3.x-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)

# Heart Disease Prediction using Machine Learning

## 📌 Project Overview
This project focuses on building an end-to-end machine learning pipeline
to predict the presence of heart disease based on patient clinical data.
The goal is to compare multiple classification models and identify the most
stable and interpretable solution.

## 🧠 Problem Statement
Heart disease is one of the leading causes of mortality worldwide.
Early detection using machine learning can assist healthcare professionals
in making informed decisions and improving patient outcomes.

## 📊 Dataset
- Source: UCI Heart Disease Dataset
- Features include age, cholesterol level, blood pressure,
  maximum heart rate, and other clinical attributes.
- Target variable:
  - `0` → No heart disease
  - `1` → Presence of heart disease

## ⚙️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 🔄 Machine Learning Workflow
1. Data loading and inspection
2. Exploratory Data Analysis (EDA)
3. Train-test split
4. Feature scaling using `StandardScaler`
5. Model training using pipelines
6. Cross-validation for performance evaluation
7. Model comparison and selection

## 🤖 Models Trained
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

## 📈 Model Evaluation
- Stratified K-Fold Cross Validation
- Accuracy Score
- Confusion Matrix
- Classification Report

Logistic Regression showed the most stable performance across folds,
making it suitable for this healthcare-related classification task.

## ✅ Key Results
- Built a clean and reusable ML pipeline
- Prevented data leakage using pipelines
- Achieved consistent performance with Logistic Regression
- Demonstrated an end-to-end applied machine learning workflow

## 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook Heart_Disease_Prediction.ipynb
