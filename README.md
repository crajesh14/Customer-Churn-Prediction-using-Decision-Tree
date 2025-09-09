# Customer Churn Prediction using Decision Tree

## 📌 Problem Statement
Customer churn is one of the biggest challenges in the telecom industry. This project aims to predict whether a customer will churn (leave the company) using a Decision Tree model.

## 📊 Dataset
- Source: [Telco Customer Churn - Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn)
- Target: `Churn` (Yes/No)

## 🔎 Steps
1. Data Cleaning & Preprocessing
   - Removed customerID
   - Handled missing values in `TotalCharges`
   - Converted categorical variables using One-Hot Encoding
2. Exploratory Data Analysis
   - Distribution of churned vs non-churned customers
   - Correlation heatmap
3. Model Training
   - Used Decision Tree Classifier (`max_depth=5`)
   - Train-test split (80-20)
4. Model Evaluation
   - Accuracy, Precision, Recall, F1-score
   - Confusion Matrix
5. Visualization
   - Full Decision Tree
   - Feature Importances (top 10 features)

## 📈 Results
- Accuracy: ~80%
- Most important features: Contract type, tenure, MonthlyCharges


---
👨‍💻 **Author**: Chakali Rajesh
