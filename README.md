# FP&A Budget & Revenue Analysis (PostgreSQL + SQL + Python + Power BI)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PowerBI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

---
## Overview
This project demonstrates my ability to:
- Build and manage a PostgreSQL database from scratch
- Clean and transform financial datasets using SQL
- Perform budgeting, revenue forecasting, and YoY trend analysis
- Integrate Python for advanced data analysis
- Develop executive dashboards in Power BI

---

## Tech Stack
- **Database**: PostgreSQL 15
- **Languages**: SQL, Python (Pandas, Matplotlib)
- **Visualization**: Power BI
- **Version Control**: GitHub

---

## Project Workflow
1. **Database Creation**  
   - Built a PostgreSQL database (`FP&A Mock`) to host financial datasets.
   - Designed normalized tables for departments, budget, and actuals.
2. **Data Ingestion & Transformation**  
   - Inserted mock FP&A data (2023–2025) for budgeting and actuals.
   - Developed SQL queries to calculate budget variances, cost allocations, and YoY revenue growth.
3. **Python Analysis**  
   - Connected to PostgreSQL using `psycopg2` & `pandas` for data extraction.
   - Performed forecasting and variance analysis.
4. **Visualization**  
   - Created Power BI dashboards for revenue vs. budget trends and cost center performance.

---

## Database Schema
### Key Tables
- **departments**: department_id, department_name
- **budget**: budget_id, department_id, fiscal_year, revenue, expenses, marketing_spend, net_income
- **actuals**: actual_id, department_id, fiscal_year, revenue, expenses, marketing_spend, net_income

### Setup Instructions
1. Install PostgreSQL 15+
2. Run database scripts (found in `/database/`):
   - `01_create_database.sql`
   - `02_schema_definition.sql`
   - `03_sample_data_inserts.sql`
3. Connect using local credentials (`.env` file not included in repo).

---

## Screenshots
![Dashboard Screenshot](visuals/dashboard_screenshot_1.png)

---

## Key Insights
- Budget vs. Actual variance showed a 12% underrun in marketing spend.
- Revenue growth YoY: +18% (2024 vs 2023), +22% (2025 vs 2024).

---


---

## Author
**Marvin Gaitán Jr**  
[LinkedIn](https://www.linkedin.com/in/marvin-gaitán-jr-ab830219a)

