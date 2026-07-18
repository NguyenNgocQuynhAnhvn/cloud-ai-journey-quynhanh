---
title: "Week 3"
date: 2026-05-03
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---


**Weekly Objectives**

- Understand and build a Data Lake: Learn the core concepts and implementation of a Data Lake using Amazon S3.
- Master the ETL process: Learn how to Extract, Transform, and Load (ETL) data using AWS services.
- Automate data processing: Build serverless data pipelines using AWS managed services.
- Optimize data organization: Organize data efficiently to improve query performance and support analytics in subsequent stages.

---

**Tasks to Be Completed This Week**

| Day | Tasks | Date |
|---|---|---|
| **Monday** | Study the core concepts of Data Lake architecture, focusing on the central role of Amazon S3 in storing both raw and processed data. Practice designing a layered storage structure and explore Lifecycle Policies to optimize storage costs for large datasets. | May 4 |
| **Tuesday (Office)** | Practice ingesting real-world datasets into the cloud. Learn how to organize data using partitioning techniques to improve query performance and implement fine-grained access control for different data partitions. | May 5 |
| **Wednesday (Office)** | Study the complete data lifecycle, including data ingestion, storage, and transformation. Learn how AWS services work together to build clean and reliable data pipelines for Machine Learning applications. | May 6 |
| **Thursday** | Study and practice building an automated data catalog using AWS Glue Crawlers and perform data format transformations to improve query performance. Use Amazon Athena to execute SQL queries directly against data stored in Amazon S3 without managing server infrastructure. | May 7 |
| **Friday** | Study and implement automated data processing using AWS Lambda. Use AWS Step Functions to orchestrate multi-step workflows with built-in error handling and recovery mechanisms. | May 8 |

**Weekly Results**

- **Monday:**
  - **Achievement:** Gained a solid understanding of layered Data Lake architecture and successfully configured automated storage lifecycle policies in Amazon S3.
  - **Lesson Learned:** A Data Lake is more than just a file repository—it is a structured data management platform that keeps data organized and readily available for various analytics workloads without requiring immediate schema definition.

- **Tuesday (Office):**
  - **Achievement:** Successfully built a secure and high-performance Data Lake by configuring Amazon S3 buckets with appropriate security settings and optimized data organization.
  - **Lesson Learned:** Data partitioning (for example, by year, month, and day) is essential for reducing query costs and significantly improving query performance when working with Big Data.

- **Wednesday (Office):**
  - **Achievement:** Completed a basic ETL (Extract, Transform, Load) workflow and gained a clear understanding of how data flows through different AWS services.
  - **Lesson Learned:** Clean, well-structured data is the foundation for building accurate and reliable AI and Machine Learning models.

- **Thursday:**
  - **Achievement:** Successfully automated schema discovery using AWS Glue Crawlers and executed complex SQL queries on raw datasets efficiently using Amazon Athena.
  - **Lesson Learned:** Serverless services such as AWS Glue and Amazon Athena allow data engineers to focus on data processing and analytics without the operational burden of managing infrastructure.

- **Friday:**
  - **Achievement:** Successfully built a fully automated event-driven data processing system and implemented a workflow orchestration process capable of monitoring the status of each processing stage.
  - **Lesson Learned:** Workflow automation and orchestration enable data pipelines to operate reliably around the clock, minimize human errors, and improve the overall professionalism and scalability of data engineering projects.