# Loan Approval Intelligence and Risk Assessment System

## 1. Project Overview

The **Loan Approval Intelligence and Risk Assessment System** is an AIML Semester 3 Skill Lab project.

The project focuses on analyzing historical loan application data to understand the factors associated with loan approval outcomes and preparing the dataset for future predictive machine learning models.

## 2. Problem Statement

Loan approval decisions involve analyzing several applicant attributes, including income, employment, credit history, loan amount and property area.

This project aims to explore these attributes, identify patterns in historical loan application data, and develop a structured data preprocessing workflow that can support future machine learning-based loan approval prediction.

## 3. Project Objectives

- Understand the loan application dataset and its features.
- Identify and handle missing values and duplicate records.
- Perform data cleaning and feature engineering.
- Analyze outliers in numerical attributes.
- Perform Exploratory Data Analysis (EDA).
- Conduct statistical analysis and hypothesis testing.
- Prepare numerical and categorical features for machine learning.
- Create a reproducible preprocessing pipeline.

## 4. Dataset Information

- Original dataset size: 614 rows.
- Number of columns: 13.
- Target variable: `Loan_Status`.
- Identifier column: `Loan_ID`.

The dataset contains applicant-related information such as income, loan amount, credit history, education, employment status and property area.

**Note:** Dataset source and license details should be added after verification.

## 5. Technologies and Libraries Used

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- Joblib

## 6. Project Workflow

The project follows these stages:

1. Environment Setup and Library Import
2. Dataset Loading
3. Dataset Understanding
4. Data Quality Analysis
5. Data Cleaning
6. Feature Engineering
7. Outlier Analysis
8. Exploratory Data Analysis (EDA)
9. Statistical Analysis and Hypothesis Testing
10. Data Preprocessing

## 7. Data Preprocessing

The preprocessing pipeline uses Scikit-learn's `ColumnTransformer` and `Pipeline`.

The following operations are performed:

- Missing numerical values are handled using median imputation.
- Missing categorical values are handled using most-frequent imputation.
- Numerical features are scaled using StandardScaler.
- Categorical features are encoded using OneHotEncoder.
- The dataset is divided into training and testing sets using an 80:20 split.
- The preprocessing transformer is fitted using training data and then applied to testing data.

Identifier and target columns are excluded from the input feature set to avoid data leakage.

## 8. Statistical Analysis

Two statistical tests are included:

- **Welch's Independent t-test:** Examines whether mean applicant income differs between loan outcome groups.
- **Chi-square Test of Independence:** Examines the association between credit history and loan approval outcomes.

## 9. Current Project Progress

### Completed Work

- Dataset loading and understanding.
- Missing-value and duplicate analysis.
- Data cleaning.
- Feature engineering.
- Outlier analysis.
- Exploratory Data Analysis.
- Statistical hypothesis testing.
- Training and testing data preparation.
- Numerical and categorical preprocessing pipeline.

### Current Stage

**Level 1 – Data Understanding and Preprocessing**

The dataset has been prepared for the next phase of machine learning development.

**Important:** A machine learning prediction model has not yet been trained. Model training and evaluation will be taken up in a future project stage.

## 10. Repository Structure

```text
loan-approval-intelligence-and-risk-assessment/
│
├── data/
│   └── README.md
│
├── models/
│   └── README.md
│
├── notebooks/
│   └── README.md
│
├── reports/
│   └── README.md
│
├── LoanApproval(3).ipynb
│
└── README.md
```

## 11. Future Scope

- Develop machine learning classification models.
- Evaluate model performance using suitable classification metrics.
- Compare different algorithms.
- Analyze important features influencing loan approval.
- Develop an interface for loan approval risk assessment.

## 12. Academic Project

Developed as part of the **Artificial Intelligence and Machine Learning – Semester 3 Skill Lab**.

**Project Title:** Loan Approval Intelligence and Risk Assessment System
