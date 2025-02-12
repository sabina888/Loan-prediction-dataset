# 🏡 Loan Prediction using Ensemble Learning

## 📌 Overview

Dream Housing Finance Company aims to automate the loan eligibility process based on customer details provided in an online application form. This project utilizes **machine learning**, specifically **ensemble learning** techniques, to predict loan eligibility based on various features such as income, credit history, and employment status.

---

## 📊 Dataset

The dataset includes the following features:

| Feature                | Description                                     |   |
| ---------------------- | ----------------------------------------------- | - |
| **Loan\_ID**           | Unique Loan ID                                  |   |
| **Gender**             | Male/Female                                     |   |
| **Married**            | Applicant married (Y/N)                         |   |
| **Dependents**         | Number of dependents                            |   |
| **Education**          | Applicant Education (Graduate/Undergraduate)    |   |
| **Self\_Employed**     | Self-employed (Y/N)                             |   |
| **ApplicantIncome**    | Applicant's income                              |   |
| **CoapplicantIncome**  | Co-applicant's income                           |   |
| **LoanAmount**         | Loan amount in thousands                        |   |
| **Loan\_Amount\_Term** | Term of loan in months                          |   |
| **Credit\_History**    | Credit history meets guidelines (1: Yes, 0: No) |   |
| **Property\_Area**     | Urban/Semi-Urban/Rural                          |   |
| **Loan\_Status**       | Target variable (Y: Approved, N: Not Approved)  |   |

---

## 🎯 Objective

The goal of this project is to build a **robust machine learning model** using ensemble learning techniques to predict whether a loan will be approved or not.

---

## ⚙️ Methodology

1. **Data Preprocessing**:
   - Handle missing values
   - Encode categorical variables
   - Normalize numerical features
2. **Model Selection**:
   - ✅ Random Forest Classifier
   - ✅ Gradient Boosting Classifier
   - ✅ XGBoost Classifier
   - ✅ Stacking Ensemble Model
3. **Evaluation Metrics**:
   - 📈 Accuracy
   - 🎯 Precision, Recall, F1-score

---

## 🛠️ Installation

To run this project, install the required dependencies using:

```bash
pip install -r requirements.txt
```

---

## 🚀 Usage

Run the main script to train and evaluate the model:

```bash
python loan_prediction.py
```

---

## 📌 Results

The trained **ensemble model** will provide predictions on loan eligibility with **high accuracy** and **robustness** compared to individual models.

---

## 🤝 Contribution

Feel free to contribute by:

- 🔍 Improving feature engineering techniques
- 🏗️ Trying other ensemble learning approaches
- 📊 Enhancing model performance

