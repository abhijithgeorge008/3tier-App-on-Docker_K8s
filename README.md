# 🏗️ Three-Tier Application on Docker & Kubernetes

## 📌 Project Overview
Built and deployed a production-ready three-tier web 
application using Docker and Kubernetes (K8s), with a 
Jenkins-based CI/CD pipeline for automated builds and 
deployments. This project demonstrates container 
orchestration, microservices architecture, and DevOps 
automation from code to deployment.

---

## 🏛️ Architecture

---

## 🛠️ Technologies Used

| Category | Technology |
|---|---|
| Frontend | HTML, CSS, JavaScript |
| Backend | Node.js |
| Containerization | Docker, Docker Compose |
| Container Orchestration | Kubernetes (K8s) |
| CI/CD | Jenkins (Jenkinsfile) |
| K8s Manifests | Deployments, Services, ConfigMaps |
| Version Control | Git, GitHub |

---

## 📁 Repository Structure

---

## 🔁 CI/CD Pipeline (Jenkinsfile)

---

## 🚀 How to Run Locally

### Using Docker Compose
```bash
# Clone the repository
git clone https://github.com/abhijithgeorge008/3--Tier-app-on-Docker-K8s

# Start all services
docker-compose up -d

# Verify containers are running
docker ps

# Access the application
# http://localhost:3000
```

### Using Kubernetes
```bash
# Apply Kubernetes manifests
kubectl apply -f k8s/

# Check deployment status
kubectl get pods
kubectl get services

# Access via NodePort or LoadBalancer
kubectl get svc
```

---

## ✅ Key Achievements

- 🐳 Containerized all three tiers using Docker
- ☸️ Deployed and managed with Kubernetes manifests
- 🔄 Automated build & deploy pipeline via **Jenkinsfile**
- 📦 Docker Compose setup for fast local development
- 🔧 **30 commits** of active development and improvements
- 🌍 Architecture supports horizontal scaling via K8s replicas

---

## 📚 What I Learned

- Designing and containerizing multi-tier applications
- Writing Kubernetes manifests for real deployments
- Building Jenkins pipelines for automated CI/CD
- Managing multi-container environments with Docker Compose
- Kubernetes service discovery and inter-tier communication

---

## 👤 Author
**Abhijith George**
Cloud & DevOps Engineer (Transitioning)
[LinkedIn](https://linkedin.com/in/abhijith-george-2107b911a) | 
[GitHub](https://github.com/abhijithgeorge008)
