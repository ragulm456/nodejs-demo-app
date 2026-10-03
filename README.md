# Node.js CI/CD Pipeline

## DevOps Internship - Task 1

This project demonstrates a CI/CD pipeline for a Node.js application using GitHub Actions and Docker.

## Technologies Used

- Node.js
- GitHub
- GitHub Actions
- Docker
- Docker Hub

## CI/CD Workflow

The pipeline is triggered whenever code is pushed to the main branch.

The pipeline performs the following steps:

1. Checkout source code
2. Setup Node.js
3. Install dependencies
4. Run tests
5. Build Docker image
6. Push Docker image to Docker Hub

## Workflow

GitHub Push
↓
GitHub Actions
↓
Install Dependencies
↓
Run Tests
↓
Build Docker Image
↓
Push Image to Docker Hub

## Docker Image

Docker Hub Repository:

ragulm456/nodejs-demo-app

## Result

The Node.js application is automatically tested and packaged into a Docker image whenever changes are pushed to the main branch.
