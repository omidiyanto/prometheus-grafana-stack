# Understanding the component
- On monitor server, you must install Prometheus & Grafana
- On client server that will be monitored, must installed node-exporter

## Notes:
- Prometheus configuration file: /etc/prometheus/prometheus.yml
- Prometheus on port 9090
- Node-Exporter on port 9100
- Grafana on port 3000

# Step-by-Step Guide for Installation
First, login as root user, for example : "sudo su -"

## Installing Prometheus on Monitor Server
curl -s https://raw.githubusercontent.com/omidiyanto/prometheus-nodeexporter-grafana-installer/main/install-prometheus | bash

## Installing Grafana on Monitor Server
curl -s https://raw.githubusercontent.com/omidiyanto/prometheus-nodeexporter-grafana-installer/main/install-grafana | bash

## Installing Node-Exporter on Client
curl -s https://raw.githubusercontent.com/omidiyanto/prometheus-nodeexporter-grafana-installer/main/install-node-exporter | bash

## Installing Apache-Exporter on Client
curl -s https://raw.githubusercontent.com/omidiyanto/prometheus-grafana-stack/main/install-apache_exporter | bash


