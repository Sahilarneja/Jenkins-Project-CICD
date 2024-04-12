# jenkins-project-CICD

## Overview

This project aims to implement continuous integration and continuous deployment (CI/CD) for an application using Docker, Jenkins, and GitHub webhooks. The process involves setting up an EC2 instance, fetching code from a GitHub repository, Dockerizing the application, and triggering builds through webhooks.

## Steps

### 1. Setting Up EC2 Instance

- Launch an EC2 instance on AWS with appropriate configurations.

### 2. GitHub Repository

- Create a GitHub repository to host the project code.
- Upload the project code to the repository.

### 3. Jenkins Integration

- Set up Jenkins on the EC2 instance.
- Configure Jenkins to fetch code from the GitHub repository.
- Create a Jenkins pipeline to automate the build and deployment process.

### 4. Dockerization

- Write a Dockerfile to containerize the application.
- Build a Docker image using the Dockerfile.
- Run the Docker container on the EC2 instance.

### 5. Webhooks

- Configure webhooks in the GitHub repository to trigger Jenkins builds automatically whenever changes are pushed to the repository.


