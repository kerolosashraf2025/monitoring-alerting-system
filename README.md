# Centralized Monitoring & Alerting System

A centralized monitoring and alerting solution built using **Prometheus**, **Grafana**, and **Alertmanager** to monitor Linux hosts, visualize system metrics, and trigger alerts based on predefined rules.

This project demonstrates practical DevOps monitoring concepts with a production-like setup.

---

## Tech Stack

- Prometheus
- Alertmanager
- Grafana
- Node Exporter
- Podman (Containerized deployment)
- Linux

---

## Architecture

- Central Prometheus server scraping **Node Exporter** metrics
- Alertmanager handling alert routing and notifications
- Grafana dashboards for real-time visualization
- Containerized services using Podman

---

## Features

- Centralized metrics collection
- Host-level monitoring (CPU, Memory, Disk, Network)
- Custom alert rules for system health
- Grafana dashboards (Node Exporter Full)
- Containerized deployment using Podman

---

## Project Structure

```bash
monitoring-alerting-system/
├── prometheus/
│   ├── prometheus.yml
│   └── rules/
│       └── node-alerts.yml
├── alertmanager/
│   └── alertmanager.yml
├── grafana/
│   └── dashboards/
├── screenshots/
│   ├── 1.jpg
│   ├── 2.jpg
│   ├── 3.jpg
│   ├── 4.jpg
│   ├── 5.jpg
│   ├── 6.jpg
│   ├── 7.jpg
│   ├── 8.jpg
│   └── 9.jpg
└── README.md
