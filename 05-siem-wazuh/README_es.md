# 🛡️ Informe de Proyecto #5: Implementación de SIEM con Wazuh + ELK

**Fecha:** Mayo de 2025  
**Autor:** Ivanof

## 🎯 Objetivo

Implementar una solución SIEM funcional utilizando Wazuh y ELK para análisis de logs en tiempo real, generación de alertas y detección de amenazas en endpoints simulados.

## 🧪 Entorno de Laboratorio

- **Sistema Operativo**: Ubuntu Server 20.04 LTS
- **Componentes**: Wazuh Manager, Agente Wazuh, Filebeat, Elasticsearch, Logstash, Kibana
- **Red**: LAN virtualizada
- **Endpoints**: Clientes Linux y Windows simulados

## 🔧 Actividades Realizadas

1. Instalación de Wazuh + ELK en una sola VM
2. Despliegue de agentes en endpoints de prueba
3. Creación de regla personalizada para detectar fuerza bruta SSH
4. Configuración de Filebeat para recolección de logs
5. Diseño de dashboards en Kibana

## ✅ Resultados

- Alertas generadas ante ataques SSH simulados
- Visualización en Kibana de syslog y auth.log
- Pipeline de logs funcionando de extremo a extremo
- Capacidad de análisis centralizado de eventos

## 🧠 Habilidades Adquiridas

- Correlación de eventos de seguridad
- Tuning de reglas de detección
- Arquitectura e implementación de SIEM
- Administración de Wazuh y ELK
