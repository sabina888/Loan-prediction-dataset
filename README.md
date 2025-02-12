Loan Prediction using Ensemble Learning

Overview

Dream Housing Finance Company aims to automate the loan eligibility process based on customer details provided in an online application form. This project utilizes machine learning, specifically ensemble learning techniques, to predict loan eligibility based on various features such as income, credit history, and employment status.

Dataset

The dataset includes the following features:

Loan_ID: Unique Loan ID

Gender: Male/Female

Married: Applicant married (Y/N)

Dependents: Number of dependents

Education: Applicant Education (Graduate/Undergraduate)

Self_Employed: Self-employed (Y/N)

ApplicantIncome: Applicant's income

CoapplicantIncome: Co-applicant's income

LoanAmount: Loan amount in thousands

Loan_Amount_Term: Term of loan in months

Credit_History: Credit history meets guidelines (1: Yes, 0: No)

Property_Area: Urban/Semi-Urban/Rural

Loan_Status: Target variable (Y: Approved, N: Not Approved)

Objective

The goal of this project is to build a robust machine learning model using ensemble learning techniques to predict whether a loan will be approved or not.

Methodology

Data Preprocessing:

Handle missing values

Encode categorical variables

Normalize numerical features

Model Selection:

Random Forest Classifier

Gradient Boosting Classifier

XGBoost Classifier

Stacking Ensemble Model

Evaluation Metrics:

Accuracy

Precision, Recall, F1-score
