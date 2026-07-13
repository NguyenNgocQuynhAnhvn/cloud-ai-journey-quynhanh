---
title: "Week 9"
date: 2026-06-22
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

> **Duration:** 22/06/2026 - 28/06/2026 Implementing the Bronze, Silver, and Gold Layers in a Medallion Data Lakehouse Architecture

---

### Weekly Objectives

- Implement the Data Processing Layer based on the Medallion Data Lakehouse architecture.
- Build ETL pipelines using AWS Glue to process data through the Bronze, Silver, and Gold layers.
- Clean, standardize, and aggregate data to support business analytics and data visualization.
- Organize data in an optimized storage format and register datasets in the AWS Glue Data Catalog to enable querying with Amazon Athena.

---

### Work Activities

- Develop **AWS Glue ETL Jobs** to process data across the entire pipeline from **Raw → Bronze → Silver → Gold**.
- Implement the **Bronze Layer** by converting raw CSV files into **Apache Parquet** format, performing automatic schema inference, and organizing datasets into separate tables on **Amazon S3**.
- Implement the **Silver Layer** by cleaning and standardizing data, including removing duplicate records, standardizing column names, processing string values, normalizing date and time formats, and validating data type consistency.
- Implement the **Gold Layer** by creating business-oriented analytical datasets, including **Dashboard Summary**, **Daily Revenue**, **Event Summary**, **Country Revenue**, **Device Summary**, **Payment Summary**, and **Source Summary** tables.
- Perform data aggregation to calculate key business metrics, including customer count, order count, total revenue, average order value, and revenue breakdowns by country, device type, payment method, and traffic source.
- Store all processed datasets in **Apache Parquet** format on **Amazon S3** to optimize storage efficiency and query performance.
- Register the Gold Layer analytical tables in the **AWS Glue Data Catalog**, making them available for querying through **Amazon Athena**.
- Validate the complete ETL workflow to ensure that data is correctly processed and stored at every stage of the Medallion architecture.

---

### Achievements

- Successfully implemented the **Data Processing Layer** based on the Medallion Data Lakehouse architecture.
- Successfully developed automated **AWS Glue ETL pipelines** covering the complete data processing workflow from **Raw → Bronze → Silver → Gold**.
- Successfully cleaned, standardized, and aggregated the data, ensuring high data quality for downstream analytics.
- Completed the Bronze, Silver, and Gold layers, with all processed datasets stored in **Apache Parquet** format on **Amazon S3**.
- Successfully registered the analytical datasets in the **AWS Glue Data Catalog**, enabling efficient querying through **Amazon Athena**.
- Established a robust data foundation for building business dashboards and supporting subsequent data analytics activities.