# Customer Churn Analysis – Exploratory Data Analysis & Power BI Dashboard

## Overview
This project analyzes customer churn using Python-based Exploratory Data Analysis (EDA) and a Power BI dashboard. The goal is to understand which customer segments are most likely to churn and identify the key factors driving churn.

This version of the project includes:
- Data cleaning and exploration in Python
- Churn analysis using grouping and aggregation
- Visual insights into churn drivers
- A complete Power BI dashboard built from the dataset

---

## Exploratory Data Analysis (Python)
The EDA covers:
- Data quality checks and type conversion
- Missing value handling
- Feature creation (usage category, tenure group, charge group)
- Churn rate calculations across different customer segments

Key relationships analyzed:
- Usage category vs churn
- Support tickets vs churn
- Satisfaction score vs churn
- Contract type vs churn
- Tenure group vs churn
- Charge group vs churn
- Internet service vs churn

Notebook: `customer_churn_eda.ipynb`

---

## Power BI Dashboard
The Power BI dashboard visualizes churn patterns for quick business understanding.

### Metrics:
- Total Customers
- Churn Rate
- Average Monthly Charges
- Average Tenure

### Visuals:
- Churn Rate by Contract Type
- Churn Rate by Satisfaction Score
- Churn Rate by Internet Service Type
- Churn Rate by Charge Group
- Churn Rate by Tenure Group

Dashboard file: `Customer_Churn.pbix`  
Screenshot: `dashboard_churn.png`

---

## Key Findings
- Low usage customers have the highest churn rate.
- Customers with multiple support tickets show extremely high churn.
- Low satisfaction scores (1–2) have nearly 100% churn.
- Month-to-month contract customers churn far more than long-term customers.
- Early-tenure customers (0–12 months) churn the most.
- Higher monthly charges correlate with higher churn.
- Fiber-optic customers churn more than DSL or no-internet customers.

---

## Business Insights
- Improve customer onboarding in the first 12 months.
- Prioritize customers facing repeated support issues.
- Launch satisfaction improvement programs targeting low scorers.
- Incentivize long-term contract adoption.
- Revisit pricing strategies in higher charge tiers.

---

## Repository Contents
