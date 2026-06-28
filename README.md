# 📊 Telco Customer Churn Prediction — End-to-End Machine Learning Pipeline

## Project Overview

This project demonstrates an end-to-end Machine Learning workflow using the IBM Telco Customer Churn dataset. The primary objective is to build a production-style preprocessing pipeline and prepare high-quality data for customer churn prediction.

Rather than focusing only on model accuracy, this project emphasizes professional data preprocessing, feature engineering, and reproducible machine learning workflows commonly used by AI/ML Engineers.

---

## Project Goals

* Perform professional data understanding
* Clean and validate raw business data
* Conduct exploratory data analysis (EDA)
* Engineer meaningful business features
* Build reusable preprocessing pipelines
* Prevent data leakage
* Compare multiple machine learning models
* Evaluate model performance using industry-standard metrics

---

## Project Structure

```
Telco-Customer-Churn/

│
├── data/
│   ├── raw/
│   │   └── Telco-Customer-Churn.csv
│   │
│   └── processed/
│       └── feature_engineered_telco.csv
│
├── notebooks/
│   ├── 01_Data_Loading.ipynb
│   ├── 02_Data_Cleaning.ipynb
│   ├── 03_Exploratory_Data_Analysis.ipynb
│   ├── 04_Feature_Engineering.ipynb
│   ├── 05_Preprocessing_Pipeline.ipynb
│   ├── 06_Model_Training.ipynb
│   ├── 07_Model_Evaluation.ipynb
│   └── 08_Final_Model.ipynb
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

# Dataset

IBM Telco Customer Churn Dataset

Target Variable:

* Churn

Business Objective:

Predict whether a customer is likely to leave the telecom company based on demographic information, subscription details, and service usage.

---

# Completed Work

## Notebook 01 — Data Loading

* Imported dataset
* Explored dataset structure
* Verified data types
* Identified target variable

---

## Notebook 02 — Data Cleaning

* Checked missing values
* Detected blank values
* Fixed `TotalCharges`
* Converted incorrect datatypes
* Removed data inconsistencies
* Generated professional Data Quality Summary

---

## Notebook 03 — Exploratory Data Analysis

Performed visual and statistical analysis for:

* Customer demographics
* Contract types
* Internet services
* Payment methods
* Monthly charges
* Tenure
* Churn distribution
* Correlation with churn

Generated business insights after every visualization.

---

## Notebook 04 — Feature Engineering

Created meaningful business-driven features including:

* TenureGroup
* TotalServices
* HasSecurityBundle
* AverageMonthlySpend
* IsFamilyCustomer

Saved the engineered dataset for downstream preprocessing.

---

## Notebook 05 — Machine Learning Preprocessing

Implemented an industry-standard preprocessing workflow using Scikit-Learn.

Completed:

* Train-Test Split
* Stratified Sampling
* Numerical & Categorical Feature Separation
* StandardScaler
* OneHotEncoder
* ColumnTransformer
* Scikit-Learn Pipeline
* Baseline Logistic Regression Model

Baseline Accuracy:

**79.77%**

---

# Skills Demonstrated

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Data Cleaning
* Exploratory Data Analysis
* Feature Engineering
* Feature Scaling
* One-Hot Encoding
* ColumnTransformer
* Pipeline
* Machine Learning Workflow
* Data Leakage Prevention

---

# Technologies

* Python 3
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Jupyter Notebook

---

# Upcoming Work

* Logistic Regression Optimization
* Decision Tree
* Random Forest
* K-Nearest Neighbors
* Support Vector Machine
* Hyperparameter Tuning
* Cross Validation
* Model Comparison
* ROC Curve
* Precision-Recall Analysis
* Feature Importance
* Final Model Selection

---

## Author

**Hasnain Ali**

AI/ML Engineering Portfolio Project

Built as part of my journey to becoming an AI/ML Engineer through hands-on, production-style machine learning projects.
