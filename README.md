# 🚀  # DevOps CI/CD Pipeline Project (Jenkins + Docker on Windows)
This is a Node.js application fully containerized using Docker. It’s designed as a DevOps starter project and is ideal for practicing CI/CD automation, Jenkins pipelines, container orchestration, and deploying to cloud platforms like AWS EC2.

## Project Overview

This project demonstrates a simple **CI/CD pipeline** using **GitHub, Jenkins (running on Windows), and Docker**.
The pipeline automatically builds and deploys a containerized application whenever code is pushed to the repository.

The goal of this project is to showcase basic **DevOps practices such as Continuous Integration, Continuous Deployment, containerization, and pipeline automation.**

---

## Architecture

Developer → GitHub → Jenkins (Windows) → Docker Build → Run Container

### Workflow

1. Developer pushes code to GitHub repository.
2. Jenkins pulls the latest code from GitHub.
3. Jenkins builds a Docker image for the application.
4. Docker runs a container from the built image.
5. The application becomes accessible through the exposed port.

---

## Technologies Used

* Git & GitHub – Source code management
* Jenkins – CI/CD automation server
* Docker – Containerization platform
* Node.js – Demo application runtime
* Windows – Jenkins host system

---

## Project Structure

```
devops-demo-app
└── public/
    └── index.html
├── server.js
├── package.json
├── package-lock.json
├── Dockerfile
└── Jenkinsfile
```
---

## Application Description

A simple **Node.js Express application** that returns a message when accessed through the browser.

Example Output:

```
CI/CD Pipeline Running on Windows Jenkins!
```

---

## Prerequisites

Before running this project, ensure the following tools are installed:

* Docker Desktop
* Jenkins
* Git
* Node.js (optional for local testing)

---

## How the CI/CD Pipeline Works

### Step 1: Code Push

The developer pushes code to the GitHub repository.

### Step 2: Jenkins Pipeline Trigger

Jenkins pulls the latest code from GitHub.

### Step 3: Docker Image Build

Jenkins builds a Docker image using the Dockerfile.

### Step 4: Container Deployment

Jenkins runs a Docker container from the built image.

---

## Running the Application

After the pipeline completes successfully, open your browser and visit:

```
http://localhost:3000
```

You should see the application response.

---

## Learning Outcomes

This project demonstrates:

* CI/CD pipeline creation
* Jenkins pipeline configuration
* Docker containerization
* GitHub integration with Jenkins
* Automated deployment workflow

---

## Future Improvements

* Integrate DockerHub for image storage
* Add automated testing stage
* Deploy containers using Kubernetes
* Add monitoring using Prometheus and Grafana
* Implement Infrastructure as Code using Terraform

---

## Author

Ashish Kumar Yadav

DevOps Enthusiast | Linux | Docker | CI/CD





