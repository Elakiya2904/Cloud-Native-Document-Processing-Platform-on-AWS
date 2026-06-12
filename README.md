# Cloud-Native Document Processing Platform on AWS

## Overview

A cloud-native, event-driven document processing platform built on AWS that enables secure document uploads, automated processing, metadata extraction, and result retrieval through scalable APIs.

The platform leverages AWS serverless and containerized services to provide high availability, scalability, security, and automation.

## Features

- Secure document upload
- Event-driven processing
- Metadata extraction
- PostgreSQL storage
- Containerized API services
- Infrastructure as Code (Terraform)
- Monitoring and logging
- Highly scalable architecture

## Architecture Components

- Amazon S3
- AWS Lambda
- Amazon ECS
- Amazon RDS PostgreSQL
- Amazon EC2 Bastion Host
- Amazon VPC
- AWS IAM
- Amazon Route 53
- Amazon CloudWatch
- NAT Gateway
- Terraform

## Workflow

1. User uploads document
2. Document stored in S3
3. S3 triggers Lambda
4. Lambda processes document
5. Results stored in RDS
6. ECS API serves processed results
7. CloudWatch monitors the system
<img width="731" height="627" alt="image" src="https://github.com/user-attachments/assets/60513815-c793-4122-a5f5-7c2584840e76" />


## Technology Stack

Backend:
- Python
- AWS Lambda
- Amazon ECS

Database:
- PostgreSQL (Amazon RDS)

Infrastructure:
- Terraform

Cloud Platform:
- AWS

Monitoring:
- Amazon CloudWatch
