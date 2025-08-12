# Datascience-internship-tasks
This repository contains my completed tasks for the Data Science internship.
Each task includes a Jupyter Notebook (.ipynb) with code, explanations, and results, along with the datasets required for execution.
Respiratory Structure:
Data-Science-Internship-Tasks/
│
├── Task1_Credit_Risk_Prediction.ipynb
├── loan_dataset.csv
├── Task2_Customer_Churn_Prediction.ipynb
├── churn_dataset.csv
├── Task3_Insurance_Charges_Prediction.ipynb
├── insurance_dataset.csv
└── README.md

Task 1 – Credit Risk Prediction:
Objective: Predict whether a loan applicant is likely to default on a loan.
Approach:
Cleaned and preprocessed data
Encoded categorical variables
Trained Logistic Regression & Decision Tree models
Evaluated using Accuracy & Confusion Matrix
Dataset: loan_dataset.csv
Result: Achieved high accuracy with Decision Tree model.

Task 2 – Customer Churn Prediction:
Objective: Identify customers who are likely to leave the bank.
Approach:
Cleaned dataset and handled categorical encoding
Trained classification models
Analyzed feature importance to identify churn factors
Dataset: churn_dataset.csv
Result: Model identified key churn indicators such as tenure, balance, and credit score.

Task 3 – Predicting Insurance Claim Amounts:
Objective: Estimate the medical insurance claim amount based on personal data.
Approach:
Applied Linear Regression model
Visualized the impact of BMI, age, and smoking status
Evaluated with MAE and RMSE
Dataset: insurance_dataset.csv
Result: Smoking status and BMI had the highest impact on charges

How to Run:
1) Clone this repository
   https://github.com/aash01k/Datascience-internship-tasks/new/main

2) Install dependencies
   pip install pandas numpy matplotlib seaborn scikit-learn

3) Open any task in Visual Studio or Jupyter Notebook
