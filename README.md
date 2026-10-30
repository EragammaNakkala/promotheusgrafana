
# AWS Server Monitoring using Prometheus and Grafana

## Project Overview

This project implements server monitoring on an AWS EC2 Ubuntu instance using Prometheus, Grafana, and Node Exporter.

## Tools and Technologies

- AWS EC2
- Ubuntu Linux
- Prometheus
- Grafana
- Node Exporter

## Architecture

1. Node Exporter collects server metrics.
2. Prometheus collects and stores the metrics.
3. Grafana connects to Prometheus and displays the metrics in dashboards.

## Monitoring Features

- CPU usage
- Memory usage
- Disk usage
- Network traffic
- Server performance

## Configuration Files

- `prometheus/prometheus.yml` – Prometheus configuration
- `systemd/prometheus.service` – Prometheus system service
- `systemd/node_exporter.service` – Node Exporter system service

## Verification

Both Prometheus and Node Exporter targets were verified as UP in Prometheus.

Grafana was successfully connected to Prometheus, and the Node Exporter Full dashboard was imported.

## Dashboard

The Grafana dashboard displays server performance metrics, including CPU, memory, disk, and network usage.

## Conclusion

Successfully implemented a server monitoring solution using Prometheus, Grafana, and Node Exporter on AWS EC2.
