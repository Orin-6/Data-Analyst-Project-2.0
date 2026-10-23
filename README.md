# Data-Analyst-Project-2.0
A collection of data analysis projects showcasing practical skills in SQL, Python, Excel, Power BI, Tableau, and data visualization through real-world datasets and insightful analysis.
# Credit Card Fraud Analysis Dashboard

An end-to-end data analysis and visualization project focused on identifying credit card fraud patterns, analyzing transaction behavior, and presenting actionable insights using **MySQL and Tableau**.

## Project Overview

Credit card fraud is a major challenge in digital payment systems. This project explores transaction data to understand fraudulent activity, examine transaction patterns, and visualize fraud trends through an interactive Tableau dashboard.

The project combines SQL-based data exploration with interactive data visualization to make fraud-related patterns easier to understand.

## Objectives

- Analyze overall transaction activity and fraudulent transactions.
- Calculate the fraud rate and fraud amount.
- Identify transaction categories associated with fraudulent activity.
- Examine monthly fraud trends.
- Compare fraudulent and non-fraudulent transactions.
- Build an interactive dashboard with filters for exploring the data.

## Tools & Technologies

- **MySQL** — Data querying, aggregation, and exploratory analysis.
- **Tableau** — Interactive dashboard and data visualization.
- **SQL** — Filtering, conditional calculations, and aggregation.
- **Data Visualization** — KPI cards, bar charts, line charts, and pie charts.

## Dashboard Features

### Key Performance Indicators (KPIs)
- Total Transactions
- Fraud Cases
- Fraud Rate
- Fraud Amount

### Visualizations
- Fraud Cases by Category
- Fraud Amount by Category
- Monthly Distribution of Fraud Cases
- Monthly Fraud Amount Trend
- Fraud vs. Non-Fraud Distribution

### Interactive Filters
- Transaction Date
- Transaction Category
- Fraud Status

The filters allow users to explore transaction patterns and compare fraudulent and non-fraudulent activity.

## SQL Analysis

SQL queries are used to explore the transaction dataset and calculate key metrics, including:

- Total transaction count
- Total fraud cases
- Fraud rate
- Average and maximum transaction amounts
- Fraud amount by category
- Potential duplicate transactions
- Fraud patterns across transaction categories

## Dataset

The project uses a credit card transaction dataset containing transaction details, transaction amounts, categories, timestamps, and a fraud indicator (`is_fraud`).

- `is_fraud = 1`: Fraudulent transaction
- `is_fraud = 0`: Non-fraudulent transaction

The dataset used in this project contains approximately 140,182 transaction records, including 613 fraudulent transactions. Update these figures if your final dataset differs.

**Dataset source:** Add the original dataset name and source link here, and follow its licensing and attribution requirements.

## Repository Structure

Organize the repository like this:

```text
credit-card-fraud-analysis/
├── README.md
├── sql/
│   └── fraud_analysis.sql
├── dashboard/
│   └── credit_card_fraud_dashboard.twbx
├── screenshots/
│   └── dashboard.png
└── data/
    └── README.md
```

*Adjust the filenames and folders to match the files you actually upload.*

## Key Learning Outcomes

- Writing SQL queries for exploratory data analysis.
- Calculating fraud-related KPIs.
- Building interactive Tableau dashboards.
- Selecting suitable visualizations for imbalanced transaction data.
- Communicating data-driven findings through visual storytelling.

## How to Explore the Project

1. Review the SQL scripts to understand the analysis.
2. View the dashboard screenshot in the `screenshots` folder.
3. Open the Tableau packaged workbook (`.twbx`) in Tableau Desktop, if included.
4. Connect the workbook to the required data source if prompted.

## Limitations

This project focuses on exploratory analysis and dashboard-based monitoring. It does not represent a production fraud detection system or a trained machine learning model.

## Author

**Rabyea Sultana Orin**

Aspiring Data Scientist | SQL | Python | Machine Learning | Data Visualization

- GitHub: https://github.com/Orin-6
- Portfolio: https://orin-6.github.io/PORTFOLIO/

---

If you find this project useful, feel free to explore the repository and share feedback.
