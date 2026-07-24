# Business-Data-Analysis-Assignment-using-Python-Pandas-Matplotlib-Seaborn-
# 📊 Telecom Customer Churn Data Analysis

An end-to-end data exploration and customer churn analysis project on a telecom subscription dataset (`exported_churn_data.csv`), written in Python.

---

## 📌 Project Overview

This project provides an in-depth exploratory data analysis (EDA) focused on customer retention, demographic distributions, and churn behavior. 

> **Note on Dataset Mapping**: The core analysis maps telecom subscription fields to equivalent customer lifecycle metrics:
> - **Product**: Mapped to `plan_type` (Basic, Standard, Premium)
> - **Rating**: Mapped to `csat_score` (Customer Satisfaction Score)
> - **Purchase Value**: Mapped to `monthly_charges`
> - **Engagement Score**: Mapped to derived inverse churn risk (`100 - churn_score`)
> - **Duration**: Calculated subscription tenure in days

---

## 💡 Key Business Insights

1. **Demographic Breakdown**: The customer base is heavily skewed towards the **Adult** age bracket, representing the primary target group for retention strategies.
2. **Gender Distribution**: Balanced distribution across male and female subscribers (`12 Female`, `9 Male`), showing consistent retention trends across genders.
3. **Churn Drivers**: Customers with escalations and low CSAT scores exhibit significantly higher churn rates.

---

## 🛠️ Tech Stack & Libraries

- **Language**: Python 3.10+
- **Data Manipulation**: `pandas`, `numpy`
- **Data Visualization**: `matplotlib`, `seaborn`
- **Environment**: Jupyter Notebook

---
