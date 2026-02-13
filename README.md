# ❤️ End-to-End Heart Disease Classification

## 📌 Project Overview

This project builds a complete end-to-end machine learning pipeline to predict the presence of heart disease using clinical patient data.

The objective is to analyze medical attributes and develop a reliable classification model that assists in early detection and risk assessment.

---

## 🎯 Problem Statement

Heart disease is one of the leading causes of death globally. Early prediction of high-risk patients can significantly improve treatment outcomes.

This project aims to:

- Perform exploratory data analysis (EDA)
- Identify important predictive features
- Train multiple classification models
- Tune hyperparameters for optimization
- Evaluate and compare model performance

---

## 📊 Dataset Information

- Source: UCI Heart Disease Dataset  
- Total Records: 303 patients  
- Features: 14 clinical attributes  
- Target Variable:
  - `0` → No Heart Disease
  - `1` → Heart Disease Present

### Key Features Include:
- Age
- Sex
- Chest Pain Type (cp)
- Resting Blood Pressure (trestbps)
- Cholesterol (chol)
- Maximum Heart Rate Achieved (thalach)
- ST Depression (oldpeak)
- Number of Major Vessels (ca)
- Thalassemia (thal)

---

## 🔎 Exploratory Data Analysis (EDA)

The following analysis was performed:

- Target distribution visualization
- Correlation heatmap
- Feature relationship analysis
- Data quality checks
- Class balance evaluation

Insights from EDA were used to guide model selection and evaluation strategy.

---

## 🤖 Models Implemented

The following machine learning models were trained and evaluated:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest Classifier

### 🔧 Hyperparameter Tuning

The KNN model was optimized by testing multiple values of K to improve performance.

---

## 📈 Model Performance

### ✅ Best Performing Model
- Accuracy: **~89%**
- Precision: 0.89
- Recall: 0.89
- F1-score: 0.89

Evaluation was conducted using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
---

## 💼 Business Impact

A predictive system like this can:

- Assist doctors in early diagnosis
- Improve preventive healthcare strategies
- Reduce risk of severe cardiac events
- Support data-driven clinical decision-making

This project demonstrates practical application of machine learning in healthcare analytics.

---

## 🚀 Future Improvements

- Cross-validation optimization
- Feature importance analysis
- Model explainability using SHAP
- Deployment using Streamlit
- API integration for real-world applications

---

## 👨‍💻 Author

**Vishal Suralkar**  
Aspiring Data Analyst | Machine Learning Enthusiast
