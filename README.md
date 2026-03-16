# devops-monitoring-project
Designed and implemented a cloud-native monitoring pipeline using Terraform for infrastructure provisioning, Ansible for configuration management, Docker for containerization, Jenkins for CI/CD automation, and Prometheus + Grafana for real-time monitoring.

# Technologies Used

- Docker
- Jenkins
- Terraform
- Ansible
- Prometheus
- Grafana
- AWS EC2
- Python (Flask API)

---
# Application

A lightweight Python Flask API is used to demonstrate application monitoring.

The application exposes a `/metrics` endpoint compatible with Prometheus.

Example endpoints:


---

# Docker

The application is containerized using Docker.

Build the Docker image:



---

# Terraform (Infrastructure as Code)

Terraform provisions cloud infrastructure on AWS.

Resources created:

- EC2 instance
- Security configuration
- Infrastructure tags

Deploy infrastructure:
