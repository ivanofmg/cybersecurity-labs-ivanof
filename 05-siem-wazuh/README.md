# 🛡️ Project Write-Up #5: SIEM Implementation with Wazuh + ELK

**Date:** May 2025  
**Author:** Ivanof

## 🎯 Objective

To implement a functional SIEM solution using Wazuh integrated with the Elastic Stack (ELK) for real-time log analysis, alerting, and threat detection across endpoints.

## 🧪 Lab Environment

- **OS**: Ubuntu Server 20.04 LTS
- **SIEM Components**: Wazuh Manager, Wazuh Agent, Filebeat, Elasticsearch, Logstash, Kibana
- **Network**: Virtualized internal LAN
- **Endpoints**: Simulated Linux and Windows nodes

## 🔧 Tasks Performed

1. Installed Wazuh manager and ELK on a single VM
2. Deployed agents on test endpoints
3. Created a custom rule to detect SSH brute-force attempts
4. Tuned Filebeat for log forwarding
5. Created dashboards in Kibana for event visualization

## ✅ Results

- Successfully triggered alerts from simulated SSH brute-force attempts
- Kibana visualizations for syslogs and auth logs
- Fully operational log collection pipeline
- Centralized event analysis and search capabilities

## 🧠 Skills Gained

- Security event correlation
- Threat detection rule tuning
- SIEM architecture and deployment
- Wazuh + ELK administration and troubleshooting
