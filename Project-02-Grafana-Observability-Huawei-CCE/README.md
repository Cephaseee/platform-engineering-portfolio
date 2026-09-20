
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

### Monitoring Stack

screenshots/observability-pods.png

### Grafana Dashboard

screenshots/grafana-dashboard.png

### Huawei ELB

screenshots/grafana-elb.png

### Node Monitoring

screenshots/node-monitoring.png

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
