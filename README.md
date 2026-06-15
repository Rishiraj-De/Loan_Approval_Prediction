# 🏦 Loan Approval Prediction System

![Python](https://img.shields.io/badge/Python-3.13-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blueviolet)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview

The **Loan Approval Prediction System** is a Machine Learning classification project designed to predict whether a loan application will be approved based on an applicant's financial, demographic, and credit-related information.

This project demonstrates a complete ML workflow, including:

* Data Cleaning
* Missing Value Handling
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Feature Encoding
* Feature Scaling
* Model Training & Evaluation
* Performance Optimization

---

## 🎯 Problem Statement

Financial institutions receive thousands of loan applications every day. Evaluating each application manually can be time-consuming and prone to human bias.

The objective of this project is to build a Machine Learning model capable of predicting loan approval decisions based on applicant information.

---

## 📊 Dataset Features

| Feature            | Description                     |
| ------------------ | ------------------------------- |
| Applicant Income   | Monthly income of applicant     |
| Coapplicant Income | Monthly income of co-applicant  |
| Age                | Applicant age                   |
| Dependents         | Number of dependents            |
| Credit Score       | Creditworthiness score          |
| Existing Loans     | Number of existing loans        |
| DTI Ratio          | Debt-to-Income Ratio            |
| Savings            | Applicant savings               |
| Collateral Value   | Value of collateral             |
| Loan Amount        | Requested loan amount           |
| Loan Term          | Loan duration                   |
| Employment Status  | Employment category             |
| Marital Status     | Applicant marital status        |
| Property Area      | Rural / Urban / Semiurban       |
| Education Level    | Educational qualification       |
| Gender             | Applicant gender                |
| Employer Category  | Government / Private / MNC etc. |

Target Variable:

**Loan Approved (Yes / No)**

---

## 🔍 Data Preprocessing

### Missing Value Handling

Numerical Features:

* Mean Imputation

Categorical Features:

* Most Frequent (Mode) Imputation

### Feature Encoding

* Label Encoding
* One-Hot Encoding

### Feature Scaling

* StandardScaler

---

## 📈 Exploratory Data Analysis

The following analyses were performed:

* Loan Approval Distribution
* Gender Distribution Analysis
* Applicant Income Distribution
* Co-applicant Income Distribution
* Credit Score Analysis
* Outlier Detection using Boxplots
* Correlation Heatmap

---

## ⚙️ Feature Engineering

To improve model performance, additional features were created:

```python
df["DTI_Ratio_sq"] = df["DTI_Ratio"] ** 2
df["Credit_Score_sq"] = df["Credit_Score"] ** 2
```

These engineered features helped capture non-linear relationships in the data.

---

## 🤖 Machine Learning Models

The following classification algorithms were trained and compared:

### 1. Logistic Regression

* Accuracy: **87.5%**
* Precision: **79.03%**
* Recall: **80.33%**
* F1 Score: **79.67%**

### 2. K-Nearest Neighbors (KNN)

* Accuracy: **77.0%**
* Precision: **66.67%**
* Recall: **49.18%**
* F1 Score: **56.60%**

### 3. Naive Bayes

* Accuracy: **86.5%**
* Precision: **78.33%**
* Recall: **77.05%**
* F1 Score: **77.69%**

---

## 🏆 Best Performing Model

### Logistic Regression

| Metric    | Score  |
| --------- | ------ |
| Accuracy  | 87.5%  |
| Precision | 79.03% |
| Recall    | 80.33% |
| F1 Score  | 79.67% |

The Logistic Regression model achieved the highest overall performance after feature engineering and optimization.

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## 📂 Project Structure

```text
Loan_Approval_Prediction
│
├── Loan_Approval_Prediction.ipynb
├── loan_approval_data.csv
├── README.md
└── .gitignore
```

---

## 🚀 Future Improvements

* Streamlit Dashboard Deployment
* Hyperparameter Tuning
* Ensemble Models
* XGBoost Integration
* Model Explainability (SHAP)
* Cloud Deployment

---

## 📷 Project Screenshots

### Dataset Overview

(Add Screenshot Here)

### Correlation Heatmap

(Add Screenshot Here)

### EDA Dashboard

(Add Screenshot Here)

### Model Comparison

(Add Screenshot Here)

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

* Data Cleaning and Preprocessing
* Feature Engineering
* Exploratory Data Analysis
* Machine Learning Classification
* Model Evaluation
* Git & GitHub Version Control

---

## 👨‍💻 Author

**Rishiraj De**

Computer Science Engineering Student
KIIT University

GitHub: https://github.com/Rishiraj-De

---

⭐ If you found this project useful, consider giving it a star!
