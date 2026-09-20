# SonarQube Enterprise Deployment on Huawei CCE

## Project Overview

Designed and implemented a SonarQube Enterprise deployment on Huawei Cloud using Kubernetes.

The objective was to provide centralized code quality analysis and Azure DevOps integration for enterprise applications.

---

## Architecture

```text
Users
   |
Huawei ELB
   |
NGINX Ingress
   |
SonarQube Service
   |
SonarQube Pod
   |
PostgreSQL RDS
```

---

## Technologies Used

- Huawei Cloud
- CCE Kubernetes
- Helm
- SonarQube Enterprise
- PostgreSQL RDS
- Azure DevOps
- Linux
- ELB

---

## Key Activities

- Provisioned Huawei Cloud infrastructure
- Installed SonarQube using Helm
- Configured PostgreSQL RDS backend
- Integrated Azure DevOps
- Configured Kubernetes Ingress
- Verified database connectivity through ECS administration server
- Troubleshot networking and authentication issues

---

## Screenshots

### Azure DevOps Integration

screenshots/azure-devops-integration.png

### SonarQube Pods

screenshots/sonarqube-pods.png

### SonarQube Dashboard

screenshots/sonarqube-dashboard.png

### PostgreSQL RDS

screenshots/rds-postgresql.png

---

## Lessons Learned

- Kubernetes networking fundamentals
- Ingress architecture
- ELB integration
- PostgreSQL administration
- Azure DevOps onboarding
- Helm-based deployments
