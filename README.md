# 📊 IBM Telco Customer Churn — Data Preparation & Preprocessing Pipeline

## Project Overview

This project demonstrates an end-to-end data preparation workflow for Machine Learning using the IBM Telco Customer Churn dataset.

The primary objective was **not** to build the most accurate churn prediction model, but to master the complete data preparation pipeline that every AI/ML Engineer performs before training machine learning models.

The project covers everything from understanding raw data to producing a fully preprocessed dataset ready for machine learning.

---

## Objectives

- Understand an unfamiliar dataset
- Perform professional data cleaning
- Handle missing values and incorrect data types
- Perform Exploratory Data Analysis (EDA)
- Engineer meaningful business-driven features
- Build reusable preprocessing pipelines
- Train and compare baseline machine learning models

---

## Dataset

**IBM Telco Customer Churn Dataset**

- 7,043 customer records
- Customer demographics
- Account information
- Services subscribed
- Billing information
- Target Variable: **Churn**

---

# Project Structure

```
Customer-Churn-Data-Preparation/
│
├── data/
│   ├── raw/
│   │   └── Telco-Customer-Churn.csv
│   │
│   └── processed/
│       └── telco_feature_engineered.csv
│
├── notebooks/
│   ├── 01_Data_Understanding.ipynb
│   ├── 02_Data_Cleaning.ipynb
│   ├── 03_EDA.ipynb
│   ├── 04_Feature_Engineering.ipynb
│   ├── 05_Preprocessing.ipynb
│   └── 06_Baseline_Model.ipynb
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

# Notebook Overview

## 01 — Data Understanding

- Dataset inspection
- Feature categorization
- Target identification
- Data types
- Unique values
- Initial business understanding

---

## 02 — Data Cleaning

- Missing value detection
- Blank space handling
- Data type correction
- TotalCharges conversion
- Duplicate checking
- Data Quality Summary

---

## 03 — Exploratory Data Analysis (EDA)

- Target distribution
- Numerical feature analysis
- Categorical feature analysis
- Churn analysis
- Crosstab visualizations
- Business insights

---

## 04 — Feature Engineering

Created several business-driven features:

- TenureGroup
- TotalServices
- HasSecurityBundle
- AverageMonthlySpend
- IsFamilyCustomer

---

## 05 — Data Preprocessing

Built a reusable preprocessing pipeline using Scikit-learn.

Includes:

- Train/Test Split
- StandardScaler
- OneHotEncoder
- ColumnTransformer
- Pipeline

---

## 06 — Baseline Machine Learning Models

Compared multiple classification algorithms:

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1 Score

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

# Key Skills Demonstrated

✔ Data Cleaning

✔ Missing Value Handling

✔ Data Type Conversion

✔ Exploratory Data Analysis

✔ Feature Engineering

✔ Machine Learning Preprocessing

✔ One-Hot Encoding

✔ Feature Scaling

✔ Pipeline Construction

✔ Baseline Model Evaluation

---

# Results

The project successfully transformed raw customer data into a machine-learning-ready dataset and compared multiple baseline classification models.

Among the evaluated models, **Logistic Regression** achieved the strongest overall baseline performance on this dataset.

---

# Learning Outcome

This project strengthened my understanding of the complete data preparation workflow used in real-world Machine Learning projects.

Rather than focusing solely on model accuracy, the project emphasizes the importance of high-quality data preprocessing, feature engineering, and reproducible machine learning pipelines.

---

## Author

**Hasnain Ali**

AI / ML Engineer Learning Journey