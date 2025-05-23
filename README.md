# Improving Loan Risk Assessment and Approval Process Using Big Data Analytics

This repository presents a comprehensive pipeline to modernize and enhance the loan approval process using Big Data, Machine Learning, and MLOps practices. It was developed as part of the **MGMT 59000 - Big Data and MLOps** course at Purdue University.

## 📌 Project Summary

Traditional loan underwriting models often lack the nuance required to differentiate between good and bad borrowers, leading to either lost opportunities or increased default rates. This project integrates data-driven modeling and MLOps pipelines to:

- Predict the likelihood of loan default.
- Estimate monthly repayment ability.
- Segment borrowers based on financial behavior.
- Identify early repayers for loyalty strategies.

## 👥 Team Members

- **Tushar Malankar** – tmalanka@purdue.edu  
- **Saquib Hussain** – hussai71@purdue.edu  

---

## 📁 Dataset

- **Source**: [Kaggle - Loan Default Prediction Challenge](https://www.kaggle.com/datasets/nikhil1e9/loan-default)
- **Records**: 255,347
- **Features**:
  - Demographics: Age, income, employment status
  - Loan specifics: Loan amount, term, purpose, rate
  - Financial health: Credit score, DTI, open credit lines
  - Target: Defaulted loan (1) or not (0)

---

## 🧠 ML Models & Goals

| Model | Objective | Type | Metric |
|-------|-----------|------|--------|
| **Logistic Regression** | Predict loan default | Classification | AUC: 0.747 |
| **Linear Regression** | Predict monthly payment | Regression | R²: 0.78 |
| **K-Means Clustering** | Segment borrower risk profiles | Unsupervised | Silhouette Score |
| **Gradient Boosted Trees** | Predict early repayment | Regression | MAE, RMSE |

---

## ⚙️ Pipeline & MLOps Stack

- **Framework**: Apache Spark (Databricks)
- **Preprocessing**: Spark ML Pipelines
- **Tracking**: MLflow for hyperparameter tuning, metrics, and artifact logging
- **Data Storage**: Delta Lake format
- **Deployment**: Model registry and version control via MLflow

---

## 🔍 Key Insights

- Borrowers earning less than $30K had a 21.9% default rate vs. 9.1% for $100K+.
- Unemployed applicants showed the highest risk.
- High DTI and low credit scores are strong predictors of default.
- Majority of early repayers had lower interest rates and smaller loan terms.

---

## 💼 Business Value

- Improve approval accuracy with granular risk segmentation.
- Tailor loan offers based on payment behavior and predicted capacity.
- Reduce defaults through better credit profiling.
- Launch proactive loyalty incentives for low-risk, early-paying borrowers.

---

## 📊 Visual Reports

Reports available in `/reports/`:
- 📄 Final_Project_Report.pdf
- 🎞️ Final_Presentation.pdf

---

## 🔧 Project Structure

