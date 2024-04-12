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

  <img width="416" alt="Screenshot 2024-03-31 001256" src="https://github.com/Sahilarneja/jenkins-project-CICD/assets/112506972/a597b1a4-c840-4a3f-a629-079da8032bec">


### 4. Dockerization

- Write a Dockerfile to containerize the application.
- Build a Docker image using the Dockerfile.
- Run the Docker container on the EC2 instance.

  <img width="400" alt="Screenshot 2024-03-31 001334" src="https://github.com/Sahilarneja/jenkins-project-CICD/assets/112506972/eac8f209-45ec-46df-a2ac-a9979b4ae5b2">


### 5. Webhooks

- Configure webhooks in the GitHub repository to trigger Jenkins builds automatically whenever changes are pushed to the repository.

<img width="608" alt="Screenshot 2024-03-31 002802" src="https://github.com/Sahilarneja/jenkins-project-CICD/assets/112506972/03e58459-93e3-4b7b-90e3-21369a543000">


