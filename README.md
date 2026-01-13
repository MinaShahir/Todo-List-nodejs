# Todo-List-nodejs 🚀

## DevOps Project – Docker, CI/CD, Kubernetes & Argo CD

A full DevOps implementation for a Node.js To-Do List application, covering containerization, CI pipeline, Kubernetes deployment, and GitOps using Argo CD.

---

## 📝 Project Description

This project is a **Node.js To-Do List web application** enhanced with a **complete DevOps workflow**.

The application allows users to:
- Create tasks
- Update task status
- Delete tasks
- Persist data using MongoDB

On top of the application layer, the project implements:
- Docker containerization
- CI pipeline with GitHub Actions
- Kubernetes deployment
- GitOps continuous delivery using Argo CD

---

## 🧱 Architecture Overview

Developer → GitHub → GitHub Actions (CI)
|
↓
Docker Hub
|
↓
Kubernetes Cluster
|
↓
Argo CD

yaml
Copy code

---

## 🛠 Technologies Used

### Application
- Node.js
- Express.js
- EJS
- MongoDB
- Mongoose

### DevOps & Cloud Native
- Docker
- GitHub Actions (CI)
- Kubernetes
- Argo CD (GitOps)
- Docker Hub
- Linux (Ubuntu VM)

---

## 📂 Project Structure

Todo-List-nodejs/
├── .github/workflows/ci.yml
├── k8s/
│ ├── deployment.yaml
│ ├── service.yaml
├── argocd-app.yaml
├── Dockerfile
├── index.js
├── package.json
├── controllers/
├── routes/
├── models/
├── views/
├── assets/
└── README.md

yaml
Copy code

---

## 🚀 Implemented Steps (Up to Step 6)

### ✅ Step 1: Application Setup
- Node.js app with Express & MongoDB

### ✅ Step 2: Dockerization
- Dockerfile created
- Application containerized
- Image pushed to Docker Hub

### ✅ Step 3: CI Pipeline
- GitHub Actions workflow
- Automatic Docker build & push on every commit

### ✅ Step 4: Kubernetes Deployment
- Deployment & Service YAMLs
- Application exposed via NodePort

### ✅ Step 5: Argo CD Installation
- Argo CD installed in Kubernetes
- UI exposed using NodePort

### ✅ Step 6: GitOps with Argo CD
- Argo CD Application created
- Git repository connected
- App auto-synced and healthy

> ⛔ Step 7 (Advanced CD automation) intentionally skipped for now.

---

## 🌐 Access

- **Application:** http://192.168.190.129:30080
- **Argo CD UI:** http://192.168.190.129:32567

---

## 📸 Screenshots

> _(Add your screenshots here later if needed)_

---

## 👨‍💻 Author

**Mina Shahir**  
DevOps Engineer (Junior)  
📧 Email: minashahir@yahoo.com
🔗 GitHub: https://github.com/MinaShahir

---

## 🎯 Key DevOps Skills Demonstrated

- Docker & container lifecycle
- CI pipelines with GitHub Actions
- Kubernetes workloads & services
- GitOps using Argo CD
- Debugging real-world Git & CI/CD issues

---

## 📌 Notes

This project is designed as a **real-world DevOps learning project**, focusing on practical issues such as:
- CI authentication
- Docker image management
- Kubernetes networking
- Git conflicts & rebasing
- GitOps best practices

---

## ✅ Status

✔ Application Healthy  
✔ CI Pipeline Working  
✔ Argo CD Synced  
✔ Kubernetes Running  
