---
title: "Week 9"
date: 2026-06-22
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

**Weekly Objectives**

- Implement the **Data Processing Layer** based on the Medallion Data Lakehouse architecture.
- Build ETL workflows using AWS Glue to process data through the Bronze, Silver, and Gold layers.
- Clean, standardize, and aggregate data to support analytics and visualization.
- Store data in an optimized format and register data tables in AWS Glue Data Catalog to enable querying with Amazon Athena.

---

**Tasks to be completed this week:**

| Day | Task | Date |
|---|---|---|
| Monday | Build AWS Glue ETL Jobs for the Bronze Layer to convert data from CSV to Apache Parquet format, automatically infer the schema, and store the data as individual tables on Amazon S3. | 15/6 |
| Tuesday | Implement the Silver Layer by cleaning and standardizing the data, including removing duplicate records, standardizing column names, processing string data, normalizing date and time formats, and validating data type consistency. | 16/6 |
| Wednesday | Build the Gold Layer by aggregating data to create analytical tables, including Dashboard Summary, Daily Revenue, Event Summary, Country Revenue, Device Summary, Payment Summary, and Source Summary. | 17/6 |
| Thursday | Store all processed data in Apache Parquet format on Amazon S3. Register the Gold Layer tables in AWS Glue Data Catalog and verify their query capability using Amazon Athena. | 18/6 |
| Friday | Test the complete ETL workflow from Raw → Bronze → Silver → Gold, verify data accuracy at each layer, evaluate processing performance, and finalize the Data Processing Layer documentation. | 19/6 |

**What were the achievements this week?**

- **Monday:**
  - **Achievement:** Successfully implemented the Bronze Layer using AWS Glue ETL, converted data from CSV to Apache Parquet format, and stored it on Amazon S3 according to the designed folder structure.
  - **Lesson Learned:** Converting data to Apache Parquet significantly reduces storage requirements, improves data reading performance, and optimizes downstream processing tasks.

- **Tuesday:**
  - **Achievement:** Successfully completed the Silver Layer with cleaned, standardized, and consistent data ready for analytical processing.
  - **Lesson Learned:** Data quality directly impacts the quality of analytical results, making data cleaning and standardization essential steps in the ETL process.

- **Wednesday:**
  - **Achievement:** Successfully built the Gold Layer by creating aggregated analytical tables for dashboards and business intelligence reporting.
  - **Lesson Learned:** Organizing aggregated data according to business use cases significantly reduces query execution time and improves the efficiency of data visualization.

- **Thursday:**
  - **Achievement:** Successfully registered the Gold Layer tables in AWS Glue Data Catalog, making them available for querying through Amazon Athena.
  - **Lesson Learned:** AWS Glue Data Catalog serves as a centralized metadata repository, enabling Amazon Athena and other analytics services to efficiently discover and access data.

- **Friday:**
  - **Achievement:** Successfully tested the complete ETL pipeline from the Raw Layer to the Gold Layer, verified data accuracy throughout every processing stage, and confirmed that the data was ready for dashboard development.
  - **Lesson Learned:** End-to-end ETL testing ensures data accuracy, integrity, and reliability before the data is used for analytics and business intelligence.

