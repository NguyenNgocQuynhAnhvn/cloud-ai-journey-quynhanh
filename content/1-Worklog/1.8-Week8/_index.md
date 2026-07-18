---
title: "Week 8"
date: 2026-06-08
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

**Weekly Objectives**

- Implement the **Ingestion Layer** for the Data Lakehouse system to collect data from multiple sources.
- Build two data ingestion mechanisms, **Batch Processing** and **Streaming Processing**, to support both scheduled and real-time data processing requirements.
- Set up and configure AWS services required for the data ingestion process.
- Verify that data is ingested accurately, completely, and successfully stored in the **Raw Layer** on Amazon S3.

---

**Tasks to be completed this week:**

| Day | Task | Date |
|---|---|---|
| Monday | Configure Amazon API Gateway to receive requests from external applications. Develop an AWS Lambda function to process incoming data and store it in Amazon S3. | 8/6 |
| Tuesday | Configure Amazon Kinesis Data Firehose to receive streaming data and automatically deliver it to the Raw Layer on Amazon S3. Test the Streaming Processing pipeline. | 9/6 |
| Wednesday | Configure Amazon EventBridge Scheduler to automatically trigger scheduled data synchronization. Develop an AWS Lambda function for the Batch Processing pipeline to synchronize data from the database to Amazon S3. | 10/6 |
| Thursday | Integrate all components of the Ingestion Layer, test both the Batch Processing and Streaming Processing pipelines, and verify that data is stored in the correct folder structure within the Raw Layer on Amazon S3. | 11/6 |
| Friday | Monitor system activity using Amazon CloudWatch Logs, analyze log files, resolve issues, evaluate data ingestion performance, and complete the Ingestion Layer deployment documentation. | 12/6 |

**What were the achievements this week?**

- **Monday:**
  - **Achievement:** Successfully configured Amazon API Gateway and deployed an AWS Lambda function to receive data from APIs and store it in Amazon S3.
  - **Lesson Learned:** Combining API Gateway with AWS Lambda enables the development of flexible, scalable serverless APIs while significantly reducing operational costs compared to traditional server-based architectures.

- **Tuesday:**
  - **Achievement:** Successfully configured Amazon Kinesis Data Firehose, enabling streaming data to be automatically delivered to the Raw Layer on Amazon S3 as designed.
  - **Lesson Learned:** Amazon Kinesis Data Firehose simplifies real-time data ingestion by continuously delivering streaming data without requiring a custom ingestion mechanism.

- **Wednesday:**
  - **Achievement:** Successfully implemented the Batch Processing pipeline using Amazon EventBridge Scheduler and AWS Lambda to automatically synchronize data from the database to Amazon S3 on a scheduled basis.
  - **Lesson Learned:** Automating the Batch Processing workflow reduces manual effort and ensures that data is synchronized accurately and on schedule.

- **Thursday:**
  - **Achievement:** Successfully integrated both the Batch Processing and Streaming Processing pipelines and verified that data was stored in the correct directory structure within the Raw Layer on Amazon S3.
  - **Lesson Learned:** End-to-end pipeline testing helps identify integration issues between AWS services early, ensuring a stable foundation before implementing downstream data processing stages.

- **Friday:**
  - **Achievement:** Monitored and analyzed system logs using Amazon CloudWatch Logs, resolved operational issues, evaluated data ingestion performance, and completed the Ingestion Layer deployment documentation.
  - **Lesson Learned:** Amazon CloudWatch Logs is an essential monitoring tool for serverless systems, enabling rapid troubleshooting, performance optimization, and improved reliability across the entire data pipeline.
