# ☸️ Kubernetes (GKE Deployment)

## 🧠 What is Kubernetes?
Kubernetes is a system used to automate deployment, scaling, and management of containerized applications.

---

## 🔑 Key Concepts

### 📦 Containers
- Lightweight apps (Docker-based)

### ☸️ Kubernetes
- Orchestrates containers

### 🧩 Pods
- Smallest deployable unit
- Contains one or more containers

### 🛠️ Cluster
- Group of nodes (VMs) running Kubernetes

### 🌐 Services
- Expose apps to external/internal users

---

## 🔥 What I Did in Lab
- Created Kubernetes cluster (GKE)
- Deployed backend & frontend containers
- Used kubectl commands
- Exposed services using LoadBalancer
- Verified application deployment

---

## 💀 Challenges Faced

- Took **3 attempts** 😭💀
- First attempt: setup mistakes
- Second attempt: system glitch
- Third attempt: finally SUCCESS 😈
- Understanding kubectl commands
- Debugging deployment & service issues

---

## 💡 Key Takeaways

- Kubernetes is powerful but complex
- Real learning happens during debugging
- CLI commands require precision
- Patience is key (fr 😭)

---

## ⚡ Important Commands (Used)

```bash
kubectl get pods
kubectl get services
kubectl create deployment
kubectl expose deployment