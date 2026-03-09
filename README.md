# Project Hydra 1.0: Security Engineering & Infrastructure Lab
**Portfolio by Joshua Sigley**

[![GitHub](https://img.shields.io/badge/GitHub-Profile-blue?logo=github)](https://github.com/suavesigley)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin)](https://www.linkedin.com/in/joshuasigley-cybersec0)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-Profile-red)](https://tryhackme.com/p/suavesigley)

---

## 🔬 Executive Summary
Project Hydra is a multi-phase infrastructure project focused on **hardware lifecycle management** and the deployment of a **segmented virtualised laboratory**. This project demonstrates the ability to perform hardware-level diagnostics, recover decommissioned assets, and configure a secure environment for simulating enterprise-grade cyber threats and defensive workflows.

## 🛠️ Technical Specifications & Asset Recovery
Rather than purchasing new equipment, this lab was engineered by diagnosing and repairing five enterprise and consumer-grade systems to serve specific roles in a security stack.

| Asset | Technical Intervention | Lab Role |
| :--- | :--- | :--- |
| **Custom Desktop** | SSD Integration / DDR3L RAM Mapping | **Primary Hypervisor:** Hosts the virtualised corporate network. |
| **HP Pavilion** | Hardware Hardening & RAM Upgrade | **Attack Platform:** Dedicated Kali Linux machine for offensive testing. |
| **Toshiba Satellite** | Storage Expansion & OS Migration | **Log & File Server:** Ubuntu-based repository for incident data. |
| **Samsung Tab A9+** | Component Repair (Screen/Digitizer) | **Mobile Endpoint:** Researching mobile-specific threat vectors. |

## 🌐 Lab Architecture
Project Hydra simulates a small enterprise network using a **segmented architecture** to ensure that "offensive" traffic is isolated from the home production network.

> [!TIP]
> **Insert your architecture diagram (a.png) here.**
> Show the flow from the Kali Attacker machine to the Windows Target through the Hypervisor.

### Key Components:
* **Virtualised Active Directory:** Simulates an enterprise identity environment for monitoring authentication logs and IAM policies.
* **Network Segmentation:** Implemented to allow controlled attack simulations between the Kali Linux host and Windows endpoints.
* **Centralised Administration:** Utilises SSH and remote management protocols to practice secure headless server administration.

## 🛡️ Security Use Cases & SOC Workflows
The Hydra environment is used to generate telemetry and practice incident response. Key focus areas include:

* **Detection Baseline Engineering:** Executing Nmap reconnaissance to analyse how different scan types (TCP Connect vs. Stealth SYN) appear in system logs.
* **Identity Threat Analysis:** Simulating brute-force and credential-stuffing attacks against Windows services to identify **Event ID 4625** (Failed Logon) patterns.
* **Host-Based Forensics:** Using SystemRescue and command-line tools to diagnose hardware failures and "malicious" system changes.
* **Malware Sandboxing:** Developing isolated environments for detonating suspicious files to observe behaviour and document Indicators of Compromise (IoCs).

## 🎓 Core Competencies Demonstrated
* **Infrastructure & OS:** Linux Administration (Ubuntu/Kali), Windows Server, and Hypervisor management.
* **Hardware Forensics:** Component-level troubleshooting, system recovery, and performance optimisation.
* **Defensive Operations:** Mapping lab activity to the **MITRE ATT&CK framework** through practical simulation and log generation.
* **IT Operations:** Practising asset management and "Help Desk" fundamentals by maintaining the lab's hardware health.

---

## 🏆 Certifications & Training
* **Security Engineer Learning Path** | TryHackMe | 2024
* **Introduction to Cyber Security** | TryHackMe | 2023
* **Cybersecurity Management Job Simulation** | ANZ (via Forage) | 2025
* **Data Analytics Job Simulation** | Deloitte (via Forage) | 2025
