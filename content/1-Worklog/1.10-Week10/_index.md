---
title: "Week 10"
date: 2026-06-15
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

**Weekly Objectives**

- Complete the **Analytics & Visualization Layer** for the Customer Behavior Analytics system on AWS.
- Build a data querying environment using Amazon Athena integrated with AWS Glue Data Catalog.
- Develop a data visualization dashboard using Streamlit and integrate it with AWS services.
- Deploy the dashboard to Amazon EC2, test the entire system, and ensure it is accessible over the Internet.

---

**Tasks to be completed this week:**

| Day | Task | Date |
|---|---|---|
| Monday | Configure Amazon Athena and connect it to AWS Glue Data Catalog. Validate the Gold Layer data using SQL queries and evaluate query performance on Apache Parquet datasets. | 22/6 |
| Tuesday | Develop the dashboard using Streamlit, design the user interface to display KPI metrics and analytical charts, and integrate AWS Wrangler to query data directly from Amazon Athena. | 23/6 |
| Wednesday | Complete the dashboard features by creating analytical charts for revenue, orders, customers, countries, devices, payment methods, and traffic sources. | 24/6 |
| Thursday | Launch and configure an Amazon EC2 instance, set up the VPC, Public Subnet, Internet Gateway, Route Table, and Security Group. Install the Python environment, AWS CLI, and deploy the Streamlit application to Amazon EC2. | 25/6 |
| Friday | Test the complete data flow from the Gold Layer → Amazon Athena → Streamlit Dashboard, verify data accuracy, evaluate system performance, and finalize the deployment documentation. | 26/6 |

**What were the achievements this week?**

- **Monday:**
  - **Achievement:** Successfully configured Amazon Athena and connected it to AWS Glue Data Catalog. Data stored in the Gold Layer was accurately queried using SQL statements.
  - **Lesson Learned:** Amazon Athena enables direct querying of data stored in Amazon S3 without requiring a dedicated database management system, reducing costs and simplifying the analytics architecture.

- **Tuesday:**
  - **Achievement:** Successfully developed the Streamlit dashboard interface and integrated AWS Wrangler to retrieve data from Amazon Athena.
  - **Lesson Learned:** AWS Wrangler simplifies the integration between AWS services and Python, enabling efficient data retrieval for visualization and analytics.

- **Wednesday:**
  - **Achievement:** Completed the dashboard with comprehensive KPI metrics and analytical charts covering revenue, orders, customers, countries, devices, payment methods, and traffic sources.
  - **Lesson Learned:** A well-designed dashboard enables users to monitor business performance effectively and make informed, data-driven decisions.

- **Thursday:**
  - **Achievement:** Successfully deployed the Streamlit application on Amazon EC2, configured the Python environment and AWS CLI, and enabled public access to the dashboard through the EC2 Public IP address.
  - **Lesson Learned:** Deploying the application on Amazon EC2 makes it accessible over the Internet while providing a flexible environment for testing and operating a real-world analytics system.

- **Friday:**
  - **Achievement:** Successfully tested the complete data flow from the Gold Layer to the Streamlit Dashboard, verified data accuracy, and confirmed that the system operated reliably.
  - **Lesson Learned:** End-to-end testing of the Analytics & Visualization Layer ensures consistency between stored data, queried data, and visualized results, providing a reliable foundation for evaluating the overall system.

