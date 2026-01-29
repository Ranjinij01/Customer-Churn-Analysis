# Customer-Churn-Analysis
Customer Retention and Churn Analysis
📌 Project Overview

Customer churn is a critical business problem that directly impacts revenue and growth. This project analyzes telecom customer data to identify key factors influencing customer churn and retention. Using SQL and Python, the analysis uncovers patterns in customer behavior and provides actionable business recommendations to reduce churn and improve customer retention.

🎯 Business Objective

Understand why customers are leaving the service (churn)

Identify high-risk churn segments

Analyze customer behavior based on tenure, contract type, charges, and payment methods

Provide data-driven recommendations to improve customer retention

🧾 Dataset

Source: Telecom Customer Churn Dataset

Rows: ~7,000 customers

Key Features:

Customer tenure

Monthly and total charges

Contract type

Payment method

Services subscribed

Target variable: Churn (Yes / No)

🛠 Tools & Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

SQL

SQLite (for KPI extraction and aggregation)

Jupyter Notebook

🧠 Methodology
1. Data Preparation

Loaded customer data from CSV

Cleaned missing and inconsistent values

Converted data types for numerical analysis

2. Exploratory Data Analysis (EDA)

Analyzed churn distribution

Studied churn trends across:

Contract type

Tenure groups

Monthly charges

Payment methods

Visualized insights using charts and plots

3. SQL-Based KPI Analysis

Loaded cleaned data into SQLite database

Used SQL queries to calculate:

Overall churn rate

Churn by contract type

Average monthly charges by churn

Tenure-based churn patterns

4. Insight Generation

Interpreted analytical results

Identified key churn drivers

Translated insights into business recommendations

📈 Key Insights

Customers on month-to-month contracts have the highest churn rate

New customers (low tenure) are more likely to churn

Customers with higher monthly charges show higher churn risk

Electronic check payment method is associated with higher churn

Long-term contracts significantly improve customer retention

💡 Business Recommendations

Encourage long-term contracts through discounts or incentives

Improve onboarding experience for new customers

Re-evaluate pricing strategies for high-charge customers

Promote automated and smoother payment methods

Proactively target high-risk customers with retention campaigns

Conclusion

This project demonstrates the use of SQL for KPI extraction and Python for exploratory data analysis and visualization, reflecting real-world data analyst workflows. The insights derived from this analysis can help businesses take proactive steps to reduce churn and improve long-term customer value.
