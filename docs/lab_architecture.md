# Project Hydra Lab Architecture

## Overview

Project Hydra is a multi-phase cybersecurity and IT infrastructure lab designed to simulate a small enterprise environment. The project demonstrates the process of building, configuring, and administering an enterprise-style IT system while incorporating security testing and monitoring.

The architecture evolved across five implementation phases.

---

## Physical Layer

The physical layer consists of a host machine used to run all virtual infrastructure.

Components:

• Host computer  
• CPU / RAM resources for virtual machines  
• Local storage used for VM disk images  

The host system provides the compute platform for the virtual lab environment.

---

## Virtualisation Layer

Virtualisation allows multiple operating systems to run simultaneously on the host machine.

Technology used:

• VirtualBox or VMware

The hypervisor provides:

• Virtual machine creation  
• Virtual network interfaces  
• Resource allocation  
• Isolation between systems  

---

## Virtual Network Architecture

The virtual network connects all machines within the lab.

Machines included:

• Windows Server – file sharing and administrative services  
• Windows Workstation – user endpoint simulation  
• Kali Linux – penetration testing and attacker simulation  

The virtual network allows traffic to be generated, monitored, and analysed during security experiments.

---

## Administrative Access

Remote administration allows system management similar to real enterprise environments.

Access methods include:

• Remote Desktop Protocol (RDP)  
• Secure Shell (SSH)

These services allow administrators to manage systems remotely within the virtual environment.

---

## Security Testing Environment

The Kali Linux virtual machine provides penetration testing capabilities.

Tools used may include:

• Nmap – network discovery  
• Metasploit – exploitation framework  
• Burp Suite – web testing  

This machine simulates adversary activity within the network.

---

## Logging and Monitoring

Systems within the lab generate logs that can be used for troubleshooting, monitoring, and security analysis.

Examples include:

• Windows Event Logs  
• System logs  
• Network traffic

These logs support investigation of simulated security events.

---

## Architectural Goals

The Hydra lab was designed to demonstrate:

• enterprise IT infrastructure setup  
• system administration workflows  
• remote management practices  
• network segmentation concepts  
• cybersecurity testing environments

The architecture provides a safe environment for experimentation with both administration and security operations.
