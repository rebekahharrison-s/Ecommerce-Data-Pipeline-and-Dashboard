# Ecommerce-Data-Pipeline-and-Dashboard
End-to-end ETL pipeline simulating a production-grade e-commerce data workflow, including ingestion from public datasets, data cleaning, transformation, and preparation for analytics and dashboarding.

E-Commerce ETL Pipeline — Data Engineering Project
##Overview

This project demonstrates a production-style ETL (Extract, Transform, Load) pipeline built using Python, designed to simulate a real-world e-commerce data workflow.

The pipeline ingests raw product data from public datasets, performs cleaning and transformation, and prepares structured outputs suitable for analytics, dashboards, or data warehousing.

##Key Features

*End-to-end ETL pipeline

*Data ingestion from GitHub-hosted datasets

*Data cleaning & validation

*Transformation logic for analytics-ready datasets

*Structured outputs for downstream use (e.g., BI tools, dashboards)

*Designed to reflect real-world data engineering practices

##Datasets

This project uses publicly available datasets from:

Amazon product dataset

Shein product dataset

(Source: luminati-io dataset samples)

##Pipeline Architecture
1. Extract

Data is pulled dynamically from GitHub repositories

Handles multiple dataset sources via configurable keys

2. Transform

Data cleaning (null handling, type corrections)

Schema standardisation across datasets

Feature engineering for analytics use cases

3. Load

Outputs structured, clean datasets

Ready for:

Data warehouses

BI dashboards

Analytical workflows

##Tech Stack

Python

Pandas

Colab Notebook

GitHub (data source + version control)

##Example Use Cases

Building dashboards (Power BI / Tableau)

Product pricing analysis

Market comparison across e-commerce platforms

Data warehouse ingestion prototype

##How to Run

Clone the repository:

git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

Install dependencies:

pip install pandas requests

Open the notebook:

jupyter notebook

Run:

ETL_Pipeline_DE_EX_ECOMM.ipynb

##Future Improvements

Add orchestration (e.g. Airflow)

Integrate cloud storage (AWS S3 / Azure Blob)

Load into a data warehouse (Snowflake / BigQuery)

Add data quality monitoring

Convert notebook into modular production code

##Why This Project Matters

This project demonstrates:

Strong understanding of ETL design patterns

Ability to work with real-world messy data

Practical data engineering skills beyond theory

Readiness for production-level thinking

##Author

Rebekah Harrison
(Data Engineering | Analytics | Python | SQL)
