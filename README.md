# HDB Resale Data Lakehouse Pipeline

An end-to-end data pipeline built using Python, AWS S3, Databricks, and PySpark to process HDB resale transaction data.

## Architecture

```text
API Ingestion (Python)
        |
        v
AWS S3
        |
        v
Databricks + PySpark
```