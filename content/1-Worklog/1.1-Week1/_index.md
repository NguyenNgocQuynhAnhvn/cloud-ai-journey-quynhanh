---
title: "Week 1"
date: 2026-04-20
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---

> **Duration:** 20/04/2026 - 26/04/2026 Cloud Fundamentals and Secure Environment Setup

---

### Weekly Objectives

- Build a secure foundation: Become familiar with the AWS Cloud environment, create an AWS account, and configure basic security and access control.
- Manage costs effectively: Learn how to monitor and control cloud spending to avoid unexpected charges while working with big data workloads.
- Understand core infrastructure: Gain an understanding of virtual servers (EC2), virtual networking (VPC), and object storage (S3).
- Master essential tools: Learn to use the AWS Command Line Interface (CLI) and AWS Cloud9 development environment instead of relying solely on the AWS Management Console.

---

### Learning Contents

#### 1. Account and Cost Management

- **Creating Your First AWS Account:** Register an AWS account, configure billing information, and apply initial security best practices.
- **Managing Costs with AWS Budgets:** Create an AWS Budget and configure spending alerts (for example, when costs reach $5 or $10) to receive email notifications, helping monitor expenses while working with large datasets.
- **Getting Help with AWS Support:** Learn how to create a Support Ticket to receive assistance from the AWS technical support team when encountering system issues or service-related questions.

#### 2. Security and Access Management (IAM)

- **Access Management with IAM:** Practice creating Users, Groups, and assigning IAM Policies. Learn how to grant read-only or full-access permissions to AWS resources.
- **Instance Profiling with IAM Roles for EC2:** Learn an advanced security practice by attaching an IAM Role to an EC2 instance instead of storing Access Keys on the server. This allows the instance to securely access other AWS services such as Amazon S3 without exposing credentials.

#### 3. Networking and Compute Infrastructure (VPC & EC2)

- **Networking Essentials with Amazon VPC:** Learn how to configure a private virtual network, including Subnets, Route Tables, and an Internet Gateway to control internet access to servers hosting data.
- **Compute Essentials with Amazon EC2:** Launch a virtual server (EC2 Instance), select an appropriate instance type, choose an Amazon Machine Image (AMI), and configure a Key Pair for secure remote access.
- **Scaling Applications with EC2 Auto Scaling:** Explore how Auto Scaling automatically increases or decreases the number of EC2 instances based on traffic or computational demand, ensuring system stability during intensive data processing tasks.

#### 4. Storage and Development Tools

- **Static Website Hosting with Amazon S3:** Learn how to create an S3 Bucket, upload files, and manage access permissions by hosting a static website on Amazon S3.
- **Cloud Development with AWS Cloud9:** Set up a browser-based integrated development environment (IDE) to write Python code and run data analysis scripts without installing software on a local computer.
- **Command Line Operations with AWS CLI:** Install and practice using the AWS Command Line Interface (CLI) to interact with and manage AWS services.

#### 5. System Monitoring

- **Monitoring with Amazon CloudWatch:** Learn how to monitor CPU utilization, network traffic, and configure CloudWatch Alarms to notify you when EC2 instances become overloaded during model training or data processing.

---

### Key Takeaways

- **Understanding the importance of access control:** Avoid using the Root account for daily operations. Instead, use IAM Users with appropriately assigned permissions to improve security and minimize operational risks.
- **The importance of cost management:** Setting up AWS Budgets helps proactively monitor cloud spending, maintain cost control, and prevent unexpected charges while using AWS services.
- **The flexibility of cloud computing:** Instead of upgrading a personal computer, you can launch a powerful Amazon EC2 instance within minutes to process massive datasets and shut it down afterward to reduce costs.
- **The role of Amazon S3 in data storage:** Amazon S3 is more than just a storage service—it provides high durability, excellent scalability, and seamless integration with many other AWS services. This makes storing, managing, and accessing data much more efficient than relying on traditional local storage.

---

*Source: [First Cloud Journey - AWS Study Group](https://cloudjourney.awsstudygroup.com/)*