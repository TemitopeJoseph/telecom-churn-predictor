# telecom-churn-predictor
# 📊 Telecom Customer Churn Prediction & Retention System

An end-to-end machine learning solution that predicts customer churn risk and translates probability scores into actionable retention strategies for telecom businesses.

![Python](https://img.shields.io/badge/Python-3.11-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.3%2B-orange.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red.svg)
![Deployment](https://img.shields.io/badge/Deployed-Streamlit%20Cloud-brightgreen.svg)

---

## 📌 Project Overview

Customer churn occurs when a customer cancels their subscription or service. In the telecom industry, acquiring a new customer costs 5 to 25 times more than retaining an existing one.

This project goes beyond raw accuracy to solve a **business-first objective**: identifying at-risk customers early enough to intervene while minimizing unnecessary promotional spending.

### 🔗 [Click Here to Access the Live Web Application](https://your-streamlit-app-link.streamlit.app) *(Replace with your live link)*

---

## 🎯 Key Business Objective & Strategy

Standard accuracy can be misleading in churn prediction because non-churners far outnumber churners. 

* **The Problem with Raw Accuracy:** A model that simply predicts "No Churn" for every customer can achieve ~73% accuracy while missing **100% of churners**.
* **The Solution (Recall Optimization):** We prioritized **Recall** (catching the maximum number of true churners) and **ROC-AUC** (overall risk-ranking capacity).
* **Retention Strategy Threshold:** Instead of the standard $0.50$ decision cutoff, we calibrated our decision threshold to **$0.35$**. This allows the customer success team to flag and save ~80% of churn-prone accounts.

---

## 🛠️ Tech Stack & Tools

* **Language:** Python 3.11
* **Data Manipulation & Viz:** Pandas, NumPy, Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (`LogisticRegression`, `ColumnTransformer`, `Pipeline`, `GridSearchCV`)
* **Model Export:** Joblib
* **Web App & Deployment:** Streamlit Community Cloud, GitHub

---

## 🔬 Machine Learning Pipeline & Workflow
