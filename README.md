# 📊 Monitoring System using Prometheus & Grafana

## 📌 Project Overview

This project implements a real-time monitoring system using Prometheus and Grafana. System metrics are collected using Node Exporter and visualized through Grafana dashboards.

## 🛠️ Tech Stack

* Prometheus (Metrics Collection)
* Grafana (Visualization)
* Node Exporter (System Metrics)
* Docker (Containerization)
* AWS EC2 (Hosting)

## ⚙️ Architecture

Node Exporter → Prometheus → Grafana Dashboard

## 🔄 Workflow

1. Node Exporter collects system metrics
2. Prometheus scrapes metrics
3. Grafana visualizes data
4. Dashboards display real-time CPU usage

## ▶️ How to Run

```bash
docker-compose up -d
```

Access:

* Prometheus → http://localhost:9090
* Grafana → http://localhost:3000

## 📸 Screenshots

(Add images inside /screenshots folder)

* Grafana dashboard
* Prometheus targets (UP)
* Docker containers running

## 📄 Documentation

👉 [View Full Project Report](./Monitoring-Documentation.pdf)

## 💡 Future Improvements

* Add alerting using Alertmanager
* Monitor multiple servers
* Integrate with cloud monitoring

## 📚 Key Learnings

* Monitoring & observability
* Metrics collection and visualization
* Docker-based deployment
