
# Grafana Observability Platform on Huawei CCE

## Project Overview

Implemented a Kubernetes observability platform using Grafana, Prometheus, Alertmanager, kube-state-metrics and Node Exporter.

The platform provides visibility into cluster health, node performance and application workloads.

---

## Architecture

```text
Users
   |
Huawei ELB
   |
Grafana Service (LoadBalancer)
   |
Grafana Pod
   |
Prometheus
   |
Node Exporter
   |
Huawei CCE Cluster
```

---

## Technologies Used

- Grafana
- Prometheus
- Alertmanager
- Node Exporter
- kube-state-metrics
- Kubernetes
- Helm
- Huawei ELB

---

## Key Activities

- Installed kube-prometheus-stack
- Configured Grafana
- Configured Prometheus
- Deployed Alertmanager
- Exposed Grafana via Huawei ELB
- Built Kubernetes monitoring dashboards
- Implemented cluster observability

---

## Screenshots

### Grafana Login Page

screenshots/grafana-login-page.png

### Grafana Home

screenshots/grafana-home.png

### Monitoring Stack Pods

screenshots/observability-pods.png

### Huawei CCE Dashboard

screenshots/grafana-cce-dashboard.png

### Node Monitoring Dashboard

screenshots/grafana-node-dashboard-01.png

### Additional Node Metrics

screenshots/grafana-node-dashboard-02.png

### Huawei ELB

screenshots/grafana-elb.png

### Grafana LoadBalancer Service

screenshots/grafana-loadbalancer-service.png

---

## Monitoring Capabilities

The solution provides visibility into:

- Node CPU
- Node Memory
- Node Storage
- Cluster Health
- Pod Health
- Namespace Utilization
- SonarQube Resource Consumption
- Prometheus Status
- Alertmanager Status

---

## Lessons Learned

- ClusterIP vs LoadBalancer Services
- Kubernetes networking
- Prometheus metrics collection
- Dashboard creation
- ELB integration
- Operational observability
