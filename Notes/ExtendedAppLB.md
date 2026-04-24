# 🌍 Extended Application Load Balancer (HTTPS)

## 🧠 What is Extended Application Load Balancer?
A global load balancer in Google Cloud that distributes user traffic across multiple backend services using HTTPS (secure protocol).

---

## 🔑 Key Concepts

### 🌍 Global Load Balancer
- Works across multiple regions
- Routes users to nearest/healthy backend
- High availability & fault tolerance

### 🔒 HTTPS (Secure Traffic)
- Uses SSL/TLS certificates
- Encrypts data between user and server

### 🧱 Backend Services
- Group of instances (VMs) serving requests
- Attached to load balancer

### ❤️ Health Checks
- Monitors backend instances
- Sends traffic only to healthy servers

### 🔁 URL Mapping
- Routes requests based on URL paths

### 📡 Forwarding Rules
- Direct incoming traffic to target proxy

---

## 🔥 What I Did in Lab

- Created backend VM instances
- Set up instance groups
- Configured health checks
- Created backend services
- Set up URL map
- Configured target HTTPS proxy
- Added SSL certificate
- Created global forwarding rule
- Tested application via external IP

---

## 💀 Challenges Faced

- Multi-step configuration (very long process 😭)
- Understanding how components connect together
- SSL certificate setup confusion
- Keeping track of all resources (backend, proxy, rules)

---

## 💡 Key Takeaways

- Load balancing is critical for real-world apps
- HTTPS ensures secure communication
- Multiple components work together (not just 1 service)
- Architecture thinking improved a lot

---

## ⚡ Flow