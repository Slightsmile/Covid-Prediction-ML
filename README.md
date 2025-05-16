# 🦠 Symptom-Based COVID-19 Prediction Using Machine Learning

This project aims to predict the presence of COVID-19 based on user-reported symptoms using various machine learning algorithms. It provides a comparative study of different models to identify the most effective approach for symptom-based diagnosis.

---

## 📌 Project Overview

- **Title**: Symptom-Based COVID-19 Diagnosis: A Comparative Study  
- **Objective**: To predict whether a person has COVID-19 based on symptoms.  
- **Dataset**: [Kaggle - Symptoms and COVID Presence](https://www.kaggle.com/datasets/hemanthhari/symptoms-and-covid-presence)

---

## 📊 Dataset Description

The dataset includes common COVID-19 symptoms and an indicator of infection status.

**Features include:**
- Cough
- Fever
- Sore Throat
- Shortness of Breath
- Headache
- Age
- ...and more

**Target:**
- Presence of COVID-19 (Yes/No)

---

## 🧹 Data Preprocessing

-  Label Encoding (for categorical features)
-  Handling Missing Values
-  Undersampling (to balance the dataset)
-  Correlation Analysis (to remove multicollinearity)
-  Feature Selection (dropping irrelevant features)
-  Train-Test Split (`train_test_split`)

---

## 🧠 Machine Learning Models Used

The following models were implemented and compared:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest
- Support Vector Machine (SVM)
- Naive Bayes

![Screenshot 2025-05-16 124123](https://github.com/user-attachments/assets/5f614d4c-d026-4035-8b45-42555686c413)

---

## 📈 Evaluation Metrics

Each model was evaluated using:

- Accuracy Score
- Confusion Matrix
- Precision, Recall, and F1-Score
- ROC Curve and AUC Score

---

## 📊 Visualizations

- Count Plots for Feature Distributions
- Confusion Matrix Heatmaps
- Feature Importance Plot (Random Forest)
- ROC Curves for Model Comparison

---

## ✅ Conclusion

This project highlights the potential of machine learning for early COVID-19 diagnosis based on symptoms. The comparative study provides insights into the strengths and limitations of different models in handling real-world healthcare data.

---

> Developed as a part of the Data Mining and Machine Learning Lab Project at Daffodil International University.
