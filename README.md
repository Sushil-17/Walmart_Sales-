# 🛒 Walmart Sales Analysis – Python & PostgreSQL ETL Project

## 📌 Overview

This project demonstrates a complete end-to-end data analytics pipeline where raw Walmart sales data is extracted, cleaned using Python, loaded into PostgreSQL & MySQL, and analyzed using advanced SQL to generate actionable business KPIs.

It replicates a real-world ETL + analytics workflow used by data teams in retail organizations.
---
### 🛠 Tech Stack

- **Python**: Pandas, NumPy
- **Databases**: PostgreSQL, MySQL
- **Libraries**: SQLAlchemy, psycopg2, mysql-connector-python
- **Tools**: VS Code, Jupyter Notebook, Kaggle API

### ⚙️ ETL Workflow
### 1️⃣ Data Extraction

Raw Walmart sales dataset downloaded directly from Kaggle using Kaggle API.

### 2️⃣ Data Cleaning & Validation

- Removed duplicates & handled missing values
- Standardized column formats & data types
- Cleaned currency values & validated schema

### 3️⃣ Feature Engineering

- Created total_amount feature using unit price × quantity to support revenue analysis.

### 4️⃣ Data Loading

- Loaded cleaned data into PostgreSQL & MySQL using SQLAlchemy.
- Automated table creation and verified record counts.

### 5️⃣ SQL Analytics

- Executed complex SQL queries including:
- Revenue & profit analysis by category & branch
- Busiest sales day per branch
- Payment method performance
- Sales shift analysis (Morning / Afternoon / Evening)
- Year-over-Year Revenue Decrease Ratio (2022 vs 2023) using CTEs & window functions


### 📊 Business Insights Generated

- Identified top-performing product categories & branches
- Analyzed customer payment preferences
- Discovered peak shopping hours & busiest transaction days
- Calculated branch-level revenue drop ratios to detect business risks

## 📂 Project Structure

```plaintext
|-- data/                     # Raw data and transformed data
|-- sql_queries/              # SQL scripts for analysis and queries
|-- notebooks/                # Jupyter notebooks for Python analysis
|-- README.md                 # Project documentation
|-- main.py                   # Main script for loading, cleaning, and processing data
```
---

## 🚀 Key Learnings

- Built production-style ETL workflow using Python & PostgreSQL
- Strengthened advanced SQL skills (CTEs, Window Functions, Aggregations)
- Developed KPI-driven business analytics mindset

## 🔮 Future Enhancements

- Integrate Power BI for interactive dashboards
- Automate pipeline for scheduled refresh
- Add real-time ingestion layer

---

