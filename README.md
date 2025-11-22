# SQL_Data_Warehouse_Project
Building a modern data warehouse with SQL Server, including ETL processes, data modelling and analytics

Welcome to the Data Warehouse and Analytics Project repository! 🚀
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights.


🏗️ Data Architecture

The data architecture for this project follows the Medallion Architecture with Bronze, Silver and Gold layers:
1. Bronze Layer: stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. Silver Layer: this layer includes data cleansing, standardization and normalization processes to prepare data for analysis.
3. Gold Layer: contains business-ready data, modeled into a star schema, required for reporting and analytics.


📖 Project Overview

This project involves:

1. Data Architecture: designing a modern Data Warehouse with Medallion Architecture Bronze, Silver and Gold layers.
2. ETL Pipelines: extracting, transforming, and loading data from the source systems into the warehouse.
3. Data Modeling: developing fact and dimension tables optimized for analytical queries.
4. Analytics & Reporting: creating SQL-based reports and dashboards for actionable insights.


🚀 Project Requirements

Building the Data Warehouse (Data Engineering)

Objective

Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

Specifications

- Data Sources: import data from two source systems (ERP and CRM) provided as CSV files.
- Data Quality: cleanse and resolve data quality issues prior to analysis.
- Integration: combine both sources into a single, user-friendly data model designed for analytical queries.
- Scope: focus on the latest dataset only; historization of data is not required.
- Documentation: provide clear documentation of the data model to support both business stakeholders and analytics teams.
- BI: Analytics & Reporting (Data Analysis)

Objective

Develop SQL-based analytics to deliver detailed insights into:

- Customer Behavior
- Product Performance
- Sales Trends

These insights empower stakeholders with key business metrics, enabling strategic decision-making.


