# Customer-Churn-Prediction-and-Risk-Analysis-Engine

# 📊 Customer Churn Prediction & Risk Analysis Engine

An interpretable machine learning project designed to predict telecom customer churn and generate business-friendly risk scores for proactive retention strategies.

## 📌 Project Overview

Customer churn is a major revenue challenge in the telecom industry. This project builds a predictive analytics system using statistical analysis and Logistic Regression to identify key churn drivers, predict customer churn probability, generate a 0–100 risk score, and provide interpretable insights for business stakeholders.

## 🎯 Objectives

- Perform data cleaning and preprocessing  
- Handle class imbalance  
- Encode categorical variables  
- Apply feature scaling  
- Train a Logistic Regression model  
- Evaluate using ROC-AUC, Precision, Recall, and F1-score  
- Develop a customer risk scoring system  

## 🗂 Dataset

Dataset used: Telco Customer Churn (IBM Sample Dataset) from Kaggle.
Kaggle Link: https://www.kaggle.com/datasets/blastchar/telco-customer-churn

The dataset contains:
- Demographics (Gender, Senior Citizen, Partner, Dependents)  
- Account Information (Tenure, Contract Type, Payment Method)  
- Service Details (Internet Service, Phone Service)  
- Monthly and Total Charges  
- Target Variable: `Churn`  

## 🛠 Technologies Used

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  

## ⚙️ Machine Learning Approach

The workflow includes:
1. Data Cleaning  
2. One-Hot Encoding of Categorical Variables  
3. Train-Test Split  
4. Feature Scaling using StandardScaler  
5. Logistic Regression with Class Weighting  
6. Model Evaluation  
7. Risk Score Generation  

## 📈 Model Evaluation Metrics

The model is evaluated using:

- Confusion Matrix  
- Precision  
- Recall  
- F1-Score  
- ROC-AUC Score  

ROC-AUC is used as the primary metric to measure classification performance and discrimination ability.

## 🔥 Risk Scoring System

The predicted churn probability is converted into a business-friendly risk score:

- **Low Risk:** < 40%  
- **Medium Risk:** 40% – 60%  
- **High Risk:** > 60%  

This enables business teams to prioritize customer retention strategies effectively.

## 🚀 How to Run

1. Clone the repository  
2. Install dependencies:
3. Open the Jupyter Notebook  
4. Run the cells sequentially  

## 📌 Key Learnings

This project demonstrates:
- The importance of handling class imbalance  
- Statistical interpretation of churn drivers  
- Building interpretable machine learning models  
- Converting predictive probabilities into actionable business insights  

## 📜 Conclusion

This churn prediction and risk analysis engine shows how machine learning can solve real-world telecom business problems while maintaining transparency, interpretability, and strong evaluation practices.
