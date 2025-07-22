# ModSecurity + Traefik Integration

This project demonstrates the integration of the ModSecurity Web Application Firewall (WAF) with Traefik using Docker.

## 🔐 Key Features

- Integrated OWASP Core Rule Set (CRS) v4.14.0
- Blocking mode with detailed logging
- JSON-formatted audit and debug logs
- Protection against:
  - Cross-Site Scripting (XSS)
  - SQL Injection
  - Malformed/malicious HTTP requests

## 🛠️ Tools and Technologies

- Traefik (reverse proxy)
- ModSecurity (WAF)
- OWASP CRS
- Docker + Docker Compose

## 📝 Configuration Highlights

- Paranoia Level: 2
- Anomaly Thresholds: Inbound 10, Outbound 5
- Debug Level: 9

## 📄 Report

See the full documentation in `ModSecurity_Traefik_Final_Report.pdf`.
