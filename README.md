# 📊 Telco Customer Churn Prediction | End-to-End Machine Learning Project

An end-to-end Machine Learning project built using the **IBM Telco Customer Churn Dataset**. This project demonstrates the complete machine learning workflow followed by AI/ML Engineers, from understanding raw data to building production-ready preprocessing pipelines and predictive models.

The primary objective is to predict whether a customer is likely to churn while following industry-standard practices for data cleaning, feature engineering, preprocessing, model development, and evaluation.

---

# 🎯 Project Objectives

- Perform professional data understanding and exploration
- Clean and preprocess raw business data
- Conduct Exploratory Data Analysis (EDA)
- Engineer meaningful features from domain knowledge
- Build reusable preprocessing pipelines using Scikit-learn
- Train and compare multiple Machine Learning models
- Evaluate models using appropriate performance metrics
- Optimize the final model through hyperparameter tuning

---

# 📁 Dataset Information

**Dataset:** IBM Telco Customer Churn Dataset

**Source:** Kaggle / IBM Sample Dataset

### Target Variable

- **Churn**
  - Yes → Customer left the company
  - No → Customer stayed

### Dataset Summary

| Property | Value |
|----------|------:|
| Total Customers | 7,043 |
| Original Features | 21 |
| Target Variable | Churn |

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- Jupyter Notebook

---

# 📂 Project Structure

```
Customer-Churn-Prediction/
│
├── data/
│   ├── raw/
│   │   └── telco_customer_churn.csv
│   │
│   ├── cleaned/
│   │   └── telco_cleaned.csv
│   │
│   └── featured/
│       └── telco_feature_engineered.csv
│
├── notebooks/
│   ├── 01_Data_Understanding.ipynb
│   ├── 02_Data_Cleaning.ipynb
│   ├── 03_Exploratory_Data_Analysis.ipynb
│   ├── 04_Feature_Engineering.ipynb
│   ├── 05_Preprocessing.ipynb
│   ├── 06_Model_Training.ipynb
│   ├── 07_Model_Evaluation.ipynb
│   └── 08_Model_Optimization.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

# 🚀 Project Workflow

## ✅ 1. Data Understanding

- Dataset overview
- Data types inspection
- Feature categorization
- Target variable identification
- Missing value inspection
- Business understanding

---

## ✅ 2. Data Cleaning

- Removed invalid records
- Corrected data types
- Converted `TotalCharges` to numeric
- Handled missing values
- Created Data Quality Summary

---

## ✅ 3. Exploratory Data Analysis (EDA)

### Univariate Analysis

- Target distribution
- Numerical distributions
- Categorical distributions

### Bivariate Analysis

- Tenure vs Churn
- Contract Type vs Churn
- Payment Method vs Churn
- Internet Service vs Churn
- Monthly Charges vs Churn
- Total Charges vs Churn

### Business Insights

- Identified high-risk customer groups
- Observed churn behavior across service categories
- Analyzed customer retention patterns

---

## ✅ 4. Feature Engineering

The following features were engineered to improve predictive performance:

| Feature | Description |
|----------|-------------|
| TenureGroup | Groups customers based on subscription duration |
| TotalServices | Total number of subscribed services |
| HasSecurityBundle | Number of security-related services |
| AverageMonthlySpend | TotalCharges divided by tenure |
| IsFamilyCustomer | Indicates whether customer has partner or dependents |

---

## ⏳ 5. Data Preprocessing *(In Progress)*

Planned topics:

- Train-Test Split
- One-Hot Encoding
- Feature Scaling
- ColumnTransformer
- Scikit-Learn Pipelines
- Data Leakage Prevention

---

## ⏳ 6. Model Training

Models to be implemented:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine
- K-Nearest Neighbors
- XGBoost

---

## ⏳ 7. Model Evaluation

Evaluation metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix
- Classification Report

---

## ⏳ 8. Model Optimization

- Hyperparameter Tuning
- Cross Validation
- Feature Importance Analysis
- Model Comparison

---

# 📈 Current Progress

| Stage | Status |
|--------|--------|
| Data Understanding | ✅ Completed |
| Data Cleaning | ✅ Completed |
| Exploratory Data Analysis | ✅ Completed |
| Feature Engineering | ✅ Completed |
| Data Preprocessing | ⏳ In Progress |
| Model Training | ⏳ Pending |
| Model Evaluation | ⏳ Pending |
| Model Optimization | ⏳ Pending |

---

# 🎯 Learning Outcomes

This project demonstrates practical skills in:

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Feature Transformation
- Machine Learning Preprocessing
- Scikit-Learn Pipelines
- Model Development
- Model Evaluation
- End-to-End ML Workflow

---

# 📌 Future Improvements

- Deploy model using Flask/FastAPI
- Create an interactive Streamlit dashboard
- Build a REST API for predictions
- Containerize application using Docker
- Deploy to Render or Azure

---

# 🤝 Connect With Me

**Hasnain Ali**

Aspiring AI/ML Engineer passionate about building real-world Machine Learning solutions and continuously improving through hands-on projects.

If you found this project useful, feel free to ⭐ the repository and connect with me on LinkedIn.