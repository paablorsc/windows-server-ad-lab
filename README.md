# CoreLine Server Infrastructure Lab

This project demonstrates the design and implementation of a Windows Server-based IT environment using Active Directory and related network services.

---

## Overview

The goal of this project was to simulate a small company infrastructure and manage users, computers, and resources from a centralized server.

The environment was built in a virtual lab using VMware Workstation.

---

## Technologies Used

- Windows Server (Domain Controller)
- Active Directory Domain Services (AD DS)
- DNS
- DHCP
- Group Policy (GPO)
- File Sharing
- Windows 10 Clients
- Kali Linux (security testing)
- VMware Workstation

---

## Network Configuration

- Network: 192.168.10.0/24
- Server IP: 192.168.10.10
- DHCP Range: 192.168.10.100 – 192.168.10.200
- DNS Server: 192.168.10.10

---

## Environment Structure

- 1 Server (CORELINE-SERVER)
  - Domain Controller
  - DNS & DHCP Server
  - File Server

- 2 Workstations
  - CORELINE-W10-01
  - CORELINE-W10-02

- 1 Kali Linux Machine
  - Used for security testing

---

## Features Implemented

- Active Directory domain (coreline.local)
- User and group management
- Group Policy configuration
- Shared folders and network drives
- Domain-joined workstations
- Remote Desktop access
- Network printer setup
- Windows Server Backup

---

## Security Testing

Security analysis was performed using:

- Nmap (network scanning)
- Wireshark (traffic analysis)
- Nessus (vulnerability scanning)
- Metasploit (security testing)

---

## Purpose

This project was created as part of a learning process to understand:

- Server administration
- Network configuration
- Active Directory management
- Basic cybersecurity practices

---

## Screenshots

Screenshots of the environment and configurations are included in the repository.

---

## Author

Student project – CoreLine Solutions Ltd (simulated company)
