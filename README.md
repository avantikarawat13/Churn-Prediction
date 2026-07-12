# 📊 Telecom Customer Churn Analysis & Prediction

An end-to-end **Data Analytics & Machine Learning** project that analyzes customer churn for a telecom company using **PostgreSQL, Power BI, Python, and Random Forest Classification**. The project covers the complete analytics pipeline—from ETL and data cleaning to dashboard creation and churn prediction.

---

## 📌 Project Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses. This project helps identify customers who are likely to leave the company by analyzing historical customer behavior and building a predictive machine learning model.

The project consists of:

* ETL pipeline using PostgreSQL
* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Power BI Dashboard
* Customer churn prediction using Random Forest
* Business insights and recommendations

---

## 🛠️ Tech Stack

| Category         | Tools                                            |
| ---------------- | ------------------------------------------------ |
| Database         | PostgreSQL                                       |
| Data Processing  | SQL                                              |
| Visualization    | Power BI                                         |
| Programming      | Python                                           |
| Libraries        | Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn |
| Machine Learning | Random Forest Classifier                         |

---

## 📂 Project Structure

```text
Telecom-Churn-Analysis/
│
├── Dataset/
│   └── telecom_churn.csv
│
├── SQL/
│   ├── create_database.sql
│   ├── staging_table.sql
│   ├── production_table.sql
│   ├── views.sql
│   └── data_cleaning.sql
│
├── PowerBI/
│   └── Telecom_Churn_Dashboard.pbix
│
├── Python/
│   ├── churn_prediction.ipynb
│   ├── model_training.py
│   └── Predictions.csv
│
├── Images/
│   ├── dashboard.png
│   ├── churn_prediction.png
│   └── architecture.png
│
└── README.md
```

---

## 🚀 Project Workflow

### 1. Data Loading

* Import telecom customer dataset into PostgreSQL
* Create staging table
* Validate data types
* Handle missing values

---

### 2. Data Cleaning

Performed data preprocessing by:

* Replacing NULL values
* Creating Production table
* Standardizing categorical values
* Creating SQL Views for reporting

---

### 3. Exploratory Data Analysis

Analyzed customer behavior across:

* Gender
* Age Group
* State
* Contract Type
* Internet Service
* Payment Method
* Monthly Charges
* Customer Status

---

### 4. Power BI Dashboard

Developed an interactive dashboard containing:

### Executive Summary

* Total Customers
* New Joiners
* Total Churn
* Churn Rate

### Customer Demographics

* Gender-wise Churn
* Age Group Analysis

### Geographic Analysis

* State-wise Churn Rate

### Account Information

* Contract Type
* Payment Method
* Tenure Analysis

### Service Analysis

* Internet Type
* Services Used
* Streaming Services

### Churn Analysis

* Churn Category
* Churn Reason
* Customer Distribution

---

## 🤖 Machine Learning

Built a **Random Forest Classifier** to predict customers who are likely to churn.

### Data Preprocessing

* Label Encoding
* Feature Selection
* Train-Test Split (80:20)

### Model Used

* Random Forest Classifier

### Model Evaluation

* Confusion Matrix
* Classification Report
* Feature Importance

---

## 📈 Prediction Pipeline

The trained model predicts churn probability for newly joined customers and exports the results as:

```text
Predictions.csv
```

This file can be connected back to Power BI for visualization.

---

## 📊 Key Business Insights

* Customers with month-to-month contracts have the highest churn.
* Fiber internet users show comparatively higher churn.
* Electronic check users churn more frequently than other payment methods.
* Short-tenure customers are more likely to leave.
* Customers without security or backup services have higher churn probability.
* High monthly charges contribute significantly to churn.


## 📌 Future Improvements

* Hyperparameter tuning
* XGBoost and LightGBM implementation
* SHAP Explainability
* Streamlit Web App
* Real-time prediction pipeline
* Docker deployment
* Cloud deployment using Azure or AWS

---

## 🎯 Skills Demonstrated

* SQL
* PostgreSQL
* Data Cleaning
* ETL Pipeline
* Power BI
* Data Visualization
* Data Modeling
* Feature Engineering
* Machine Learning
* Random Forest
* Customer Analytics
* Business Intelligence

---

## 📚 Learning Outcomes

Through this project, I gained hands-on experience in:

* Designing ETL workflows
* Database management
* Power BI dashboard development
* Data preprocessing
* Feature engineering
* Building predictive ML models
* Translating business problems into analytical solutions

---

## ⭐ If you found this project helpful

Please consider giving the repository a ⭐ to support my work.

---

## 👩‍💻 Author

**Avantika Rawat**

