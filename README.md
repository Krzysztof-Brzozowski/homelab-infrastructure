# HomeLab Infrastructure

A self-hosted infrastructure and cybersecurity laboratory built on Ubuntu Server. This project is used to develop practical skills in Linux administration, Docker, monitoring, networking, automation, email infrastructure, and security operations.

## Project Overview

The HomeLab serves as a production-like environment used for learning, testing, and operating real services. The infrastructure combines containerized applications, security monitoring, backup systems, and cloud integration.

## Infrastructure Stack

### Core Platform

* Ubuntu Server
* Docker
* Nginx
* Cloudflare Tunnel
* Samba File Services

### Security

* Wazuh SIEM

  * Wazuh Manager
  * Wazuh Indexer
  * Wazuh Dashboard
* Fail2Ban
* ClamAV Antivirus
* Security Monitoring and Log Analysis

### Monitoring

* Uptime Kuma
* System Monitoring
* Service Availability Monitoring

### Self-Hosted Services

* Nextcloud
* Home Assistant
* Matter Server
* UniFi Network Controller
* Portfolio Website
* Stalwart Mail Server

### Storage Architecture

* NVMe SSD – Operating System
* SSD – Docker Applications and Cache
* HDD – Primary Data Storage
* USB HDD – Backup Repository

## Technical Skills Demonstrated

* Linux Administration
* Docker Container Management
* Network Services Deployment
* Infrastructure Monitoring
* SIEM Operations (Wazuh)
* Security Hardening
* Backup and Recovery Planning
* Cloudflare Integration
* Email Infrastructure Management
* Troubleshooting and Root Cause Analysis

## Active Services

| Service           | Purpose                    |
| ----------------- | -------------------------- |
| Wazuh             | Security Monitoring & SIEM |
| Stalwart Mail     | Email Infrastructure       |
| Nextcloud         | Private Cloud Storage      |
| Home Assistant    | Smart Home Automation      |
| UniFi Controller  | Network Management         |
| Uptime Kuma       | Service Monitoring         |
| Portfolio Website | Public Portfolio Platform  |

## Project Structure

```text
homelab-infrastructure/
├── backup-strategy/
├── diagrams/
├── docker/
├── docs/
├── monitoring/
├── security/
└── screenshots/
```

## Future Development

* Automated Backup Validation
* Infrastructure as Code Documentation
* Additional Security Monitoring Integrations
* Centralized Log Management Improvements
* Internal Service Documentation
* Network Architecture Diagrams

## Project Status

Active Development

The infrastructure is continuously expanded and maintained as part of ongoing Linux, DevOps, infrastructure, and cybersecurity learning.
