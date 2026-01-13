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

---

## 🌐 Access

- **Application:** http://192.168.190.129:30080
- **Argo CD UI:** http://192.168.190.129:32567

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

---

## 📸 Screenshots

Home Page:

![4080f91d-3ceb-4aa4-928c-5f766cf6df51](https://github.com/user-attachments/assets/63b34a98-ad96-4a15-a8ce-8911a79fb29f)

Dashboard:

![b5d5f9b6-6db9-44ca-8496-64d6f108fa84](https://github.com/user-attachments/assets/41a537a3-9049-4299-82cd-83a5a5751076)

Add Task Form:

![005c8a7f-2caa-463d-8926-45e31b091f2b](https://github.com/user-attachments/assets/d3c3ec89-52d4-4cfa-a743-ca4ad1844d63)

All Tasks View:

![c3572a85-41e9-490d-8a95-e1fd02c654c6](https://github.com/user-attachments/assets/f08eb9a4-b57e-4129-836d-09adfaf19c70)

Argo CD:

![279e4fa5-7bcf-462f-aa13-273bec34c3e1](https://github.com/user-attachments/assets/749f1077-594c-4205-a051-1c330a5ccacb)

