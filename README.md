# Prometheus Monitoring Platform

## 项目简介

基于 Docker Compose 搭建的监控告警平台。

## 技术栈

- Prometheus
- Grafana
- Alertmanager
- Node Exporter
- Nginx
- Docker Compose

## 功能

- 主机资源监控
- CPU告警
- 邮件通知
- Grafana可视化

## 项目结构

infra/
├── alertmanager/
├── deploy/
├── nginx/
├── prometheus/
└── registry/

scripts/
├── start.sh
├── stop.sh
└── restart.sh
