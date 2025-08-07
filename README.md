📊 Data Warehouse and Analytics Project
Welcome to the Data Warehouse and Analytics Project repository! 🚀
This project showcases a complete data warehousing and analytics solution — from ingesting raw data to delivering actionable business insights. Designed as a portfolio-level project, it follows industry best practices in data engineering, data modeling, and analytics.

🏗️ Data Architecture
This project follows the Medallion Architecture with three layers:

🔹 Bronze Layer: Raw data ingestion from ERP and CRM systems (CSV files) into SQL Server.

🔸 Silver Layer: Cleaned, standardized, and normalized data for integration and transformation.

⭐ Gold Layer: Business-ready star schema models for efficient analytics and reporting.

📖 Project Overview
What this project includes:

Modern Data Architecture: Implemented using Medallion pattern.

ETL Pipelines: Built with SQL scripts to extract, transform, and load data.

Dimensional Modeling: Star schema with fact and dimension tables.

SQL Analytics & Reporting: Business insights on customer behavior, product performance, and sales trends.

🎯 Key Skills Demonstrated
This project is ideal for showcasing expertise in:

🧠 SQL Development

🏗️ Data Architecture

🔄 ETL Pipeline Development

📊 Data Modeling

📈 Data Analytics

💼 Data Engineering

🛠️ Tools & Resources
Everything is free and easily accessible!

📁 Datasets: ERP and CRM sample data (CSV)

🧰 SQL Server Express: Host your data warehouse

🖥️ SSMS (SQL Server Management Studio): Query and manage databases

🧠 DrawIO: Design architecture, data flows, and models

📋 Notion: Project templates, planning, and documentation

🔧 Git & GitHub: Version control and collaboration

🚀 Project Requirements
🔧 Data Engineering
Objective: Build a consolidated SQL Server data warehouse using data from ERP and CRM sources.

Load CSV data into SQL Server

Cleanse and validate datasets

Integrate both systems into a unified analytical model

No historization needed – focus on the latest dataset

Document architecture, schema, and naming standards

📊 Data Analysis & BI
Objective: Deliver meaningful analytics using SQL queries and reporting logic.

Analyze Customer Behavior

Evaluate Product Performance

Track Sales Trends

Refer to docs/requirements.md for detailed analytics questions.

📂 Repository Structure
graphql
Copy
Edit
data-warehouse-project/
│
├── datasets/                  # ERP and CRM CSV files
├── docs/                      # Architecture, models, and documentation
│   ├── etl.drawio             # ETL techniques diagram
│   ├── data_architecture.drawio
│   ├── data_catalog.md        # Dataset field descriptions
│   ├── data_flow.drawio
│   ├── data_models.drawio     # Star schema visual
│   ├── naming-conventions.md
│
├── scripts/                   # ETL scripts (SQL)
│   ├── bronze/                # Raw ingestion
│   ├── silver/                # Data transformation
│   ├── gold/                  # Analytics-ready modeling
│
├── tests/                     # Data quality tests
├── README.md                  # Project overview (this file)
├── LICENSE
├── .gitignore
└── requirements.txt           # Tool dependencies
