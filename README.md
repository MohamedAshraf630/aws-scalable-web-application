# 🚀 Scalable Web Application on AWS

A production-style AWS infrastructure project demonstrating a highly available and scalable web application using Amazon EC2 Auto Scaling, Application Load Balancer (ALB), Amazon CloudFront, AWS WAF, Amazon Route 53, Amazon RDS, Amazon CloudWatch, and AWS Systems Manager.


## 📖 Project Overview

This project simulates a production-ready web application hosted on AWS following cloud architecture best practices. The infrastructure is designed for scalability, security, and high availability by distributing traffic through an Application Load Balancer, automatically scaling EC2 instances based on demand, and accelerating content delivery using Amazon CloudFront.

To improve security, AWS WAF protects the application from common web vulnerabilities, while Amazon CloudWatch and Amazon SNS provide monitoring and alerting. AWS Systems Manager Session Manager enables secure instance management without requiring SSH access.

---

## 🏗️ Architecture

<img width="1536" height="1024" alt="architecture-diagram" src="https://github.com/user-attachments/assets/b6471594-f4e4-40f6-b57c-221860cea1dd" />

---

## ✨ Key Features

* Multi-Availability Zone VPC architecture
* Public and private subnet design
* Internet Gateway and NAT Gateway
* Application Load Balancer with health checks
* EC2 Auto Scaling Group using Target Tracking
* AWS WAF with managed security rules
* Amazon CloudFront for content delivery
* Amazon Route 53 Alias Record and Health Check
* Amazon RDS MySQL database (Single-AZ)
* CloudWatch Dashboard, Alarms, and SNS notifications
* Secure EC2 access through AWS Systems Manager Session Manager

---

## ☁️ AWS Services Used

* Amazon VPC
* Amazon EC2
* Launch Template
* Auto Scaling Group
* Application Load Balancer (ALB)
* AWS WAF
* Amazon CloudFront
* Amazon Route 53
* Amazon RDS (MySQL)
* Amazon CloudWatch
* Amazon SNS
* AWS Systems Manager
  

## ✅ Project Validation

The deployment was tested by:

* Verifying CloudFront successfully serves the application
* Confirming healthy targets behind the Application Load Balancer
* Testing Auto Scaling functionality
* Connecting Amazon EC2 to Amazon RDS using the MariaDB client
* Monitoring infrastructure with CloudWatch dashboards and alarms
* Receiving SNS email notifications
* Accessing EC2 instances securely through Systems Manager Session Manager

---

## 📸 Project Screenshots

### Application Load Balancer

<img width="3195" height="1218" alt="07-ALB" src="https://github.com/user-attachments/assets/5e38d148-7eac-469b-84a2-3aa283e8c218" />


### Auto Scaling Group

<img width="3150" height="555" alt="04-ASG" src="https://github.com/user-attachments/assets/78d9d1af-e0cb-4f2b-897c-e5b081944945" />


### CloudFront Distribution

<img width="3078" height="234" alt="08-cloudfront(CDN)" src="https://github.com/user-attachments/assets/98f70a97-8b16-42cc-a73c-0d4119ea53a1" />


### CloudWatch Dashboard

<img width="3801" height="687" alt="13-Cloudwatch-dashboard" src="https://github.com/user-attachments/assets/cd114343-a29a-4dca-b6ea-99f0cb907d28" />
