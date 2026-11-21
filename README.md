# dbt-Big-Query---Procurement-Analytics
A personal data engineering project that demonstrates how procurement data can be transformed into analytics-ready datasets using dbt and Google BigQuery.  The project simulates a procurement environment with suppliers, purchase orders, purchase order items and cost centres.



Procurement Analytics – dbt & BigQuery
Overview

A personal data engineering project focused on building a procurement analytics data warehouse using dbt and Google BigQuery.

The project simulates a procurement environment and transforms raw procurement data into structured, analytics-ready datasets.

Objectives
Build a cloud-based data warehouse using Google BigQuery.
Transform raw data using dbt and SQL.
Implement staging, intermediate and dimensional data models.
Apply data quality tests and documentation.
Analyse procurement spend and supplier performance.
Prepare datasets for business intelligence and reporting.
Technology Stack
Technology	Purpose
SQL	Data transformation
dbt Core	Data modelling and transformation
Google BigQuery	Cloud data warehouse
Python	Data generation and processing
Git & GitHub	Version control
Power BI	Data visualisation (planned)
Project Structure
text
procurement-analytics-dbt/
│
├── data/               # Synthetic source datasets
├── models/             # dbt data models
├── scripts/            # Python scripts
├── README.md
├── .gitignore
└── requirements.txt

Planned Data Models
stg_suppliers – Clean supplier data
stg_purchase_orders – Clean purchase order data
stg_purchase_order_items – Clean order item data
fct_procurement_spend – Procurement spend fact table
dim_suppliers – Supplier dimension
dim_cost_centers – Cost centre dimension
Project Status

In Progress – Initial setup

Repository created
Initial project structure
Create synthetic procurement datasets
Set up Google BigQuery
Initialise dbt project
Implement staging models
Build dimensional data models
Add data quality tests
Connect Power BI dashboard
Data Disclaimer

All datasets will be fictional and generated for educational purposes. No confidential company, supplier or business data is used.

Author

Business Information Technology Student – FHNW

Personal learning project exploring modern data engineering and business intelligence.
