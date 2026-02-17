# Cybersecurity Homelab - Red Team & Blue Team Simulation

A virtualized **Security Operations Center (SOC) Homelab** designed to simulate real-world enterprise attack and defense scenarios using **Splunk SIEM**, **Active Directory**, and controlled adversary activity.

This project demonstrates practical skills in:

- SIEM deployment
- Log ingestion & analysis
- Threat detection engineering
- Active Directory security monitoring
- Red Team attack simulation
- Blue Team incident response workflows

---

## Lab Overview

This homelab replicates a **mini enterprise network** where:

- Attack activity is generated from a Kali Linux system
- Logs are produced by Windows and Active Directory
- Security monitoring and detection occur in Splunk

The goal is to simulate **end-to-end SOC operations**.

---

## Architecture Diagram

![SOC Homelab Architecture](homelab.png)

---

## Lab Components

### Red Team (Attacker Environment)

**Kali Linux VM**

Used to simulate real-world attack techniques:

- Brute force attacks
- Phishing & payload delivery
- Lateral movement
- Credential harvesting
- Malware simulation

---

### Enterprise Environment

#### Windows 10 Enterprise Workstation
- Endpoint telemetry
- Sysmon logging
- PowerShell activity
- User behavior monitoring

#### Active Directory Domain Controller
- Authentication logs
- Kerberos activity
- LDAP events
- Privilege escalation tracking

---

### SIEM & Monitoring Layer

**Debian-based Splunk Server**

Responsibilities:

- Log ingestion
- Data correlation
- Detection rule execution
- Alert generation

---

## 🔍 What This Lab Simulates

### Red Team Activities

- Password spraying
- Privilege escalation
- Lateral movement
- Malicious PowerShell execution
- Malware persistence techniques

---

### Blue Team Capabilities

- Security event monitoring
- Threat detection using Splunk SPL
- Incident investigation workflows
- Alert tuning
- Detection engineering

---

## Technology Stack

| Category | Tools |
|----------|------|
| Virtualization | VMware Workstation Pro |
| SIEM | Splunk |
| Logging | Sysmon, Windows Event Logs |
| OS Platforms | Kali Linux, Windows 10, Windows Server, Debian |
| Directory Services | Active Directory Domain Services |
| Detection Framework | MITRE ATT&CK |

---


## Learning Objectives

This lab was built to develop hands-on skills in:

- SOC operations
- Threat hunting
- Log analysis
- Detection engineering
- Active Directory security
- Incident response workflows

---

## Skills Demonstrated

This project showcases practical knowledge of:

- Enterprise logging architecture
- SIEM deployment and configuration
- Attack detection lifecycle
- Security monitoring workflows
- Blue Team operational procedures

---

## Disclaimer

This lab is strictly for **educational and defensive cybersecurity purposes**.

All attack simulations are conducted within an isolated virtual environment.
