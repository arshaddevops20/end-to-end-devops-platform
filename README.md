# End-to-End DevOps Platform  
(IaC → CI/CD → Kubernetes → Monitoring)

## Overview
This repository demonstrates a complete, production-style DevOps workflow covering infrastructure provisioning, CI/CD automation, Kubernetes deployment, and monitoring.  
It reflects real-world DevOps practices used in enterprise cloud environments.

---

## Architecture Flow
Terraform → CI/CD → Docker → Kubernetes → Monitoring

---

## Architecture Diagram (ASCII)

                ┌──────────────┐
                │   GitHub     │
                │ Source Code  │
                └──────┬───────┘
                       │
        ┌──────────────▼──────────────┐
        │ CI/CD (Jenkins / GitHub     │
        │ Actions)                    │
        └──────────────┬──────────────┘
                       │
                ┌──────▼───────┐
                │   Docker     │
                │ Image Build  │
                └──────┬───────┘
                       │
                ┌──────▼───────┐
                │ Kubernetes   │
                │ (EKS / GKE / │
                │ KIND)        │
                └──────┬───────┘
                       │
        ┌──────────────▼──────────────┐
        │ Monitoring & Observability  │
        │ Datadog / Prometheus /      │
        │ Grafana                     │
        └─────────────────────────────┘

---

## Tech Stack
- Cloud: AWS / GCP  
- IaC: Terraform  
- CI/CD: Jenkins, GitHub Actions  
- Containers: Docker  
- Orchestration: Kubernetes  
- Monitoring: Datadog, Prometheus, Grafana  
- OS: Linux  
- SCM: Git, GitHub  

---

## Repository Structure
