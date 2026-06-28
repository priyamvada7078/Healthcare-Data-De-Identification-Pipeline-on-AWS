# 🏥 Healthcare Data Compliance & Analytics Platform

A secure, event-driven healthcare data engineering pipeline built on AWS that automates validation, de-identification, ETL processing, and analytics for sensitive healthcare records. The project demonstrates scalable cloud architecture, serverless computing, and secure data processing using AWS services.

---

## 📌 Project Overview

Healthcare organizations generate large volumes of patient data containing Personally Identifiable Information (PII). Before this data can be used for analytics, it must be validated, cleaned, and de-identified to ensure privacy compliance.

This project implements an automated AWS-based pipeline that:

- Validates incoming healthcare records
- Detects and quarantines invalid data
- De-identifies sensitive patient information
- Performs ETL using Apache Spark on AWS Glue
- Stores processed datasets securely
- Enables SQL-based analytics using Amazon Athena

---

## 🚀 Features

- Automated data validation using AWS Lambda
- Event-driven architecture with Amazon S3
- Invalid record quarantine mechanism
- HIPAA-inspired data de-identification
- ETL processing using AWS Glue and Apache Spark
- Secure cloud storage on Amazon S3
- SQL analytics with Amazon Athena
- Monitoring using Amazon CloudWatch
- Audit logging with AWS CloudTrail
- Email notifications using Amazon SNS
- IAM-based access control

---

## 🏗️ Workflow

```
Healthcare Records
        │
        ▼
Amazon S3 (Raw Bucket)
        │
        ▼
AWS Lambda Validation
        │
 ┌──────┴────────┐
 │               │
 ▼               ▼
Clean Data   Invalid Data
    │         (Quarantine)
    ▼
AWS Glue ETL
    │
    ▼
Data De-identification
    │
    ▼
Amazon S3 (Curated Bucket)
    │
    ▼
Amazon Athena
    │
    ▼
Analytics & Reporting
```

---

## ☁️ AWS Services Used

- Amazon S3
- AWS Lambda
- AWS Glue
- Apache Spark
- Amazon Athena
- AWS IAM
- Amazon CloudWatch
- AWS CloudTrail
- Amazon SNS

---

## 🛠️ Tech Stack

- AWS Cloud
- Python
- Apache Spark
- SQL
- AWS Glue
- AWS Lambda

---

## 📂 Project Highlights

- Designed a scalable serverless data engineering pipeline.
- Implemented automated validation to improve data quality.
- Applied de-identification techniques such as masking and hashing to protect sensitive healthcare information.
- Built an analytics-ready data lake using AWS services.
- Integrated monitoring, auditing, and notification mechanisms for improved reliability and security.

---

## 📷 Screenshots

Screenshots of the architecture, AWS services, and analytics dashboard will be added soon.

---

## 📖 Future Enhancements

- Infrastructure as Code (Terraform)
- CI/CD using GitHub Actions
- Real-time data ingestion
- Interactive dashboards
- Data quality reporting

---

## ⚠️ Note

This project was deployed and tested on AWS. Cloud resources have been decommissioned to avoid unnecessary costs. The repository contains the complete source code and project implementation.

---

## 👩‍💻 Author

**Priyamvada Chaudhary**

B.Tech Information Technology
