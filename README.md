# Retail Sales ETL Pipeline with Databricks & PySpark

A simple ETL pipeline built using **Databricks and PySpark** to process and analyze retail transaction data.

The project follows the **Medallion Architecture (Bronze → Silver → Gold)** to demonstrate data ingestion, data cleaning, transformation, and business-level analytics.

---

## Project Overview

The goal of this project is to build a small end-to-end ETL pipeline for retail transaction data.

## Dataset

The transaction dataset used in this project was obtained from the following repository:

[Alex The Analyst](https://github.com/AlexTheAnalyst/DatabricksSeries/tree/main/Data%20Engineering)

The pipeline:

1. Takes raw CSV transaction data as input
2. If multiple csv files for transaction, combines them into single bronze dataset
3. Cleans and validates the data
4. Generates sales insights and visualizations

---

## Technologies Used

- **Databricks**
- **PySpark**
- **Python**
- **SQL**
- **GitHub**
- **Delta Tables**
- **Medallion Architecture**
