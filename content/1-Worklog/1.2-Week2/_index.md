---
title: "Week 2"
date: 2026-04-27
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---


**Weekly Objectives**

- Master different data storage models: Learn the differences between relational (SQL) and non-relational (NoSQL) databases and apply them to various analytics scenarios.
- Learn data migration techniques: Transfer data from on-premises environments or between different systems into AWS Cloud for further processing.
- Optimize database queries: Develop advanced SQL skills to improve data retrieval efficiency.

---

**Tasks to Be Completed This Week**

| Day | Tasks | Date |
|---|---|---|
| **Monday** | Study and practice provisioning a relational database using Amazon Relational Database Service (RDS). Explore managed features such as automated backups, version upgrades, and Multi-AZ deployments for high availability. Configure Security Groups to control database access and test connectivity from an Amazon EC2 instance or local workstation in preparation for future data analytics exercises. | Apr 27 |
| **Tuesday** | Continue practicing Amazon RDS by deploying and managing relational databases such as MySQL and PostgreSQL on AWS. Complete the Advanced PostgreSQL on AWS (Part 1 & 2) modules to learn advanced query optimization techniques and efficient processing of complex datasets for data preprocessing tasks. | Apr 28 |
| **Wednesday** | Learn and practice NoSQL database concepts through NoSQL Database Essentials with Amazon DynamoDB. Create schema-less tables with high scalability and complete the Building Advanced Applications with Amazon DynamoDB lab to design optimized data models for Big Data applications requiring ultra-low latency. | Apr 29 |
| **Thursday** | Practice database migration using AWS Database Migration Service (DMS) together with the Schema Conversion Tool (SCT). Learn how to automatically convert database schemas and establish secure, continuous data synchronization from external environments to AWS. | Apr 30 |
| **Friday** | Implement an in-memory caching solution using Amazon ElastiCache to improve data access performance. Explore AWS Storage Gateway to establish seamless hybrid storage connectivity between on-premises infrastructure and AWS cloud storage services. | May 1 |

**Weekly Results**

- **Monday:**
  - **Achievement:** Successfully deployed a fully managed MySQL/PostgreSQL database instance on AWS. Established secure connectivity and became familiar with the Amazon RDS management console.
  - **Lesson Learned:** Using a managed database service such as Amazon RDS significantly reduces infrastructure management overhead compared with manually deploying databases on Amazon EC2.

- **Tuesday:**
  - **Achievement:** Successfully provisioned an Amazon RDS PostgreSQL instance and executed complex SQL queries with improved performance through query optimization techniques.
  - **Lesson Learned:** Advanced SQL enables data cleaning and preprocessing directly within the database, reducing the need for additional processing in Python or R.

- **Wednesday:**
  - **Achievement:** Successfully created an Amazon DynamoDB table and performed high-speed Key-Value data retrieval operations.
  - **Lesson Learned:** NoSQL databases are well suited for storing unstructured data and processing large-scale workloads with high read/write throughput that traditional relational databases may struggle to achieve.

- **Thursday:**
  - **Achievement:** Successfully simulated the migration of an existing database to AWS Cloud with minimal downtime.
  - **Lesson Learned:** AWS Schema Conversion Tool (SCT) and AWS Database Migration Service (DMS) help automate database migration, reducing manual effort, minimizing errors, and accelerating the migration process.

- **Friday:**
  - **Achievement:** Successfully integrated an in-memory caching layer to reduce the workload on the primary database and configured AWS Storage Gateway to synchronize on-premises data automatically with Amazon S3.
  - **Lesson Learned:** Optimizing data access performance through caching enables faster response times for real-time analytics while hybrid storage solutions simplify data synchronization between on-premises and cloud environments.