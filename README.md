📝 Todo List Application – DevOps Project
📌 Project Overview

This project is a full DevOps implementation of a Todo List web application built using Node.js and MongoDB, containerized with Docker, deployed on Kubernetes, and automated using CI/CD pipelines with GitHub Actions and Argo CD (GitOps).

The goal of this project is to demonstrate real-world DevOps practices, starting from source code to automated deployment on a Kubernetes cluster.

📚 Documentation

📄 Project Documentation
👉 Under continuous improvement (Step 6 completed)

🧠 Application Description

The Todo List application is a web-based application that allows users to create and manage daily tasks.

Application Flow:

Users can add new tasks using a form

Tasks are stored in MongoDB Atlas

Tasks can be marked as completed or deleted

Views are rendered using EJS

Styled with CSS and client-side JavaScript

🏗️ DevOps Architecture
Developer (Local VM)
   ↓ git push
GitHub Repository
   ↓
GitHub Actions (CI)
   - Build Docker image
   - Push image to Docker Hub
   ↓
Argo CD (GitOps CD)
   - Watches GitHub repo
   - Syncs Kubernetes manifests
   ↓
Kubernetes Cluster
   - Deployment
   - Service (NodePort)

🛠️ Technologies Used
Application

Node.js

Express.js

EJS

JavaScript

CSS

Database

MongoDB Atlas

Mongoose

DevOps & Cloud

Docker

Docker Hub

GitHub Actions (CI)

Kubernetes

Argo CD (GitOps CD)

📁 Project Structure
Todo-List-nodejs/
├── .github/workflows/
│   └── ci.yml                 # CI pipeline (build & push Docker image)
├── k8s/
│   ├── deployment.yaml        # Kubernetes Deployment
│   └── service.yaml           # Kubernetes NodePort Service
├── config/
├── controllers/
├── models/
├── routes/
├── views/
├── assets/
├── Dockerfile
├── index.js
├── package.json
├── package-lock.json
├── README.md

🚀 CI Pipeline (GitHub Actions)

The CI pipeline automatically:

Triggers on push to main

Builds Docker image

Pushes image to Docker Hub

📄 CI file:

.github/workflows/ci.yml

🔄 CD Pipeline (Argo CD – GitOps)

Argo CD monitors the GitHub repository

Automatically syncs Kubernetes manifests from /k8s

Ensures the cluster state matches Git

Argo CD Status:

✅ Application: todo-app

✅ Status: Healthy & Synced

✅ Namespace: todo-app

☸️ Kubernetes Deployment

Deployment:

Image from Docker Hub

Environment variables from Kubernetes Secret

Service:

Type: NodePort

Exposed externally

▶️ Run Locally (Optional)
git clone https://github.com/MinaShahir/Todo-List-nodejs
cd Todo-List-nodejs
npm install
npm start

🐳 Run with Docker
docker build -t minashahir/todo-list-nodejs:1.0 .
docker run -p 4000:4000 minashahir/todo-list-nodejs:1.0

✨ Features

Create, update, and delete tasks

Mark tasks as completed

MongoDB persistent storage

Dockerized application

CI/CD automation

GitOps-based deployment

👨‍💻 Author

Mina Shahir
DevOps Engineer (Junior)

🔗 GitHub: https://github.com/MinaShahir

🎯 Project Status

✅ Step 1: Application setup
✅ Step 2: Dockerization
✅ Step 3: Push image to Docker Hub
✅ Step 4: Kubernetes deployment
✅ Step 5: Argo CD GitOps
✅ Step 6: CI with GitHub Actions
⏸️ Step 7: Image Updater (Paused)

🏁 Final Notes

This project demonstrates:

Real CI/CD pipelines

Kubernetes production concepts

GitOps best practices

End-to-end DevOps workflow
