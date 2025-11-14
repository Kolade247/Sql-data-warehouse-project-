# Sql-data-warehouse-project-
SQL Data Warehouse Project

Building a modern data warehouse using SQL Server, following best practices in ETL processes, data modeling, and analytics.

🚀 Project Overview

This project demonstrates how to design and implement a full end-to-end data warehouse solution, starting from raw source files and transforming them into analytics-ready datasets.

It follows the Medallion Architecture (Bronze → Silver → Gold) to ensure data quality, scalability, and maintainability.

📁 Architecture

Sources:

CRM system (CSV files)

ERP system (CSV files)

Folder-based file ingestion

Layers:

Bronze: Raw ingested data

Silver: Cleaned and standardized data

Gold: Business-ready, analytics-friendly tables

Consumption:

BI & Reporting (Power BI, Excel)

SQL & Ad-hoc analysis

Machine Learning models

🛠️ Tech Stack

SQL Server / SSMS

SQL Server Integration Services (SSIS)

Data Modeling (Star/Snowflake Schema)

T-SQL for Transformations

GitHub for Version Control

📦 Key Features

Automated extraction of CSV files

Data quality checks & validations

Staging → Transformation → Presentation layers

Fact and Dimension table design

Incremental loading logic

Audit & logging mechanisms

📊 What This Project Demonstrates

✔ How to build a scalable data pipeline
✔ How to structure data for analytics and BI
✔ How to apply the Medallion Architecture in SQL Server
✔ How to model data using facts, dimensions, and relationships
✔ How to create clean, reusable SQL scripts for ETL
