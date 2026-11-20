# End-to-End Customer Retention Analysis Platform

## Project Overview

This project presents an end-to-end Customer Retention Analysis Platform integrating cloud-based data engineering, machine learning, workflow orchestration, and business intelligence.

The platform is developed using Azure Databricks, Apache Spark (PySpark), Apache Airflow, PySpark MLlib, and Microsoft Power BI.

It aims to transform raw customer data into meaningful business insights and predictive customer churn analytics.

## Technology Stack

- Azure Databricks
- Azure Data Lake Storage Gen2
- Apache Spark / PySpark
- Medallion Architecture (Bronze, Silver, Gold)
- Apache Airflow
- PySpark MLlib
- Python
- Microsoft Power BI
- DAX

## Project Architecture

Data Sources → Bronze Layer → Silver Layer → Gold Layer → Feature Engineering → Machine Learning → Power BI Dashboards

Apache Airflow orchestrates the execution of the Databricks notebooks.

## Machine Learning Models

Three supervised classification algorithms are implemented:

1. Decision Tree
2. Random Forest
3. Logistic Regression

### Model Performance

| Model | Accuracy | Precision | Recall | F1-Score |
|---|---:|---:|---:|---:|
| Decision Tree | 0.8218 | 0.8041 | 0.8218 | 0.7417 |
| Random Forest | 0.8217 | 0.8535 | 0.8217 | 0.7414 |
| Logistic Regression | 0.8216 | 0.6751 | 0.8216 | 0.7412 |

## Power BI Dashboards

The project includes dashboards covering:

- Executive Analytics
- Customer Demographics
- Revenue Analytics
- Customer Engagement
- Support and Services Analytics
- Churn and Retention Analysis
- Customer 360
- Product and Service Usage Analytics
- Customer Segmentation
- Geographic Analytics
- Machine Learning Model Performance
- Data Quality and Pipeline Monitoring

## Workflow Orchestration

Apache Airflow coordinates the execution of 15 Azure Databricks notebooks through a Directed Acyclic Graph (DAG).

## Key Features

- Automated data ingestion and transformation
- Medallion Architecture
- Customer feature engineering
- Predictive churn modelling
- Workflow orchestration
- Interactive business intelligence dashboards

## Research Objective

To develop a scalable and integrated analytical platform that supports customer behaviour analysis, churn prediction, and data-driven customer retention strategies.

## Author

Ashwini Zade

Customer Analytics | Data Engineering | Machine Learning


