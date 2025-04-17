# Revenue-Dashboard
This project demonstrates a complete data pipeline for business intelligence and visualization. Data was extracted using SQL queries in MySQL Workbench, cleaned and transformed using Python (Pandas and SQLAlchemy), and finally visualized in a Power BI dashboard.

The dashboard provides actionable insights into key performance indicators such as [e.g., sales analysis, product performance, revenue trends — update based on your actual data] for effective decision-making.

Workflow Overview:
Data Extraction
-Queried data from a PostgreSQL database using MySQL Workbench.
-Fetched multiple tables dynamically using SQLAlchemy and pandas.read_sql().

Data Cleaning & Transformation (Python)
-Removed null values and handled negative ages using .abs().
-Identified and removed duplicates.
-Engineered new features such as total_sale_amount = quantity_sold * price.
-Updated the sales table and exported all tables to an Excel file.

Visualization (Power BI)
-Imported the cleaned Excel file (Jforce.xlsx) into Power BI.
-Created an interactive dashboard with key visuals, slicers, and filters for dynamic analysis.

Tech Stack:
SQL: PostgreSQL (via MySQL Workbench)
Python: Pandas, SQLAlchemy, XlsxWriter
Visualization: Power BI
