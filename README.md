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

![Hydra Architecture](images/a.png

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
Phase 1: Hardware Diagnosis & Troubleshooting
Goal: To diagnose and identify the hardware issues with all five non-working computers.
Key Tasks: Used a SystemRescue USB to boot each machine, run hardware diagnostic tests on the CPU and hard drives, and visually inspect components like RAM and hard drive connectors.
Outcome: Identified the desktop needed an SSD and DDR3/DDR3L RAM and that the laptops had issues ranging from failed hard drives to a failed CPU. Repaired the desktop by installing a 1TB SSD and two new RAM sticks.

Phase 2: Operating System Installation & Configuration
Goal: To successfully install and configure a dedicated operating system on two of my repaired laptops, setting them up for their specific roles in the home lab.
Key Tasks: Created bootable USB drives for Kali Linux and Ubuntu Server. Installed Kali Linux on the HP Pavilion for cybersecurity projects. Installed Ubuntu Server on the Toshiba Satellite to function as a server. Troubleshot and resolved common installation errors.
Outcome: Successfully installed and configured both operating systems. The HP Pavilion is now running Kali Linux, and the Toshiba Satellite is running Ubuntu Server.

Phase 3: File Server & Help Desk Implementation
Goal: To configure one of the laptops as a functional file server and help desk hub.
Key Tasks: Installed and configured Samba on the Ubuntu laptop to enable network file sharing. Set up a shared folder accessible to other devices on the network.

Phase 4: Remote Administration & Access
Goal: To demonstrate the ability to manage a server remotely from a client machine.
Key Tasks: Used SSH from the Kali Linux laptop to securely connect to and administer the Ubuntu server from a distance. Practised executing commands and managing files without a physical keyboard or monitor on the server itself.

Phase 5: Virtualisation
Goal: To set up a virtualisation platform to run multiple operating systems on a single piece of hardware.
Key Tasks: Installed the KVM hypervisor and its management tools on the Ubuntu server. Learned to create and manage virtual machines from the command line.

Phase 6: Network Scanning & Reconnaissance
Goal: To perform ethical reconnaissance against a target.
Key Tasks: Used a network scanning tool like Nmap on your Kali Linux laptop to scan your Ubuntu server for open ports and services.

Phase 7: Vulnerability Exploitation
Goal: To practice ethical hacking in a safe and controlled environment.
Key Tasks: Installed a vulnerable operating system (like Metasploitable) in a KVM virtual machine on your Ubuntu server and used tools from your Kali Linux laptop to exploit its weaknesses.

Phase 8: Hardware Repair & Documentation
Goal: To perform a complete hardware repair and document the entire process as a help desk ticket.
Key Tasks: Sourced and installed a new screen on the Samsung Galaxy Tab A9+. Used a help desk ticketing platform to document the entire process from the initial issue to the final resolution.

Phase 9: Honeypot Deployment
Goal: To deploy a defensive security tool that can detect and log malicious activity.
Key Tasks: Installed and configured a honeypot on one of your systems to act as a decoy for attackers. Analysed the logs to understand common attack patterns and behaviours.

Phase 10: Portfolio Creation & Final Documentation
Goal: To create a professional portfolio that showcases all your projects and skills.
Key Tasks: Used GitHub Pages to publish a portfolio website. Wrote a professional README.md and created individual walkthroughs for each project phase, including images and clear explanations of the outcomes.



## 🏆 Certifications & Training
* **Security Engineer Learning Path** | TryHackMe | 2024
* **Introduction to Cyber Security** | TryHackMe | 2023
* **Cybersecurity Management Job Simulation** | ANZ (via Forage) | 2025
* **Data Analytics Job Simulation** | Deloitte (via Forage) | 2025
