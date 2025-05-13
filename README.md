# Loan-Prediction-Model

# 🏦 Loan Approval Prediction using Logistic Regression

This project builds a machine learning model to predict whether a loan application will be approved or not based on applicant information such as income, employment status, marital status, credit history, and education. The model is trained using logistic regression — a widely used algorithm for binary classification problems.



# 📂 Table of Contents

- [Dataset](#dataset)
- [Installation](#installation)
- [Methodology](#methodology)
- [Results](#results)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

# 📈 Project Overview

Loan approval prediction is a common task in financial analytics. By using applicant details such as income, employment status, credit history, and loan amount, we aim to build a logistic regression model that predicts loan approval (Approved or Not Approved).

This can help financial institutions streamline their decision-making process and assess loan risk more efficiently.

---

# 📊 Dataset

- **Source**: [Loan Prediction Dataset - Kaggle]-- Original version(https://www.kaggle.com/datasets/ninzaami/loan-predication)
- **Size**: 548 training entries with 13 features each
- **Target Variable**: `Loan_Status` (Y = Approved, N = Not Approved)

## Features used:
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Gender
- Married
- Education
- Self_Employed
- Property_Area


---

# 💻 Installation

To set up the project locally, follow these steps:

"""
### 1. Clone the repository


### 2. (Optional) Create a virtual environment


### 3. Install dependencies
pip install -r requirements.txt eg. pandas, numpy, scikit-learn, matplotlib, seaborn etc"""

####

# 🧠 Methodology
### Data Cleaning 
- Handle missing values
- Remove outliers
- Delete duplicates and errors


### Exploratory Data Analysis (EDA)
- Distribution plots
- Class imbalance checks

### Data preprocessing and modeling
- Logistic Regression with scikit-learn
- Feature selection

# Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score

# Results
Logistic Regression achieved:
- Accuracy: 83%
- F1 Score: 0.81
- Precision: 0.85
- Recall: 0.83
