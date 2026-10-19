# SQL Data Analytics Project

## 📌 Overview

This project focuses on exploring and analyzing sales data using **SQL Server** to uncover meaningful business insights, identify sales trends, and understand customer and product performance.

I worked on this project to strengthen my SQL skills through hands-on practice with real-world data analysis scenarios, from basic data exploration to advanced analytical queries and reporting.

The project covers exploratory data analysis, advanced analytics, customer segmentation, product performance analysis, and sales reporting.

## 🎯 Project Objectives

- Explore the database structure and understand the relationships between tables.
- Analyze sales data to identify key business metrics.
- Investigate sales trends over time.
- Identify top-performing products and customers.
- Calculate running totals, cumulative metrics, and performance indicators.
- Segment customers based on purchasing behavior.
- Generate customer and product reports to support data-driven decision-making.

## 🛠️ Tools & Technologies

- **SQL Server** – Database management and querying
- **SQL Server Management Studio (SSMS)** – Writing and executing SQL queries
- **SQL** – Data exploration, transformation, aggregation, and analysis
- **Git & GitHub** – Version control and project documentation

## 📂 Project Structure

```text
sql-data-analytics-project/
│
├── 01_datasets/
│   ├── DataWarehouseAnalytics.bak
│   └── csv-files/
│
├── 02_docs/
│   ├── Project Roadmap.png
│
└── 03_scripts/
    ├── 00_init_database.sql
    ├── 01_*.sql
    ├── 02_*.sql
    ├── ...
    └── 13_*.sql
```

## 📊 Project Workflow

### 1. Exploratory Data Analysis (EDA)

Scripts 01–06 focus on understanding the data and identifying initial business insights.

- Database exploration and schema understanding
- Dimension and date exploration
- Measures and key metrics analysis
- Magnitude analysis
- Ranking analysis to identify top-performing products and customers

### 2. Advanced Data Analytics

Scripts 07–13 focus on deeper analysis using SQL techniques.

- Changes and trends over time
- Cumulative sales and running totals
- Performance analysis
- Part-to-whole analysis
- Customer segmentation
- Product performance analysis
- Customer and product reporting

## 💡 Key SQL Concepts Practiced

- `SELECT`, `WHERE`, `ORDER BY`
- Aggregate functions: `SUM()`, `AVG()`, `MIN()`, `MAX()`, `COUNT()`
- `GROUP BY` and `HAVING`
- Joins and table relationships
- Common Table Expressions (CTEs)
- Subqueries
- Window functions
- `CASE` expressions
- Date functions and time-based analysis
- Views
- Ranking and cumulative calculations
- Customer segmentation and report generation

## 📈 Business Insights

The analysis is designed to help answer questions such as:

- Which products and customers generate the highest sales?
- How do sales change over time?
- Which product categories contribute most to overall sales?
- How can customers be grouped based on purchase history and spending?
- Which products perform well or poorly?
- What patterns can help support business decisions?

## 🚀 Getting Started

### Prerequisites

- SQL Server 2022 or newer if restoring the provided database backup
- SQL Server Management Studio (SSMS)
- Git, if cloning the repository

### Option 1: Restore the database backup

1. Clone or download this repository.
2. Open SSMS and connect to your SQL Server instance.
3. Restore `01_datasets/DataWarehouseAnalytics.bak` using the database restore wizard.
4. Open the SQL scripts in `03_scripts/`.
5. Execute the scripts in numerical order and review the results.

### Option 2: Build the database from CSV files

1. Ensure the CSV files are available in `01_datasets/csv-files/`.
2. Open `03_scripts/00_init_database.sql` in SSMS.
3. Check the file paths in the script and update them to match your local folder.
4. Ensure the SQL Server service account has permission to read the CSV files.
5. Execute the script to create and populate the database.

## 📚 What I Learned

Through this project, I gained practical experience in:

- Writing structured SQL queries to answer analytical questions.
- Understanding database schemas, dimensions, and fact tables.
- Aggregating and transforming data for reporting.
- Using CTEs and window functions for advanced analysis.
- Analyzing customer purchasing behavior and product performance.
- Organizing SQL scripts into a structured analytical workflow.
- Turning raw sales data into meaningful business insights.

## 👨‍💻 Author

**Sai Kiran Reddy**

This project represents my hands-on practice in SQL, data analytics, and database querying as part of my journey toward becoming a skilled Data Engineer.

---

⭐ If you find this project useful, feel free to explore the SQL scripts and the analytical techniques used throughout the project.
