# 🚀 Project introduction

In this project, we will walkthrough the process of configuring a CI/CD pipeline on EKS using Jenkins and ArgoCD. This project aims to show some hands-on experiences in deploying, securing and monitoring an application.

## 🎤 Project overview

In this project, we will cover the following key aspects:

Jenkins Server Configuration: Install and configure essential tools on the Jenkins server, including Jenkins itself, Docker, Sonarqube, Kubectl, AWS CLI, and Trivy.
EKS Cluster Deployment: Utilize eksctl commands to create an Amazon EKS cluster, a managed Kubernetes service on AWS.
Load Balancer Configuration: Configure AWS Application Load Balancer (ALB) for the EKS cluster.
Amazon ECR Repositories: Create private repositories for both frontend and backend Docker images on Amazon Elastic Container Registry (ECR).
ArgoCD Installation: Install and set up ArgoCD for continuous delivery and GitOps.
Sonarqube Integration: Integrate Sonarqube for code quality analysis in the DevSecOps pipeline.
Jenkins Pipelines: Create Jenkins pipelines for deploying backend and frontend code to the EKS cluster.
Monitoring Setup: Implement monitoring for the EKS cluster using Helm, Prometheus, and Grafana.
ArgoCD Application Deployment: Use ArgoCD to deploy the Three-Tier application, including database, backend, frontend, and ingress components.
DNS Configuration: Configure DNS settings to make the application accessible via custom subdomains.
Data Persistence: Implement persistent volume and persistent volume claims for database pods to ensure data persistence.
Conclusion and Monitoring: Conclude the project by summarizing key achievements and monitoring the EKS cluster’s performance using Grafana.

## Prerequisites

To follow this project, you must:

- Have an AWS account
- An EC2 instance with type xlarge

## 👉 Details


