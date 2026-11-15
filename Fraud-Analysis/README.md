# Data-Analyst-Project-2.0

A collection of data analysis projects showcasing practical skills in SQL, Python, Excel, Power BI, Tableau, and data visualization through real-world datasets and insightful analysis.

---

## Credit Card Fraud Analysis Dashboard

An end-to-end data analysis and visualization project that identifies credit card fraud patterns and presents the findings through an interactive dashboard, built with **MySQL** and **Tableau**.

### Dashboard Preview

![Credit Card Fraud Dashboard](Fraud-Analysis/Screenshot%202026-10-24%20000613.png)

### Project Overview

Credit card fraud is a major challenge in digital payment systems. This project explores transaction data to understand fraudulent activity, examine transaction patterns, and visualize fraud trends. SQL is used for data exploration, and Tableau is used to present the results in an interactive dashboard.

### Objectives

- Analyze overall transaction activity and fraudulent transactions.
- Calculate the fraud rate and fraud amount.
- Identify transaction categories associated with fraud.
- Examine monthly fraud trends.
- Compare fraudulent and non-fraudulent transactions.
- Build an interactive dashboard with filters.

### Tools & Technologies

- **MySQL**: data querying, aggregation, and exploratory analysis
- **Python (Jupyter Notebook)**: supporting analysis
- **Tableau**: interactive dashboard and visualization

### Dashboard Features

**Key Performance Indicators (KPIs)**
- Total Transactions
- Fraud Cases
- Fraud Rate
- Fraud Amount

**Visualizations**
- Fraud Cases by Category
- Fraud Amount by Category
- Monthly Distribution of Fraud Cases
- Monthly Fraud Amount Trend
- Fraud vs. Non-Fraud Distribution

**Interactive Filters**
- Transaction Date
- Transaction Category
- Fraud Status

### SQL Analysis

SQL queries are used to calculate key metrics, including:

- Total transaction count
- Total fraud cases
- Fraud rate
- Average and maximum transaction amounts
- Fraud amount by category
- Potential duplicate transactions
- Fraud patterns across transaction categories

### Dataset

The dataset contains credit card transaction details such as amount, category, timestamp, and a fraud indicator (`is_fraud`).

- `is_fraud = 1`: fraudulent transaction
- `is_fraud = 0`: non-fraudulent transaction

It includes approximately 140,182 transactions, of which 613 are fraudulent.

**Source:** (add dataset name and link here)

### Repository Structure

```text
Data-Analyst-Project-2.0/
├── README.md
├── fraud_analysis.sql
├── fraud_analysis.ipynb
├── dashboard_1_fixed.twb
└── Fraud-Analysis/
    └── Screenshot 2026-10-24 000613.png
```

### How to Explore the Project

1. Open `fraud_analysis.sql` to review the SQL analysis.
2. Open `fraud_analysis.ipynb` to view the notebook.
3. Open `dashboard_1_fixed.twb` in Tableau Desktop and reconnect the data source if prompted.
4. See the `Fraud-Analysis` folder for the dashboard screenshot.

### Key Learning Outcomes

- Writing SQL queries for exploratory data analysis
- Calculating fraud-related KPIs
- Building interactive Tableau dashboards
- Choosing suitable visualizations for imbalanced data
- Communicating findings through visual storytelling

### Limitations

This project focuses on exploratory analysis and dashboard-based monitoring. It is not a production fraud detection system or a trained machine learning model.

---

## Author

**Rabyea Sultana Orin**
Aspiring Data Scientist | SQL | Python | Machine Learning | Data Visualization

- GitHub: https://github.com/Orin-6
- Portfolio: https://orin-6.github.io/PORTFOLIO/
