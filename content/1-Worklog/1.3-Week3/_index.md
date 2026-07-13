---
title: "Week 3"
date: 2026-05-03
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

> **Duration:** 04/05/2026 - 10/05/2026 Building a Data Lake and Data Engineering

---

### Weekly Objectives

- Understand and build a Data Lake: Learn the fundamental concepts of a Data Lake and how to implement one using Amazon S3.
- Learn the ETL process: Understand how to extract, transform, and load (ETL) data using AWS data engineering services.
- Automate data processing: Use serverless services to build automated data pipelines.
- Optimize data management: Organize data efficiently to improve query performance and support analytics in the following weeks.

---

### Learning Contents

#### 1. Data Lake Fundamentals and Implementation

- **Data Lake Fundamentals on AWS:** Learn the core concepts of Data Lake architecture, including data layering (raw, processed, and analytics-ready data), and understand why Amazon S3 is the preferred storage solution for building a Data Lake.
- **Building a Data Lake with Your Own Data:** Practice uploading real-world datasets to Amazon S3, organizing data using prefixes, and managing the data lifecycle.

#### 2. Data Engineering

- **Data Engineering Immersion Day:** Gain hands-on experience with the complete data engineering workflow, including data ingestion, storage, processing, and analytics. Learn how AWS services work together in real-world data engineering projects.
- **Cost Data Analysis with AWS Glue and Amazon Athena:** Use AWS Glue Crawlers to automatically scan data stored in Amazon S3 and create metadata tables in the AWS Glue Data Catalog. Learn how to use AWS Glue ETL jobs to clean and transform data (for example, converting CSV files into Parquet format to improve query performance).

#### 3. Serverless Analytics

- **Serverless Analytics with Amazon Athena:** Practice writing standard SQL queries to analyze data stored directly in Amazon S3. Learn techniques such as data partitioning to improve query performance and reduce operational costs.

#### 4. Automation and Workflow Orchestration

- **Serverless Automation with AWS Lambda:** Learn how to develop Lambda functions that automatically trigger data processing workflows whenever new files are uploaded to the Data Lake.
- **Workflow Orchestration with AWS Step Functions:** Practice designing multi-step data processing workflows (for example: Step 1 – Validate data → Step 2 – Execute an AWS Glue Job → Step 3 – Send a notification) with built-in error handling and automated execution.

#### 5. Resource Organization and Management

- **Resource Organization with Tags and Resource Groups:** Learn how to organize AWS resources by assigning tags, making it easier to manage resources across different projects and research stages.

---

### Key Takeaways

- **Understanding the role of a Data Lake in data storage:** Amazon S3 is more than just a storage service—it serves as the foundation of a modern data analytics platform. It enables scalable and cost-effective storage for both raw and processed data, making future analytics and machine learning workflows more efficient.
- **Understanding the benefits of the serverless model:** AWS Glue and Amazon Athena enable data transformation and querying without the need to provision or manage servers, simplifying infrastructure management while reducing operational costs.
- **Recognizing the importance of ETL and data standardization:** Cleaning, transforming, and standardizing data are essential steps before performing data analysis or training machine learning models. Well-prepared data significantly improves model accuracy and overall analytical performance.
- **Understanding the role of automation in data processing:** AWS Lambda and AWS Step Functions help automate repetitive tasks, create consistent data processing workflows, and enable the system to automatically respond whenever new data is added to the Data Lake.

---

*Source: [First Cloud Journey - AWS Study Group](https://cloudjourney.awsstudygroup.com/)*
