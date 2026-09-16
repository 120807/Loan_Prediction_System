# 🏦 Loan Approval Prediction System

A Machine Learning-based web application that predicts whether a loan application is likely to be **Approved** or **Rejected** based on applicant and financial information.

The application is built using **Python, Streamlit, Pandas, and Scikit-learn**, with a pre-trained machine learning model used to generate predictions.

---

## 📌 Project Overview

Loan approval depends on several factors such as the applicant's education, employment status, income, loan amount, credit score, and available assets.

This project provides a simple web interface where users can enter these details and get a machine-learning-based loan prediction instantly.

### 🎯 Objective

- Predict loan approval status using Machine Learning.
- Provide a simple and interactive user interface.
- Process applicant information automatically.
- Scale input features before prediction.
- Display the prediction as **Loan Approved** or **Loan Rejected**.

---

## ✨ Features

- 📊 Interactive web interface
- 👨‍👩‍👧 Number of dependents input
- 🎓 Education selection
- 💼 Self-employment selection
- 💰 Annual income input
- 🏦 Loan amount input
- 📅 Loan duration input
- 📈 Civil/Credit score input
- 💵 Assets input
- 🤖 Machine Learning prediction
- ⚡ Instant prediction using Streamlit

---

## 🛠️ Technologies Used

- **Python**
- **Streamlit**
- **Pandas**
- **Scikit-learn**
- **Pickle**
- **Jupyter Notebook**
- **Machine Learning**

---

## 📋 Input Features

The model uses the following features:

| Feature | Description |
|---|---|
| Number of Dependents | Number of people dependent on the applicant |
| Education | Graduate or Not Graduate |
| Self Employed | Whether the applicant is self-employed |
| Annual Income | Applicant's annual income |
| Loan Amount | Requested loan amount |
| Loan Duration | Duration of the loan |
| Civil/Credit Score | Applicant's credit score |
| Assets | Total assets owned by the applicant |

---

## 🔄 Working Process

```text
User Input
    ↓
Streamlit Web Interface
    ↓
Convert Categorical Values
    ↓
Create DataFrame
    ↓
Scale Input Features
    ↓
Load Pre-trained ML Model
    ↓
Generate Prediction
    ↓
Display Result
