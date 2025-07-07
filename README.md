# 🩺 Liver Cirrhosis Prediction using Machine Learning

This project aims to predict liver cirrhosis in patients using clinical data and machine learning models. The application leverages modern ML techniques, backed by a Flask web interface, to assist healthcare providers in early detection and decision-making.

---

## 📌 Problem Statement

Liver cirrhosis is a chronic condition where healthy liver tissue is replaced with scar tissue, leading to serious health risks. Early diagnosis is difficult using conventional methods. This project addresses the problem by using machine learning to detect cirrhosis risk early, using patient data such as blood tests, alcohol use, and other liver health metrics.

---

## 🎯 Objectives

- Predict the likelihood of liver cirrhosis based on clinical input data.
- Assist doctors in making early and effective diagnoses.
- Deploy a web-based predictive interface for real-time usage.

---

## 📊 Dataset

The dataset used in this project was sourced from Kaggle:  
🔗 [Liver Cirrhosis Prediction Dataset](https://www.kaggle.com/datasets/bhavanipriya222/liver-cirrhosis-prediction)

**Features Include:**
- Age, Gender
- Alcohol consumption
- Liver enzyme levels (ALT, AST, etc.)
- Albumin, Bilirubin, and other blood test parameters

**Preprocessing Steps:**
- Handling missing values
- Encoding categorical data
- Outlier detection
- Feature scaling
- Train-test splitting

---

## 🤖 Machine Learning Models Used

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest Classifier ✅ *(Selected model)*

The models were evaluated on:
- Accuracy
- Precision
- Recall
- F1-Score

🏆 **Best Accuracy Achieved**: ~98% with Random Forest Classifier

---

## 🔧 Technologies Used

- **Python**: Data processing, model training
- **Scikit-learn**: ML modeling
- **Flask**: Backend web server
- **HTML/CSS**: Simple frontend UI
- **Jupyter Notebook**: Development environment

---

## 🧪 Project Workflow

```mermaid
graph LR
A[Data Collection] --> B[Preprocessing]
B --> C[Model Building]
C --> D[Evaluation]
D --> E[Deployment]
E --> F[Prediction Output]
