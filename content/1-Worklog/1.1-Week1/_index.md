---
title: "Week 1"
date: 2026-04-20
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---


**Weekly Objectives**

- Build a secure foundation: Become familiar with the AWS Cloud environment, create an AWS account, and configure basic security and access control.
- Manage costs effectively: Learn how to monitor and control cloud spending to avoid unexpected charges while working with big data workloads.
- Understand core infrastructure: Gain an understanding of virtual servers (EC2), virtual networking (VPC), and object storage (S3).
- Master essential tools: Learn to use the AWS Command Line Interface (CLI) and AWS Cloud9 development environment instead of relying solely on the AWS Management Console.

---

**Tasks to Be Completed This Week**

| Day | Tasks | Date |
|---|---|---|
| **Monday (Office)** | Create a new AWS account, complete billing setup, and activate the initial **USD 100 AWS credit**. Launch and test an Amazon EC2 instance using a self-generated key pair, experiment with the **Claude 3 Haiku Playground** in Amazon Bedrock, configure cost alerts with AWS Budgets, create a basic AWS Lambda function, and provision an Amazon RDS PostgreSQL database. | Apr 20 |
| **Tuesday** | Study and practice AWS Identity and Access Management (IAM) by creating Users, Groups, and Policies, and assigning permissions based on the **Principle of Least Privilege**. Learn about IAM Roles and Instance Profiles, and configure an EC2 instance to securely access Amazon S3 without using Access Keys. | Apr 21 |
| **Wednesday (Office)** | Design and deploy a virtual network using Amazon VPC. Configure core networking components, including Subnets, Internet Gateway, and Route Tables, to build an isolated cloud network. Explore and configure EC2 Auto Scaling to automatically adjust the number of EC2 instances according to workload demands, ensuring high availability for data processing systems. | Apr 22 |
| **Thursday** | Practice data storage and static website hosting with Amazon S3. Learn how to manage S3 Buckets, object access policies, and storage classes. Set up a cloud-based development environment with AWS Cloud9 and use the AWS CLI to automate AWS resource management tasks. | Apr 23 |
| **Friday** | Implement centralized monitoring using Amazon CloudWatch. Build CloudWatch Dashboards to monitor system performance and configure CloudWatch Alarms with email notifications. Explore AWS Support plans and support request procedures, and review the weekly AWS Budgets report to analyze actual cloud spending. | Apr 24 |

**Weekly Results**

- **Monday (Office):**
  - **Achievement:** Successfully activated an AWS account with a total of **USD 200 in promotional credits**. All five test resources were successfully provisioned and safely terminated after the exercises.
  - **Lesson Learned:** Became familiar with the AWS Management Console and developed the habit of cleaning up cloud resources immediately after completing hands-on exercises to prevent unnecessary costs.

- **Tuesday:**
  - **Achievement:** Successfully configured AWS IAM by creating Users, Groups, Policies, IAM Roles, and Instance Profiles. Enabled secure access from an EC2 instance to Amazon S3 without using Access Keys.
  - **Lesson Learned:** IAM is a fundamental component of cloud security. Applying the Principle of Least Privilege significantly reduces security risks while making access management more efficient.

- **Wednesday (Office):**
  - **Achievement:** Successfully deployed a secure and isolated virtual network using Amazon VPC and gained hands-on experience configuring Subnets, Internet Gateway, Route Tables, and EC2 Auto Scaling.
  - **Lesson Learned:** Amazon VPC provides the first layer of security for cloud infrastructure. Incorrect Subnet or Route Table configurations can lead to connectivity issues or unintended data exposure.

- **Thursday:**
  - **Achievement:** Successfully stored and managed files in Amazon S3, established a cloud-based development environment using AWS Cloud9, and learned the fundamental AWS CLI commands for managing cloud resources.
  - **Lesson Learned:** Amazon S3 is much more than cloud storage—it is a highly scalable and durable storage platform. Mastering the AWS CLI is essential for automating cloud workflows and building future data pipelines.

- **Friday:**
  - **Achievement:** Successfully implemented automated infrastructure monitoring with Amazon CloudWatch, including email-based alert notifications. Completed the deployment of a secure cloud foundation and reviewed the week's cloud spending using AWS Budgets.
  - **Lesson Learned:** Continuous monitoring is essential for maintaining a reliable cloud environment. Performance dashboards and automated alerts enable potential issues to be detected and resolved before they affect system operations.