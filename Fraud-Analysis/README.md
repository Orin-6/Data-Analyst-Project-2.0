# Credit Card Fraud Analysis Dashboard

An end-to-end data analysis and visualization project that identifies credit card fraud patterns and presents the findings through an interactive dashboard, built with **MySQL** and **Tableau**.

## Dashboard Preview

![Credit Card Fraud Dashboard](Screenshot%202026-10-24%20000613.png)

🎥 [Watch the dashboard demo](Dashboard%20-%20Trim.mp4)

## Project Overview

Credit card fraud is a major challenge in digital payment systems. This project explores transaction data to understand fraudulent activity, examine transaction patterns, and visualize fraud trends. SQL is used for data exploration, and Tableau is used to present the results in an interactive dashboard.

## Objectives

- Analyze overall transaction activity and fraudulent transactions.
- Calculate the fraud rate and fraud amount.
- Identify transaction categories associated with fraud.
- Examine monthly fraud trends.
- Compare fraudulent and non-fraudulent transactions.
- Build an interactive dashboard with filters.

## Tools & Technologies

- **MySQL**: data querying, aggregation, and exploratory analysis
- **Tableau**: interactive dashboard and visualization

## Dashboard Features

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

## SQL Analysis

SQL queries are used to calculate key metrics, including:

- Total transaction count
- Total fraud cases
- Fraud rate
- Average and maximum transaction amounts
- Fraud amount by category
- Potential duplicate transactions
- Fraud patterns across transaction categories

## Dataset

The dataset contains credit card transaction details such as amount, category, timestamp, and a fraud indicator (`is_fraud`).

- `is_fraud = 1`: fraudulent transaction
- `is_fraud = 0`: non-fraudulent transaction

It includes approximately 140,182 transactions, of which 613 are fraudulent.

**Source:** (add dataset name and link here)

## Folder Structure

```text
Fraud-Analysis/
├── README.md
├── fraud_database.sql
├── fraud_analysis.sql
├── dashboard_1_fixed.twb
├── Dashboard - Trim.mp4
└── Screenshot 2026-10-24 000613.png
```

| File | Description |
|------|-------------|
| `fraud_database.sql` | Database and table setup |
| `fraud_analysis.sql` | SQL queries for fraud analysis |
| `dashboard_1_fixed.twb` | Tableau dashboard workbook |
| `Dashboard - Trim.mp4` | Dashboard demo video |
| `Screenshot 2026-10-24 000613.png` | Dashboard screenshot |

## How to Explore the Project

1. Run `fraud_database.sql` to set up the database.
2. Run `fraud_analysis.sql` to see the analysis queries.
3. Open `dashboard_1_fixed.twb` in Tableau Desktop and reconnect the data source if prompted.
4. Watch the demo video for a quick walkthrough.

## Key Learning Outcomes

- Writing SQL queries for exploratory data analysis
- Calculating fraud-related KPIs
- Building interactive Tableau dashboards
- Choosing suitable visualizations for imbalanced data
- Communicating findings through visual storytelling

## Limitations

This project focuses on exploratory analysis and dashboard-based monitoring. It is not a production fraud detection system or a trained machine learning model.

## Author

**Rabyea Sultana Orin**
Aspiring Data Scientist | SQL | Python | Machine Learning | Data Visualization

- GitHub: https://github.com/Orin-6
- Portfolio: https://orin-6.github.io/PORTFOLIO/
