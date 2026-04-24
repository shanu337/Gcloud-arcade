# 🔥 Cloud NGFW (Next-Gen Firewall)

## 🧠 What is NGFW?
Cloud NGFW is an advanced firewall system in Google Cloud that provides centralized and more secure control over network traffic.

---

## 🔑 Key Concepts

### 🏷️ Tags (Important!!)
- Used to apply firewall rules to instances
- Example: ssh, web, external

### 🌐 Firewall Rules
- Control incoming & outgoing traffic
- Based on IP, ports, protocols

### 🌍 Global Network Firewall Policy
- Centralized firewall rules across networks
- More scalable than individual VPC rules

### 🔢 Tag Values
- Each tag has a numeric ID (like: tagValues/xxxx)
- Required for migration

---

## 🔥 What I Did in Lab
- Identified existing VPC firewall rules
- Created tag keys & values (ssh, web, external)
- Retrieved numeric tag values
- Created JSON mapping file
- Migrated firewall rules using gcloud command
- Verified migration using logs

---

## 💀 Challenges Faced

- Finding **numeric tag values** 😭
- JSON file formatting issues
- `.json` file extension mistake 💀
- gcloud error: `NoneType has no attribute startswith`
- Debugging CLI commands step by step

---

## 💡 Key Takeaways

- Tags are powerful for managing firewall rules
- Small mistakes in JSON can break everything
- Debugging CLI errors is a crucial skill
- Centralized firewall policies are more scalable

---

## ⚡ Important Commands (Used)

```bash
gcloud beta compute firewall-rules migrate \
--source-network=external-network \
--bind-tags-to-instances \
--tag-mapping-file=VPC_Rules.json