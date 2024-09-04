# FinalProject

### done by:
- Mohamed Ahmed Almemari
- Maha Alzaabi

# Infrastructure Monitoring and Stress Testing Project

## Project Description

This project involves setting up a monitoring and alerting system for a multi-server infrastructure that includes a Prometheus server, a MySQL server, and a Grafana server. The objective is to ensure that the infrastructure's CPU, memory, disk, and SQL resources are effectively monitored during stress tests, with alerts being triggered when resource usage exceeds specified thresholds.

### Infrastructure Setup

- **VM_0**: Prometheus Server
- **VM_1**: MySQL Server
- **VM_2**: Grafana Server

### Tasks

#### Task 0: Install MySQLD_Exporter & NodeExporter on VM_1
- Install the necessary exporters on the MySQL server to monitor its metrics.

#### Task 1: Install AlertManager on VM_0
- Set up AlertManager on the Prometheus server to handle alerts and notifications.

#### Task 3: Configure AlertManager to Send Email Notifications
- Set up email notifications in AlertManager to notify the relevant stakeholders when alerts are triggered.

#### Task 4: Write a Python Script in VM_1 to Perform Stress Tests
- **Press 1**: Perform CPU Stress Test
- **Press 2**: Perform Memory Stress Test
- **Press 3**: Perform Disk Stress Test
- **Press 4**: Perform SQL Stress Test

#### Task 5: Write Prometheus Rules to Monitor Resource Usage
- Monitor CPU, memory, disk, and SQL stress tests.
- Trigger an alert if resource usage exceeds 70%.
- Configure AlertManager to send a CC email to `cprofessional01@gmail.com`.

#### Task 6: Configure Grafana Server with NodeExporter & MySQL Dashboard
- Set up Grafana to monitor the resources during stress testing and visualize the metrics.

#### Task 7: Create a GitHub Repository
- Create a GitHub repository containing all project files, including Python scripts, YAML files, etc.
- Include a README file with the project description, objectives, and details.

## Objectives

1. **Monitoring**: Set up comprehensive monitoring for CPU, memory, disk, and SQL metrics on the MySQL server.
2. **Alerting**: Ensure that alerts are triggered when resource usage exceeds 70% during stress tests, and that email notifications are sent to the relevant stakeholders.
3. **Visualization**: Use Grafana to visualize resource usage and performance metrics in real-time.
4. **Automation**: Write scripts to automate stress testing and monitoring tasks.
5. **Documentation**: Document the project setup, configuration, and usage details in a GitHub repository.
