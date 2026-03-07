# 🚀 Dockerized Node.js App.
This is a Node.js application fully containerized using Docker. It’s designed as a DevOps starter project and is ideal for practicing CI/CD automation, Jenkins pipelines, container orchestration, and deploying to cloud platforms like AWS EC2.

---

## 📦 Project Structure
---
local-devops-app
|__Jenkinsfile
├── Dockerfile
├── package.json
├── package-lock.json
├── server.js
└── public/
    └── index.html
---
    
## 📦 Requirements

Before you begin, make sure you have these installed on your system:

- [Node.js](https://nodejs.org/) (for local testing if needed)
- [Docker Desktop](https://www.docker.com/products/docker-desktop) (make sure Docker is running)

---

## 🛠 1. Clone or Download the Project

git clone https://github.com/ashish7408/docker-node-demo
cd docker-node-demo
## Go to your project folder then build docker image (Make sure folder contain all files and with same extentons as this one)
## 🐳 Docker Commands

### * Build the Docker image:
docker build -t local-devops-app .

### * Run the Docker Container:
docker run -d -p 8080:80 local-devops-app

### * To find all running Docker containers, use this command:
docker ps

### * If you only want the container IDs:
docker ps -q

### * To Stop a Container:
docker stop <container id>

### To run app : go to : http://localhost:8080






