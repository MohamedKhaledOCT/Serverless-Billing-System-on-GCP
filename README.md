# Pet Theory - Serverless Billing System 🐾

![Google Cloud Run](https://img.shields.io/badge/Google_Cloud-Run-blue?logo=google-cloud)
![Serverless](https://img.shields.io/badge/Architecture-Serverless-orange)
![Microservices](https://img.shields.io/badge/Pattern-Microservices-green)

A complete migration from monolithic to serverless architecture for a veterinary billing system using Google Cloud Platform.

## 📌 Project Overview

This project demonstrates:
- **Monolith-to-microservices** transformation
- **Serverless implementation** using Cloud Run
- **CI/CD pipeline** with Cloud Build
- **Secure service communication** with IAM

## 🛠️ Technical Stack

| Component          | Technology Used              |
|--------------------|------------------------------|
| Compute Platform   | Google Cloud Run             |
| Containerization  | Docker                       |
| CI/CD             | Cloud Build                  |
| Security          | IAM, Service Accounts        |
| Infrastructure    | GCP CLI (gcloud)             |

## 🚀 Deployment Steps

### 1. Setup Environment
```bash
gcloud config set project $(gcloud projects list --format='value(PROJECT_ID)' --filter='qwiklabs-gcp')
gcloud config set run/region us-east4
gcloud config set run/platform managed
