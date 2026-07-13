---
title: "Week 8"
date: 2026-06-08
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

> **Duration:** 08/06/2026 - 14/06/2026 Implementing the Ingestion Layer for the Data Lakehouse

---

### Weekly Objectives

- Implement the Ingestion Layer for the Data Lakehouse to collect data from multiple data sources.
- Build two data ingestion mechanisms—Batch Processing and Streaming Processing—to support both scheduled and real-time data processing requirements.
- Configure and deploy the AWS services required for the data ingestion pipeline.
- Verify that incoming data is successfully ingested, validated, and stored in the Raw Layer on Amazon S3.

---

### Work Activities

- Configure **Amazon API Gateway** to receive requests and data from external applications.
- Develop **AWS Lambda** functions to process incoming data from API Gateway and store it in the data storage layer.
- Configure **Amazon Kinesis Data Firehose** to ingest streaming data and automatically deliver it to **Amazon S3**.
- Set up **Amazon EventBridge Scheduler** to automatically trigger scheduled data synchronization workflows.
- Develop an **AWS Lambda** function for the Batch Processing pipeline to synchronize data from the source database to Amazon S3.
- Test the complete data ingestion workflow for both the Batch Processing and Streaming Processing pipelines, and evaluate system reliability and stability.
- Verify that data is stored in the correct directory structure within the Raw Layer of Amazon S3.
- Monitor and analyze system logs using **Amazon CloudWatch Logs** to detect errors, troubleshoot issues, and evaluate the performance of the data ingestion process.

---

### Achievements

- Successfully implemented the Ingestion Layer for the Data Lakehouse architecture.
- Successfully built two data ingestion pipelines based on the Batch Processing and Streaming Processing models.
- Successfully configured and integrated **Amazon API Gateway**, **AWS Lambda**, **Amazon Kinesis Data Firehose**, **Amazon EventBridge Scheduler**, and **Amazon S3** into the data ingestion workflow.
- Incoming data was automatically ingested and successfully stored in the Raw Layer of Amazon S3 according to the designed architecture.
- Successfully completed end-to-end testing of the data ingestion pipelines, confirming that the system operates reliably and is ready for the next phase of ETL development and data processing within the subsequent layers of the Data Lakehouse.