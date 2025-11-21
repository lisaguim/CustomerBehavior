<h2 align="center"> Customer Behavior & Churn Insights Using SQL </h2>
📌 Project Overview

This mini-project demonstrates advanced SQL analytics applied to a real customer dataset.
The goal is to extract meaningful insights using analytical SQL techniques such as window functions, CTEs, subqueries, and conditional transformations.

The focus is not on model building, but on data exploration, behavioral analysis, and metric creation — skills highly valuable in operational analytics, forecasting, and decision-support environments.

📜 Dataset

The dataset used comes from a public Telco Customer Churn dataset, containing demographic attributes, service usage, subscription patterns, and churn behavior.

Main fields include:
customerID, gender, SeniorCitizen, Contract, InternetService, MonthlyCharges, TotalCharges, and Churn.

🧰 Tools & Environment

  - DuckDB (for SQL execution inside Python)
  - Jupyter Notebook
  - Pandas

This setup allows running SQL queries locally without needing a database server.

🔍 SQL Topics Covered

The notebook includes 8+ advanced SQL queries demonstrating:

✔ Window Functions

  - ROW_NUMBER
  - LAG
  - Running totals (SUM() OVER)

✔ Common Table Expressions (CTEs)

  - Daily aggregations
  - Intermediate transformations
  - Cleaner query organization

✔ Subqueries

  - Filtering above/below global averages
  - Comparative metrics

✔ Conditional Logic

  - CASE WHEN classifications
  - Risk tiers
  - Charge segmentations

📊 Example Insights

  - Identification of customers with increasing monthly spending.
  - Behavioral patterns by contract type, tenure, and churn.
  - Segmentation of customers by service usage.
  - Detection of anomalies and outliers in spending behavior.

🧠 Why This Project Matters

  - This project demonstrates:
  - Ability to work with real-world messy customer data.
  - Proficiency with analytical SQL — key for roles in Operations Analytics, Forecasting, and KYC/Data Quality.
  - Capability to build insights that directly support business decisions.
  - Clean, structured thinking in query design and data storytelling.

📁 Structure

├── CustomerBehaviorChurnInsights.ipynb   # Main notebook (DuckDB + SQL queries)
└── WA_Fn-UseC_-Telco-Customer-Churn.csv     # Dataset used for analysis


🚀 Next Steps

Potential extensions include:
  
  - Feature engineering for churn prediction.
  - Operational dashboards using Power BI / Looker Studio.
  - Cohort analysis and forecasting with SQL.
