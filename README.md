# airport-sdlc-automation-tool

# 🛫 Airport SDLC Automation Tool

## 📌 Problem Statement
Airports rely on mission-critical software systems such as:
- Flight Information Display System (FIDS)
- Baggage Handling Systems
- Security & Biometric Applications
- Reservation & ERP Tools

Updating these applications must be **safe, automated, and ensure zero downtime**.  
This project builds an **automation tool** that handles the full **SDLC pipeline** (Build → Test → Deploy → Monitor → Rollback).

---

## 🏗️ Architecture Overview
- **Source Code Management** → GitHub/GitLab  
- **CI/CD Pipeline** → Jenkins / GitHub Actions  
- **Testing** → Unit + Integration + Security Scans  
- **Containerization** → Docker  
- **Orchestration** → Kubernetes (EKS/Minikube)  
- **Monitoring & Rollback** → Prometheus + Grafana + AlertManager  

---

## 🚀 Features
✅ Automated Build & Test on every commit  
✅ Automated Security Scans (Trivy, SonarQube, Snyk)  
✅ Blue/Green or Canary Deployment for zero downtime  
✅ Auto Rollback if deployment fails  
✅ Monitoring dashboard with real-time health checks  

---

## 🛠️ Tech Stack
- **Version Control** → GitHub  
- **Pipeline Orchestration** → Jenkins / GitHub Actions  
- **Build Tool** → Maven (Java) / NPM (Node.js)  
- **Containerization** → Docker  
- **Orchestration** → Kubernetes (EKS/Minikube)  
- **Monitoring** → Prometheus + Grafana  
- **Cloud** → AWS (EC2, EKS, S3, IAM)  

---

## 📅 Roadmap
- **Phase 1** – Setup basics (Mock Airport App + Docker)  
- **Phase 2** – CI/CD Pipeline (Build → Test → Deploy to Staging)  
- **Phase 3** – Automated Deployment (Blue/Green + Rollback)  
- **Phase 4** – Monitoring (Prometheus + Grafana)  
- **Phase 5** – Demo & Resume Boost  

---

## ✨ Deliverable
A working SDLC automation tool with:
- Mock Airport App (Flight Info Display)  
- Jenkins pipeline running CI/CD  
- Kubernetes Deployment (with rollback)  
- Grafana dashboard monitoring app uptime/errors  
