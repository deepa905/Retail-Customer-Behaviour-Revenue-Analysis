# Retail Customer Behaviour & Revenue Analysis

## Project Overview
This project analyses customer purchasing behaviour, revenue trends, and subscription patterns using Python, SQL, and Power BI. The objective was to identify which customer segments and product categories contribute most to business revenue and to uncover insights that can support data-driven marketing and customer engagement strategies.

The analysis combines data cleaning, KPI reporting, SQL-based business analysis, and interactive dashboard development to simulate a real-world analytics workflow.

---

# Project Highlights
- Analysed customer transaction and demographic data across multiple product categories
- Performed data cleaning and exploratory analysis using Python
- Built SQL queries to calculate business KPIs and segment-level insights
- Developed an interactive Power BI dashboard for self-service analysis
- Identified that product category had a stronger impact on revenue than customer age

---

# Business Problem
A retail business wants to better understand:
- Which customer segments generate the highest revenue
- Which product categories drive customer spending
- Whether demographic factors influence purchasing behaviour
- Which customer groups show higher subscription conversion rates

The goal of the analysis is to support better marketing decisions and improve customer targeting strategies.

---

# Dataset Overview

The dataset contains customer demographic and transaction-related information, including:

- Customer Age
- Gender
- Product Category
- Purchase Amount
- Subscription Status
- Customer Location
- Transaction Behaviour

---

# Tools & Technologies

| Tool | Purpose |
|---|---|
| Python (Pandas, NumPy, Matplotlib) | Data cleaning and exploratory analysis |
| SQL | KPI calculations and business analysis |
| Power BI | Dashboard development and visualisation |
| Excel | Data review and summary reporting |
| Google BigQuery / MySQL | SQL query execution |

---

# Business Questions

The analysis focused on answering the following business questions:

1. Which product categories generate the highest revenue?
2. Does customer age significantly influence spending behaviour?
3. Which customer groups contribute most to subscription conversions?
4. Which demographic segments have the highest average purchase value?
5. How do purchasing patterns vary across categories and customer groups?

---

# Data Cleaning & Preparation

The dataset was cleaned and prepared before analysis by:

- Handling missing and inconsistent values
- Validating data types and column formats
- Removing duplicate records
- Standardising categorical values
- Preparing structured datasets for SQL and dashboard reporting

---

# SQL Analysis

SQL was used to calculate business KPIs and segment-level insights, including:

- Total Revenue
- Average Purchase Value
- Revenue by Product Category
- Customer Segment Analysis
- Subscription Conversion Rate
- Category-wise Purchase Trends

### Sample SQL Query

```sql
SELECT product_category,
       SUM(purchase_amount) AS total_revenue
FROM customer_data
GROUP BY product_category
ORDER BY total_revenue DESC;
```

---

# Key Insights

- Product category had a stronger impact on revenue than customer age
- Electronics customers showed the highest average purchase value
- Subscription conversion rates varied significantly across customer groups
- High-spending customers were concentrated within specific product categories
- Certain demographic segments contributed disproportionately to total revenue

---

# Power BI Dashboard

The Power BI dashboard was developed to help business users interactively explore customer and revenue trends.

### Dashboard Features
- KPI Cards
- Revenue Analysis
- Category-wise Sales Trends
- Customer Segment Filters
- Subscription Behaviour Analysis
- Interactive Slicers and Drilldowns

---

# Dashboard Preview

<img width="689" height="376" alt="image" src="https://github.com/user-attachments/assets/9c65ab3f-2edb-4a6a-b535-b031bf819879" />


---

# Business Recommendations

Based on the analysis:

- Focus marketing campaigns on high-performing product categories
- Improve subscription targeting for high-spending customer segments
- Develop personalised promotional strategies based on purchasing behaviour
- Use segment-level revenue insights to optimise customer engagement efforts

---

# Repository Structure

```text
retail-customer-behaviour-analysis/
│
├── data/
├── notebooks/
├── sql/
├── dashboard/
├── README.md
```

---

# Project Workflow

```text
Raw Data
→ Data Cleaning (Python)
→ Exploratory Analysis
→ SQL KPI Analysis
→ Power BI Dashboarding
→ Business Insights & Recommendations
```

---

# Conclusion

This project demonstrates how SQL, Python, and Power BI can be combined to transform raw customer data into meaningful business insights. The analysis highlights the importance of customer segmentation, KPI reporting, and visual analytics in supporting data-driven business decisions.

---

# Author

Deepa Thomas  
Data Analyst | SQL • Python • Power BI • Business Analytics

GitHub: https://github.com/deepa905
