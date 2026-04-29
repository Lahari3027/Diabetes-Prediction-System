# problem statement 
Implementing a Decision Tree Classifier to Predict Whether a Patient Has Diabetes or Not Based on Their Medical History Using Scikit-learn in Python

# 🩺 Advanced Diabetes Prediction System

An end-to-end Machine Learning project that predicts diabetes risk using healthcare indicators from the BRFSS 2015 dataset.

## 🚀 Project Overview

This project uses Machine Learning algorithms to classify whether a person is diabetic or non-diabetic based on health-related features.

The system includes:
- Data preprocessing
- Feature engineering
- Binary classification
- Model training and evaluation
- Hyperparameter tuning
- Visualization dashboards
- Model saving for deployment

---

## 📂 Dataset

Dataset used: **BRFSS 2015 Health Indicators Dataset**

Source:
https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset

Target Variable:
- `0` → No Diabetes / Pre-diabetes
- `1` → Diabetes

Original target:
- `Diabetes_012`
    - 0 = No diabetes
    - 1 = Pre-diabetes
    - 2 = Diabetes

Converted into binary classification:
- 2 → 1
- 0,1 → 0

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## 🤖 Machine Learning Models

Implemented models:
- Decision Tree Classifier
- Random Forest Classifier

Optimization:
- GridSearchCV Hyperparameter Tuning
- Cross Validation

---

## 📊 Evaluation Metrics

Models evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- ROC Curve
- AUC Score
- Cross Validation Score

---

## 📈 Visualizations

Project includes:

- Confusion Matrix Heatmap
- Feature Importance Graph
- Correlation Heatmap
- Decision Tree Visualization
- ROC Curve
