# ELK SIEM – Web Attack Detection

## Overview

This project demonstrates the deployment and configuration of the Elastic Stack (ELK) for collecting Apache web server logs and creating custom detection rules for web attack monitoring.

The project includes the installation of the Apache HTTP Server on Linux, configuration of the Apache integration in Elastic, verification of log ingestion, and creation of a custom detection rule within Kibana.

This laboratory project demonstrates practical experience with Security Information and Event Management (SIEM) technologies, Linux administration, and log management.

---

## Technologies

- Elasticsearch
- Logstash
- Kibana
- Apache HTTP Server
- Elastic Agent
- Linux
- SIEM

---

## Objectives

- Deploy Apache Web Server
- Configure Apache Integration
- Collect Apache Logs
- Verify Log Ingestion
- Create a Custom Detection Rule
- Configure Rule Severity
- Prepare ELK for Web Attack Detection

---

# Project Workflow

## Step 1 — System Update

Updated the Linux operating system before installing the required software packages.

![System Update](system_update.png)

---

## Step 2 — Apache Web Server Installation

Installed and configured the Apache HTTP Server.

Verified that the service was successfully installed and operational.

![Apache Installation](apache_webserver_installation.png)

---

## Step 3 — Apache Installation Verification

Confirmed that the Apache installation completed successfully.

![Installation Completed](installaton_is_over.png)

---

## Step 4 — Configure Apache Integration

Configured the Apache Integration within the Elastic Agent Policy.

This enables Apache logs to be collected automatically by Elasticsearch.

![Apache Integration](integration_to_elastic.png)

---

## Step 5 — Save Integration Configuration

Saved the integration settings and applied the configuration.

![Saving Configuration](saving_configuration.png)

---

## Step 6 — Verify Log Collection

Verified that Apache log events were successfully ingested into Elasticsearch.

![Verifying Log Collection](verifying_logcollection.png)

---

## Step 7 — Create a Custom Detection Rule

Created a Custom Query Detection Rule within Kibana to detect suspicious web activity.

![Custom Detection Rule](custom_detectionrule.png)

---

## Step 8 — Configure Rule Severity

Assigned **High** severity to the detection rule according to the simulated attack scenario.

![Rule Severity](ruleseverity.png)

---

## Step 9 — Configuration Review

Reviewed the final ELK configuration before enabling the detection rule.

![Configuration](configuration.png)

---

## Step 10 — Final Result

Successfully completed the deployment and configuration of an ELK SIEM environment capable of collecting Apache logs and supporting web attack detection through custom detection rules.

![Successfully Created](succesfully_created.png)

---

# Skills Demonstrated

- ELK Stack Deployment
- Elasticsearch Configuration
- Kibana Administration
- Apache Integration
- Elastic Agent Configuration
- Linux Administration
- Log Collection
- SIEM Fundamentals
- Detection Rule Configuration
- Web Attack Monitoring

---

# Learning Outcomes

Through this project I gained practical experience in:

- Deploying an ELK SIEM environment
- Installing and configuring Apache Web Server
- Integrating Apache logs with Elastic
- Configuring Elastic Agent policies
- Creating custom detection rules
- Working with Kibana Detection Engine
- Understanding SIEM workflow and log ingestion

---

# Author

**Nurshat Alzhan**

Cybersecurity Student

Astana IT University
