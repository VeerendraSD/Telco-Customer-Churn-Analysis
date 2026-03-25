# Telco-Customer-Churn-Analysis
End-to-end customer churn analysis and prediction using machine learning with actionable business insights.


# Customer Churn Analysis and Prediction
## Overview
The project is about customer churn analysis and prediction using a telecom dataset. The project aims at understanding the major determinants of customer churn and developing a machine learning model for proactive customer churn prediction. 

---

## Objectives
- Understand the major determinants of customer churn  
- Conduct exploratory data analysis (EDA)  
- Develop a model for customer churn prediction  
- Extract business insights for customer retention  

---

## Exploratory Data Analysis
Some of the major insights from exploratory data analysis are as follows:

- Low-tenure customers are more likely to churn  
- The highest customer churn is observed for month-to-month contracts  
- High monthly charges increase customer churn  
- High monthly charges and lack of long-term contract increase customer churn  

---

## Feature Engineering
- Categorical variables are converted into numerical variables  
- Missing value handling for variable "TotalCharges"  
- Feature engineering for customer churn prediction model  

---

## Model Building 
- Used **Logistic Regression** as the baseline model
- Implemented **class balancing** to handle class imbalance
- Data splitting: **80% training set** and **20% test set**

## Model Performance 
- Accuracy: ~72%
- - Precision: ~48%
- Recall: ~79%
- F1 Score: ~0.60
- The model focuses on high recall to ensure that a majority of churn-prone customers are captured.

## Key Findings
- **Contract type** is the key factor that influences churn
- Customers with **long-term contracts** are more stable
- Offering services such as **TechSupport and OnlineSecurity** reduces customer churn
- High-risk customers: - Low tenure - High monthly charges - Month-to-month contracts

## Business Recommendations 
- Better onboarding for new customers
- Long-term contracts with incentives
- Better support services to retain customers
- Target high-risk customers with special offers

## 🛠️ Tech Stack - Python - Pandas, NumPy - Matplotlib, Seaborn - Scikit-learn

## 🚀 Conclusion This project highlights the importance of using data insights and machine learning to understand customer behavior and reduce churn for a business.
