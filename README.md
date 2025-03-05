# Jenkins Pipeline Projects

This repository contains Jenkins pipeline examples showcasing both **Single-Stage** and **Multi-Stage** pipeline configurations.

### Single-Stage Pipeline
A simple Jenkins pipeline that runs a single stage.

#### **File:** `single-stage/Jenkinsfile`

#### **Features:**
- Runs a single **Build** stage.
- Uses the default Jenkins agent.
- Prints a message to the console.

---

### 2️⃣ Multi-Stage Pipeline
A Jenkins pipeline with multiple stages for a complete CI/CD process.

#### **File:** `multi-stage/Jenkinsfile`

#### **Features:**
- Uses **Docker containers** for different environments.
- Separates pipeline into **Back-end** and **Front-end** stages.
- Runs `mvn --version` in the Maven container.
- Runs `node --version` in the Node.js container.

---
### **Prerequisites**
- Jenkins installed with Pipeline plugin.
- Docker installed and running.

