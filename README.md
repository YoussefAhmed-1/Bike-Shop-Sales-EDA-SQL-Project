# 🚴 Bike Shop Sales Analysis | SQL Project

## 📌 Project Overview

This project focuses on analyzing a bike shop's sales data using **Microsoft SQL Server** to explore business performance and extract meaningful insights from the data.

The project involves working with a structured database, organizing datasets, and writing SQL queries to investigate sales-related information and support data-driven business understanding.

## 🎯 Project Objectives

- Explore and understand the underlying sales database.
- Analyze business data using SQL queries.
- Extract meaningful information from structured datasets.
- Practice SQL techniques for data exploration and analysis.
- Develop a better understanding of business performance through data.

## 🛠️ Tools & Technologies

- **Database:** Microsoft SQL Server
- **Query Language:** SQL
- **IDE:** SQL Server Management Studio (SSMS)
- **Data Formats:** CSV, SQL Server Database Backup (.bak)

## 📂 Repository Structure

```text
Bike-analysis-sql/
│
├── 01_datasets/
│   └── Database backup and CSV datasets
│
├── 02_docs/
│   └── Project documentation and notes
│
├── 03_scripts/
│   └── SQL scripts and analysis queries
│
├── LICENSE
└── README.md
```

## 🗄️ Database Setup

You can prepare the database using either of the following methods:

### Option 1: Restore the Database Backup

1. Open SQL Server Management Studio (SSMS).
2. Connect to your SQL Server instance.
3. Right-click on **Databases**.
4. Select **Restore Database**.
5. Choose the backup file located in `01_datasets/`.
6. Complete the restoration process.

**Note:** The existing database backup requires SQL Server 2022 or newer.

### Option 2: Build the Database from CSV Files

1. Make sure the CSV datasets are available in the `01_datasets/` directory.
2. Open the initialization script:

   `03_scripts/00_init_database.sql`

3. Update the CSV file paths in the script to match your local environment.
4. Execute the script in SSMS to create and populate the database.

## 🔍 Analysis Workflow

The project follows a structured SQL analysis workflow:

1. **Database Preparation:** Set up the database and prepare the datasets for analysis.
2. **Data Exploration:** Examine the database structure and understand the available data.
3. **SQL Analysis:** Write and execute queries to investigate the business data.
4. **Insight Extraction:** Interpret query results and identify meaningful business information.

## 📁 SQL Scripts

The `03_scripts/` directory contains the SQL scripts used throughout the project, organized in sequence.

The initialization script is:

- `00_init_database.sql` – Creates and populates the database using the provided CSV files.

## 📈 Key Learning Outcomes

Through this project, I gained practical experience in:

- Working with relational databases.
- Writing SQL queries for business data analysis.
- Exploring structured datasets.
- Preparing databases using CSV files.
- Organizing SQL scripts into a structured analytical workflow.
- Understanding how SQL can support business analysis.

## 🚀 Future Improvements

- Expand the analysis with additional business questions.
- Develop more detailed sales performance metrics.
- Identify trends and patterns in sales data.
- Build an interactive dashboard using Power BI.

## 👤 Author

**Youssef Ahmed**

GitHub: [@YoussefAhmed-1](https://github.com/YoussefAhmed-1)

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
