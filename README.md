## Customer Churn Prediction
## 📋 Project Overview
**Goal:** Predict customer churn (binary classification: churn / no churn) using tabular data.
Customer churn occurs when customers stop using a company's products or services. Predicting churn is critical for businesses to retain customers, optimize marketing strategies, and reduce revenue loss.
## 🔍 Problem Understanding
**Customer Churn Prediction is a binary classification problem:**
Class 0: Customers who stay (no churn).
Class 1: Customers who leave (churn).
**By analyzing patterns in customer data, we can build a predictive model to:**
Identify customers likely to churn.
Take proactive measures to retain them (e.g., discounts, personalized services).
## 🗂 Dataset Overview
**The dataset contains tabular data with customer-related features, including:**
Demographic Information (e.g., age, gender).
Customer Usage Patterns (e.g., product usage, purchase history).
Subscription Details (e.g., tenure, contract type).
Service Metrics (e.g., support calls, charges).
## 🔑 Features and Labels
Input Features:
Age
Tenure
MonthlyCharges
TotalCharges
Number of Support Calls
Contract Type (e.g., monthly, yearly)
Payment Method
Target Variable:
Churn (1 = churn, 0 = no churn)
## 🛠 Steps in the Project

**Data Exploration & Cleaning**

Handle missing values, outliers, and data inconsistencies.
Visualize key features to understand trends.

**Feature Engineering**
Convert categorical variables into numerical 
Scale numerical features for better model performance.

**Train-Test Split**
Split the dataset into training (80%) and testing (20%) subsets.

**Model Building**
Build and compare multiple machine learning models:
Logistic Regression
Random Forest
Gradient Boosting
Support Vector Machines (SVM)
SMOTE technique for imbalance data

**Model Evaluation**
Evaluate models using the following metrics:
Accuracy
Recall (Sensitivity)
Precision
F1-Score

**Hyperparameter Tuning**
Fine-tune the best-performing model to optimize its performance.

## 📊 Key Tools & Libraries
Programming Language: Python
Libraries:
Data Handling: pandas, numpy
Visualization: matplotlib, seaborn
Model Building: scikit-learn
Hyperparameter Tuning: GridSearchCV, RandomizedSearchCV
Model Evaluation: classification_report, confusion_matrix
## 🔎 Model Comparison
 ![modell](https://github.com/user-attachments/assets/9bc46e78-cd16-4123-9614-4f9fb047aa34)

## 📂 Project Files
churn_data.csv: Dataset used for the project.
churn_prediction.ipynb: Notebook containing the code, visualizations, and results.
README.md: Project documentation.
