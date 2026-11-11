# Containerized Web Application with CI/CD

## Project Overview

This project demonstrates the deployment of a containerized web application using Docker, Azure Container Registry (ACR), Azure Container Apps, GitHub, and GitHub Actions.

The project includes an automated CI/CD pipeline that builds and publishes Docker images to Azure whenever changes are pushed to GitHub.

## Architecture

```text
Developer
    │
    ▼
GitHub Repository
    │
    ▼
GitHub Actions
    │
    ▼
Azure Container Registry (ACR)
    │
    ▼
Azure Container App
    │
    ▼
Public URL
```

## Business Objective

The objective of this project was to automate application deployment and reduce manual deployment effort through a CI/CD pipeline.

## Technologies Used

- Docker
- Dockerfile
- GitHub
- GitHub Actions
- Azure Container Registry (ACR)
- Azure Container Apps
- Microsoft Azure

## Implementation Steps

1. Created a simple web application using HTML
2. Built a Docker image using a Dockerfile
3. Tested the container locally
4. Created an Azure Container Registry
5. Pushed Docker images to ACR
6. Created an Azure Container App
7. Deployed the container from ACR
8. Created a GitHub repository
9. Configured GitHub Actions
10. Automated Docker image builds and pushes to ACR

## Skills Demonstrated

- Docker Containerization
- Image Management
- Azure Container Registry
- Azure Container Apps
- GitHub
- GitHub Actions
- CI/CD Pipelines
- DevOps Fundamentals

## Lessons Learned

- Building Docker images from source code
- Managing container registries
- Deploying cloud-native applications
- Automating builds with GitHub Actions
- Securely storing credentials using GitHub Secrets

## Outcome

Successfully deployed a containerized application to Azure and implemented an automated CI/CD pipeline that builds and publishes Docker images whenever changes are committed to the repository.
