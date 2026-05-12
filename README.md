# SOC Home Lab — Splunk SIEM with Live Threat Detection

## Overview
Built a home SOC lab using Splunk Enterprise and Ubuntu to simulate real-world threat detection and monitoring.

## Lab Architecture
- Windows 11 running Splunk Enterprise 10.2.1
- Ubuntu 22.04 endpoint
- Splunk Universal Forwarder
- VirtualBox

## Attacks Simulated
- SSH brute force attacks
- Invalid username attempts
- Firewall probe traffic

## What Splunk Detected
- Failed SSH logins
- Invalid users
- UFW firewall blocks
- 101+ security events

## Dashboard Features
- Attack timeline graph
- Top targeted usernames
- Brute force counter
- Live events table

## Tools Used
- Splunk Enterprise
- Ubuntu 22.04
- VirtualBox
- UFW
- SSH

## Screenshots

### Splunk Dashboard
![Dashboard](screenshots/dashboard.png)

### Brute Force Detection
![Bruteforce](screenshots/brute-force.png)

### UFW Logs
![UFW](screenshots/ufw-logs.png)