# AWS CDK with Python - S3 and Lambda Integration

Automate your AWS infrastructure with AWS Cloud Development Kit (CDK) using Python. This project provisions an S3 bucket with versioning enabled and a Lambda function triggered by S3 object creation events. All IAM roles are managed securely by CDK.

---

## Features

- Infrastructure as code with AWS CDK and Python
- S3 bucket with versioning and automatic lifecycle policies
- Event-driven Lambda function triggered on new S3 objects
- Automated IAM role and permission management
- Easy deployment and updates using CDK CLI

---

## Architecture Overview

The stack provisions an S3 bucket configured to send notifications to a Lambda function whenever objects are created. The Lambda function contains simple Python code to log event details. CDK generates and manages IAM roles, enforcing least privilege principles.

- AWS S3 bucket with event notifications
- Python-based Lambda function triggered by bucket events
- IAM roles and policies provisioned by CDK
- Deployment and updates via AWS CDK CLI tools

---

## Setup Instructions

1. **Install prerequisites:**
   ```
   npm install -g aws-cdk
   pip install -r requirements.txt
   ```
2. **Bootstrap your AWS environment:**
   ```
   cdk bootstrap
   ```
3. **Deploy the stack:**
   ```
   cdk deploy
   ```
4. **Test your setup:**
   Upload a file to the created S3 bucket and monitor Lambda executions in CloudWatch Logs.

---

> Connect with me on GitHub and LinkedIn

<p align="center">
  <a href="https://github.com/ShaikhAteeb02">
    <img src="https://img.shields.io/badge/GitHub-Profile-informational?style=for-the-badge&logo=github&logoColor=white&color=181717" alt="GitHub Profile" />
  </a>
  <a href="https://www.linkedin.com/in/ateeb-ahmed-shaikh-932234192/">
    <img src="https://img.shields.io/badge/LinkedIn-Profile-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Profile" />
  </a>
</p>
