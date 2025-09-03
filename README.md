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
This project is licensed .


<img width="1915" height="887" alt="image" src="https://github.com/user-attachments/assets/04775324-50ee-4534-a9e9-0cbf0c5b4037" />
<img width="1587" height="785" alt="image" src="https://github.com/user-attachments/assets/1b5a4660-c71d-40b2-972d-8bfd7dde7ad0" />
<img width="1886" height="482" alt="image" src="https://github.com/user-attachments/assets/7134921b-5621-40a3-94e0-b78b6986e6c0" />
--<img width="1562" height="838" alt="image" src="https://github.com/user-attachments/assets/fe7bf169-af83-4f42-8d4d-d481965ce3f6" />
<img width="1902" height="877" alt="image" src="https://github.com/user-attachments/assets/a01352d5-a5e7-478d-89ad-1913b4909414" />
<img width="1908" height="900" alt="image" src="https://github.com/user-attachments/assets/1f31494e-c840-4e1a-9951-098da2b7a305" />
<img width="1912" height="922" alt="image" src="https://github.com/user-attachments/assets/d7634d6a-d56d-4ecb-ba48-24c69a47c083" />
<img width="1912" height="877" alt="image" src="https://github.com/user-attachments/assets/2a6ab88b-af52-4e23-9dd5-254cf8461161" />




-
