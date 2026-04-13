# AWS Full DevOps Pipeline Project

## Project Overview

This project demonstrates an end-to-end DevOps pipeline using Terraform, Docker, Kubernetes, and AWS.

The architecture includes:
- CI/CD pipeline using Jenkins
- Docker containerization
- Amazon ECR for image storage
- Terraform for infrastructure automation
- Amazon EKS for container orchestration
- ALB for traffic routing
- CloudFront and Route 53 for global access
- Monitoring using CloudWatch, SNS, Prometheus, and Grafana

---

## Architecture Diagram

![Architecture Diagram](architecture-diagram.png)

---


## Project Flow

1. Developer pushes code to GitHub
2. CI/CD pipeline builds Docker image
3. Image is pushed to ECR
4. Terraform provisions AWS infrastructure
5. EKS deploys containers
6. ALB routes traffic
7. CloudFront delivers content globally
8. Monitoring tools track performance

---

## Folder Structure
aws-full-devops-pipeline/
│
├── README.md
├── architecture-diagram.png
├── terraform/
│   ├── main.tf
│   ├── variables.tf
│   └── modules/
├── docker/
│   └── Dockerfile
├── k8s/
│   ├── deployment.yaml
│   ├── service.yaml
│   └── ingress.yaml
├── cicd/
│   └── Jenkinsfile
├── app/
│   └── app.py
├── monitoring/
│   ├── prometheus.yaml
│   └── grafana.md
├── screenshots/
├── deployment-steps.md
├── interview-questions.md
└── resume-points.md

## Features

- End-to-End DevOps Pipeline
- Infrastructure as Code
- Containerized Deployment
- Kubernetes Orchestration
- Monitoring and Alerts

---

## Resume Points

- Built full DevOps pipeline using Terraform, Docker, and Kubernetes
- Automated infrastructure provisioning using Terraform
- Deployed microservices on AWS EKS
- Implemented CI/CD using Jenkins
- Integrated monitoring and alerting systems

---

## Interview Questions

1. Explain end-to-end DevOps pipeline
2. What is Terraform role?
3. How Docker and Kubernetes work together?
4. What is EKS?
5. How CI/CD pipeline works?
