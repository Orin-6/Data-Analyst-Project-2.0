# 📊 Telecom Customer Churn, Retention & Revenue Risk Analytics

## 📌 Project Overview

This project focuses on analyzing telecom customer churn, retention patterns, and revenue risks using Python and Power BI.

The goal is to identify why customers leave, understand customer retention behavior, detect high-value churned customers, and uncover business insights that can help improve customer retention and reduce revenue loss.

The project follows an end-to-end data analytics workflow, starting with data exploration and cleaning in Python and ending with interactive dashboards in Power BI.

## 🎯 Project Objectives

- Analyze overall customer churn and retention rates.
- Identify key factors influencing customer churn.
- Understand customer behavior based on tenure and contract type.
- Identify high-value customers who have churned.
- Analyze revenue risks associated with customer churn.
- Generate actionable business insights to support retention strategies.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and preprocessing |
| Pandas | Data cleaning and manipulation |
| NumPy | Numerical operations and feature engineering |
| Power BI | Interactive dashboard development |
| DAX | Measures and KPI calculations |
| Jupyter Notebook | Data exploration and analysis |

## 📂 Dataset

**Dataset:** Telco Customer Churn

**Source:** IBM Sample Data / Kaggle

The dataset contains customer information, including:

- Customer demographics
- Account information
- Services subscribed
- Contract details
- Monthly and total charges
- Customer tenure
- Churn status

## 🔄 Project Workflow

### 1. Data Loading & Exploration (Python)

- Imported the dataset using Pandas.
- Examined dataset dimensions and structure.
- Reviewed data types and statistical summaries.
- Identified missing values and duplicate records.
- Explored unique values across columns.

### 2. Data Cleaning & Feature Engineering

- Converted `TotalCharges` into numeric format.
- Handled missing and inconsistent values.
- Removed duplicate records.
- Created tenure groups.
- Categorized customers based on monthly charges.
- Converted churn status into a numerical flag.

### 3. Power BI Dashboard Development

Developed three interactive dashboard pages:

**Dashboard 1: Customer Churn Analysis**
- Total Customers
- Churned Customers
- Churn Rate
- Overall churn patterns
- Customer churn by different categories

**Dashboard 2: Customer Retention Analysis**
- Retained Customers
- Retention Rate
- Customer retention patterns
- Tenure-based retention analysis
- Key retention insights

**Dashboard 3: Revenue Risk Analysis**
- Revenue-related KPIs
- High-value churned customers
- Revenue risk patterns
- Customer segments contributing to revenue loss

## 📈 Key Business Insights

The analysis focuses on identifying:

- Customer segments with higher churn rates.
- Retention differences across contract types.
- The relationship between customer tenure and churn.
- High-value customers who have discontinued services.
- Potential revenue risks associated with customer churn.

## 📊 Dashboard Preview

### Dashboard 1 – Customer Churn Analysis
![Screenshot 1](Screenshot%202026-11-15%20011038.png)

### Dashboard 2 – Customer Retention Analysis
![Screenshot 2](Screenshot%202026-11-15%20011056.png)


### Dashboard 3 – Revenue Risk Analysis
![Screenshot 3](Screenshot%202026-11-15%20011038.png)


## 📁 Project Structure

```text
Telco-Customer-Churn/
│
├── Dataset/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
├── Notebook/
│   └── Telco_Customer_Churn_Analysis.ipynb
│
├── Dashboard/
│   ├── Customer_Churn_Analysis.png
│   ├── Customer_Retention_Analysis.png
│   ├── Revenue_Risk_Analysis.png
│   └── Telecom_Customer_Churn.pbix
│
└── README.md
```

## 💡 Business Recommendations

- Focus on customers with higher churn probabilities.
- Develop targeted retention campaigns for month-to-month customers.
- Improve customer engagement during the early stages of their subscriptions.
- Offer personalized incentives to retain high-value customers.
- Monitor revenue risks associated with customer cancellations.

## 🚀 Project Outcome

This project demonstrates an end-to-end data analytics workflow using Python and Power BI. It transforms raw telecom customer data into meaningful business insights through data cleaning, feature engineering, KPI development, and interactive visualization.

## 👩‍💻 Author

**Orin**

GitHub: [Orin-6](https://github.com/Orin-6)

Portfolio: [Data Science & Machine Learning Portfolio](https://orin-6.github.io/PORTFOLIO/)

---

