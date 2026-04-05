# ModSecurity + Traefik WAF Integration

This project demonstrates the deployment and configuration of a Web Application Firewall (WAF) using ModSecurity integrated with Traefik in a containerized environment.

The setup leverages the OWASP Core Rule Set (CRS) to detect and block common web attacks such as Cross-Site Scripting (XSS), SQL Injection, and malformed HTTP requests.

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
