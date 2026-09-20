# SonarQube Enterprise Deployment on Huawei CCE

## Overview

Designed and implemented a SonarQube Enterprise deployment on Huawei Cloud using Kubernetes.

## Objectives

- Deploy SonarQube Enterprise using Helm
- Integrate with Azure DevOps
- Store application data in PostgreSQL RDS
- Expose the application through Huawei ELB and Kubernetes Ingress

## Technologies

- Huawei Cloud
- CCE Kubernetes
- Helm
- SonarQube Enterprise
- PostgreSQL RDS
- Azure DevOps
- Linux

## Architecture

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

## Activities Performed

- Built Huawei Cloud infrastructure
- Deployed SonarQube using Helm
- Configured PostgreSQL RDS backend
- Integrated Azure DevOps
- Configured Kubernetes Ingress
- Troubleshot connectivity and authentication issues

## Lessons Learned

- Kubernetes networking
- Ingress architecture
- Helm deployments
- PostgreSQL administration
- ELB integration
