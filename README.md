# GitHub Actions CI/CD Pipeline for Docker, ECS, and EKS

This repository contains a CI/CD pipeline set up using GitHub Actions. The pipeline automates the process of building and pushing Docker images, deploying to staging and production environments, and deploying to AWS ECS (Elastic Container Service) and EKS (Elastic Kubernetes Service).

## Workflow Overview

The workflow is divided into the following four main steps:
1. **Build and Push Docker Image**
2. **Deploy to Staging and Production**
3. **Deploy to ECS**
4. **Deploy to EKS**

### Prerequisites

Before using this pipeline, ensure you have the following set up:
- AWS account with EB, S3, ECR, ECS, and EKS configurations.
- GitHub repository secrets for AWS credentials, like `AWS_ACCESS_KEY_ID`, `AWS_SECRET_ACCESS_KEY`, and `AWS_TOKEN_SESSION`.
- A Dockerfile in the root of your repository for building the image.

