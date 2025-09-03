# 🚑 Kubernetes Cluster Health Checker and Auto-Healing

## 📘 Overview
Managing Kubernetes clusters manually can be time-consuming and error-prone, especially for small DevOps teams. This project provides an automated health monitoring and self-healing system for Kubernetes clusters, ensuring high availability and reduced manual intervention.

## 🎯 Problem Statement
Large-scale Kubernetes clusters require constant monitoring and quick recovery from failures. Manual management leads to downtime and inefficiencies. This tool automates health checks, recovery actions, and alerting to maintain cluster stability.

## 🧭 Project Goals
- Monitor node and pod health, resource usage, and cluster metrics.
- Automatically restart failed pods and reschedule workloads.
- Trigger scaling events and rebalance resources across nodes.
- Send real-time alerts via Slack or Teams.
- Provide a web dashboard for live and historical cluster insights.

## 🛠️ Tools & Technologies
| Tool            | Purpose                                                  |
|-----------------|----------------------------------------------------------|
| Go              | Core logic and Kubernetes API integration                |
| Python          | Scripting and data preprocessing                         |
| Kubernetes API  | Cluster resource management                              |
| Prometheus      | Metrics collection                                       |
| Grafana         | Dashboard visualization                                  |
| Alertmanager    | Alert routing and severity handling                      |
| Slack API       | Real-time notifications                                  |
| Docker          | Containerization and deployment                          |

## 🚀 Project Sprints

### 🏁 Sprint 1: Setup & Access
- Initialize repo and project structure
- Configure Kubernetes API access
- Install Prometheus for metric collection

### 🔍 Sprint 2: Health Monitoring
- Monitor node and pod health
- Collect metrics via Prometheus
- Visualize metrics in Grafana
- Set up basic alerts with Alertmanager

### 🔄 Sprint 3: Pod-Level Self-Healing
- Restart/reschedule failed pods
- Clean up CrashLoopBackOff/Evicted pods
- Log healing actions for audit

### 📈 Sprint 4: Node-Level Scaling & Balancing
- Auto-scale nodes based on usage
- Enable horizontal pod autoscaling
- Redistribute pods for optimal performance

### 📣 Sprint 5: Alerting & Notifications
- Integrate Slack/Teams for alerts
- Customize alert rules by severity
- Document alert setup and management

### 📊 Sprint 6: Dashboard & Documentation
- Build Grafana dashboard or custom UI
- Display metrics, logs, and healing history
- Write setup, usage, and troubleshooting guides

## 📦 Deliverables
- ✅ Automated Health Monitoring Tool
- ✅ Self-Healing for Pods and Nodes
- ✅ Real-Time Alerts via Slack/Teams
- ✅ Web Dashboard for Monitoring
- ✅ Full Documentation

## 📚 Documentation
- [Setup Guide](docs/setup.md)
- [Usage Instructions](docs/usage.md)
- [Troubleshooting](docs/troubleshooting.md)
- [Architecture Overview](docs/architecture.md)

## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

## 📄 License
This project is licensed under the MIT License.

---
