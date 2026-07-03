**Brain Tasks App - End-to-End DevOps Deployment on AWS EKS**

**Project Overview**

This project demonstrates an end-to-end DevOps implementation for the Brain Tasks App using AWS services and Kubernetes.

**The project covers:**

•	Dockerizing the application
•	Storing Docker images in AWS ECR
•	Provisioning Kubernetes cluster using Amazon EKS
•	Deploying the application to Kubernetes
•	Building CI/CD pipeline using AWS CodeBuild and CodePipeline
•	Monitoring build and deployment logs using CloudWatch

**Project Architecture**

GitHub Repository
        │
        ▼
AWS CodePipeline
        │
        ▼
AWS CodeBuild
        │
        ▼
Docker Build
        │
        ▼
AWS ECR
        │
        ▼
Amazon EKS Cluster
        │
        ▼
Kubernetes Deployment
        │
        ▼
LoadBalancer Service
        │
        ▼
Browser (Port 3000)
________________________________________
**Repository Structure**

Brain-Tasks-App/
│
├── src/
├── public/
├── package.json
├── Dockerfile
├── buildspec.yml
├── deployment.yaml
├── service.yaml
├── README.md
└── screenshots/
________________________________________
**Technologies Used**

•	AWS EKS
•	AWS ECR
•	AWS CodeBuild
•	AWS CodePipeline
•	AWS CloudWatch
•	Docker
•	Kubernetes
•	GitHub
•	Node.js
•	kubectl
•	AWS CLI
________________________________________
**Prerequisites**

Before starting, install:

•	Git
•	Docker
•	Node.js
•	AWS CLI
•	kubectl
•	eksctl
Configure AWS credentials:
AWS Configure
