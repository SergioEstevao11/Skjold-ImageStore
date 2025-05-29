# Secure Serverless Image Upload App 🚀

A full-stack, AWS-native, serverless image upload and management platform built with **React**, **API Gateway**, **Lambda**, **S3**, **DynamoDB**, and provisioned entirely using **Terraform**. 
This project emphasizes **security**, **cloud architecture best practices**, and is my "sandbox" to practice and showcase my cloud expertize.

---

## 🧱 Architecture Overview

- **Frontend**: React app hosted in S3 and served via CloudFront
- **Backend**: API Gateway → Lambda → DynamoDB/S3
- **Security**: IAM (least privilege), WAF, KMS, VPC, SSM, S3 signed URLs
- **Monitoring**: CloudWatch, GuardDuty, AWS Config
- **CI/CD**: GitHub Actions for Terraform and frontend deploys

---

## 🚀 Features

- Upload and retrieve images securely
- Time-limited access via signed URLs
- Modular infrastructure using Terraform
- Highly secure and compliant design
- Fully documented and CI/CD-enabled

---

## 🔧 Deployment Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/secure-image-app.git
   cd secure-image-app
