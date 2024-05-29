+++
title = 'Overview'
date = 2024-05-29T12:49:43-07:00
draft = false
+++

Absolutely! Here are conceptual summaries for each of the listed AWS services, aiming for better understanding and retention:

**Orchestration and Integration:**

* **Amazon Managed Workflows for Apache Airflow (MWAA):** A service that handles the setup and management of Apache Airflow, a popular platform for creating, scheduling, and monitoring complex data processing workflows.
* **Amazon Simple Notification Service (SNS):** A messaging service that allows you to send notifications to a large number of subscribers through various channels like email, SMS, or mobile push notifications.
* **Amazon Simple Queue Service (SQS):** A message queue service that enables communication between distributed components of applications, ensuring reliability and scalability.
* **AWS Step Functions:** A serverless orchestration service that helps you visualize and manage the steps of your application's workflow, especially useful for coordinating Lambda functions and other AWS services.

**Cloud Financial Management:**

* **AWS Budgets:** A tool for setting alerts and tracking your AWS spending, helping you avoid unexpected costs and optimize resource usage.
* **AWS Cost Explorer:** A service that provides detailed reports and insights into your AWS costs, allowing you to identify trends, optimize spending, and forecast future costs.

**Compute:**

* **AWS Batch:** A service that allows you to run large-scale batch computing jobs efficiently, distributing them across the available compute resources.
* **Amazon EC2 (Elastic Compute Cloud):**  The foundation of AWS compute, providing virtual servers (instances) that you can customize with various configurations to meet your application needs.
* **AWS Lambda:** A serverless computing platform that runs your code in response to events without requiring you to provision or manage servers.
* **AWS Serverless Application Model (SAM):** A framework that simplifies building serverless applications on AWS, defining resources and permissions using a template.

**Containers:**

* **Amazon Elastic Container Registry (ECR):** A managed Docker container image registry that allows you to store, manage, and deploy containerized applications easily.
* **Amazon Elastic Container Service (ECS):** A highly scalable container orchestration service that helps you run and manage Docker containers on AWS.
* **Amazon Elastic Kubernetes Service (EKS):** A managed service that simplifies running Kubernetes, a popular open-source container orchestration system, on AWS infrastructure.

**Databases:**

* **Amazon DocumentDB:** A fully managed, highly scalable document database that is compatible with MongoDB applications and tools.
* **Amazon DynamoDB:** A fast and flexible NoSQL database that delivers single-digit millisecond performance at any scale, suitable for mobile, web, gaming, ad tech, IoT, and many other applications.
* **Amazon Keyspaces:** A scalable, highly available, and managed Apache Cassandra-compatible database for running applications that require low latency and high throughput at any scale.
* **Amazon MemoryDB for Redis:** A durable, in-memory database service that powers modern real-time applications with sub-millisecond latency.
* **Amazon Neptune:** A fast, reliable, fully managed graph database service that makes it easy to build and run applications that work with highly connected datasets.
* **Amazon RDS:** A managed relational database service that makes it easy to set up, operate, and scale relational databases in the cloud.
* **Amazon Redshift:** A fully managed, petabyte-scale data warehouse service in the cloud, designed for analyzing all your data using standard SQL and your existing Business Intelligence (BI) tools.

**Developer Tools:**

* **AWS Command Line Interface (CLI):** A unified tool to manage your AWS services through commands entered in a terminal or script. It provides direct access to the full range of AWS functionalities.
* **AWS Cloud9:** A cloud-based integrated development environment (IDE) that allows you to write, run, and debug code directly in your web browser. Ideal for collaborative projects and serverless development.
* **AWS Cloud Development Kit (CDK):** Enables you to define your cloud infrastructure as code using familiar programming languages (e.g., TypeScript, Python, Java). It streamlines infrastructure provisioning and management, promoting consistency and automation.
* **AWS CodeBuild:** A fully managed continuous integration service that compiles source code, runs tests, and produces ready-to-deploy software packages. It integrates with other AWS services and supports various build environments.
* **AWS CodeCommit:** A secure, highly scalable, managed source control service that hosts private Git repositories. It eliminates the need to operate your own source control system and scales seamlessly with your development needs.
* **AWS CodeDeploy:** Automates application deployments to various compute services (e.g., EC2, Lambda, ECS) or on-premises servers. It simplifies deployment processes and helps achieve continuous delivery.
* **AWS CodePipeline:** A fully managed continuous delivery service that helps you automate your release pipelines for fast and reliable application and infrastructure updates.

**Frontend Web and Mobile:**

* **Amazon API Gateway:** A fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale. It acts as a "front door" for applications to access data, business logic, or functionality from your back-end services.

**Machine Learning:**

* **Amazon SageMaker:** A fully managed service that provides every developer and data scientist with the ability to build, train, and deploy machine learning (ML) models quickly. It offers a broad set of tools and capabilities to support the entire ML workflow.

**Management and Governance:**

* **AWS CloudFormation:** Provides a common language for you to describe and provision all the infrastructure resources in your cloud environment. This infrastructure as code (IaC) tool allows for easy replication and management of stacks of resources.
* **AWS CloudTrail:** Records API activity within your AWS account, providing a history of AWS calls for auditing, security analysis, and troubleshooting.
* **Amazon CloudWatch:** Collects monitoring and operational data in the form of logs, metrics, and events, providing a unified view of AWS resources, applications, and services that run on AWS and on-premises servers.
* **Amazon CloudWatch Logs:** Monitors, stores, and accesses your log files from EC2 instances, AWS CloudTrail, and other sources. It helps you analyze logs, troubleshoot problems, and derive insights.
* **AWS Config:** Assesses, audits, and evaluates the configurations of your AWS resources, recording configuration changes and relationships between resources.
* **Amazon Managed Grafana:** A fully managed service for visualizing and analyzing metrics, logs, and traces. It provides a rich set of features for creating interactive dashboards and alerts.
* **AWS Systems Manager:** Helps you automatically collect software inventory, apply OS patches, create system images, and configure Windows and Linux operating systems. It provides a unified user interface so you can track and execute operational tasks across your AWS resources.
* **AWS Well-Architected Tool:** Reviews the state of your workloads and compares them against the latest AWS architectural best practices. It produces a plan to help you architect for the cloud and build secure, high-performing, resilient, and efficient infrastructure.

**Migration and Transfer:**

* **AWS Application Discovery Service:** Helps you plan migration projects by gathering configuration and usage data about your on-premises servers. 
* **AWS Application Migration Service:** Simplifies and expedites the migration of applications to AWS. It minimizes downtime and reduces operational overhead.
* **AWS Database Migration Service (DMS):** Helps migrate databases to and from AWS easily and securely. It supports homogeneous migrations (e.g., Oracle to Oracle) and heterogeneous migrations (e.g., Oracle to Amazon Aurora).
* **AWS DataSync:** Moves large amounts of data between on-premises storage and AWS or between AWS storage services. It automates, accelerates, and encrypts data transfer.

**Migration and Transfer:**

* **AWS Schema Conversion Tool (SCT):** Automates the conversion of schemas and code objects between different database platforms (e.g., Oracle to Amazon Aurora). It simplifies database migrations by handling complex conversions and minimizing downtime.
* **AWS Snow Family:** A collection of physical devices designed to securely move large amounts of data into and out of AWS. This is useful for scenarios where network transfer is not practical due to high data volumes or bandwidth constraints.
* **AWS Transfer Family:** Fully managed services that enable secure file transfers over standard protocols like SFTP, FTPS, and FTP. This is ideal for migrating existing file transfer workflows to the cloud.

**Networking and Content Delivery:**

* **Amazon CloudFront:** A fast content delivery network (CDN) service that securely delivers data, videos, applications, and APIs to customers globally with low latency and high transfer speeds.
* **AWS PrivateLink:** A service that provides private connectivity between VPCs, AWS services, and on-premises applications, keeping your network traffic within the AWS network and away from the public internet.
* **Amazon Route 53:** A highly available and scalable cloud Domain Name System (DNS) web service. It translates human-readable domain names (like `www.example.com`) into numeric IP addresses that computers use to connect to each other.
* **Amazon Virtual Private Cloud (VPC):**  Lets you provision a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define. You have complete control over your virtual networking environment, including IP address range, subnet creation, and route table and network gateway configuration.

**Security, Identity, and Compliance:**

* **AWS Identity and Access Management (IAM):** A web service that helps you securely control access to AWS resources. It lets you create and manage AWS users and groups, and use permissions to allow and deny their access to AWS resources.
* **AWS Key Management Service (KMS):** Makes it easy for you to create and manage cryptographic keys and control the use of encryption across a wide range of AWS services and in your applications. 
* **Amazon Macie:** A fully managed data security and data privacy service that uses machine learning and pattern matching to discover and protect your sensitive data in AWS.
* **AWS Secrets Manager:** Helps you protect secrets needed to access your applications, services, and IT resources. The service enables you to easily rotate, manage, and retrieve database credentials, API keys, and other secretsthroughout their lifecycle.
* **AWS Shield:** A managed Distributed Denial of Service (DDoS) protection service that safeguards web applications running on AWS.
* **AWS Web Application Firewall (WAF):** A web application firewall that helps protect your web applications or APIs against common web exploits that may affect availability, compromise security, or consume excessive resources.

**Storage:**

* **AWS Backup:** A fully managed service that makes it easy to centralize and automate data protection across AWS services and on-premises applications. It simplifies the creation of cost-efficient, application-consistent backups for faster recovery times.
* **Amazon Elastic Block Store (EBS):** Provides block storage volumes for use with EC2 instances. EBS volumes behave like raw, unformatted block devices. You can mount these volumes as devices on your instances.
* **Amazon Elastic File System (EFS):** A simple, serverless, set-and-forget, elastic file system that lets you share file storage with hundreds or thousands of EC2 instances or Lambda functions.
* **Amazon Simple Storage Service (S3):** Object storage built to store and retrieve any amount of data from anywhere. It offers a simple web services interface that you can use to store and retrieve any amount of data, at any time, from anywhere on the web.
* **Amazon S3 Glacier:** A secure, durable, and extremely low-cost storage service for data archiving and long-term backup. It is designed for data that is infrequently accessed and for which retrieval times of several hours are suitable.

