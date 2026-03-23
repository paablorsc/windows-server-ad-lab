# Windows Server Active Directory Lab

## Overview

This project demonstrates the setup of a Windows Server environment using Active Directory.

The goal was to manage users, computers, and network resources from a central server in a virtual lab.

---

## Key Features

- Active Directory domain setup
- Centralized user and group management
- Group Policy configuration
- Network services (DNS, DHCP)
- File sharing and network drives
- Remote access (RDP)
- Network printer configuration
- Security testing (Nmap, Wireshark, Nessus, Metasploit)

---

## Environment

- Windows Server (Domain Controller)
- Windows 10 workstations
- Kali Linux (security testing)
- VMware Workstation

---

## Network Configuration

- Network: 192.168.10.0/24
- Server IP: 192.168.10.10
- DHCP enabled for clients
- DNS configured on server

---

## Active Directory

Active Directory was installed and configured.

Users and groups were created for centralized management.

- Domain: coreline.local
- Users added to groups
- Permissions managed through groups

![Active Directory - users and groups](https://github.com/user-attachments/assets/cf0497b4-4011-4d88-9c8a-165884fea7c3)

*Users and groups created in Active Directory*


![Active Directory - structure](https://github.com/user-attachments/assets/aae0be35-24f5-4be7-ad11-c40497dae006)

*Organizational structure inside Active Directory*

---

## Group Policy

A Group Policy Object (GPO) was created to manage workstation settings and security.

Configuration:

- GPO name: Workstation Security GPO  
- Linked to domain  
- Applied to domain computers  

Security settings:

- Password policy  
- Firewall enabled  
- Automatic updates  
- User restrictions  

The policy allows centralized control of user and system settings.

![Group Policy Management](https://github.com/user-attachments/assets/19ad8cec-6a13-433a-ac49-8c5dadc0bb95)
*Workstation Security GPO configured in Group Policy Management*

---

## File Sharing

Shared folders were created on the server.

- Central file storage
- Access controlled using groups
- Network drives mapped on clients

![File Sharing](https://github.com/user-attachments/assets/1c71325f-7087-49d8-80a4-abb6a4783229)
*Shared folders configured on the server*

---

## Domain Join

Workstations were joined to the domain.

- Users can log in with domain accounts
- Central authentication enabled

![Domain Join](https://github.com/user-attachments/assets/e02ecf3c-eceb-40ba-8805-51febd7bd9ec)

*Workstation successfully joined to the domain*

---

## Remote Access

Remote Desktop was enabled on the server.

- Server can be accessed remotely
- Admin control from another machine

![Remote Desktop](https://github.com/user-attachments/assets/b1e81a16-1e66-4b13-9243-20ab124424f0)

*Remote Desktop connection to the server*

---

## Network Printer

A network printer was added using TCP/IP.

- Static IP assigned
- Shared to clients

![Network Printer](https://github.com/user-attachments/assets/c2f892a4-2a3b-4137-80cc-14e0f2a60978)

*Printer configured using Standard TCP/IP port*

---

## Security Testing

Security tools were used to analyze the network.

### Nmap

- Network scan performed
- Open ports identified

![Nmap Scan](https://github.com/user-attachments/assets/afe2beb6-2a87-4eae-8f37-db9bc0cfdf36)

*Nmap scan results showing open ports*

---

### Wireshark

- Network traffic captured
- ICMP packets analyzed

![Wireshark](https://github.com/user-attachments/assets/a2e79b9d-4f9f-4eb2-a41a-46288f90dd6d)

*ICMP traffic captured using Wireshark*

---

### Nessus

- Vulnerability scan performed
- No critical issues found

![Nessus Scan](https://github.com/user-attachments/assets/8bb3b376-ce6c-473e-badc-7f108110a51f)
![Nessus Results](https://github.com/user-attachments/assets/044a1ba4-eaa9-4363-b1a3-e5459b0be0df)

*Nessus vulnerability scan results*

---

### Metasploit

- Basic service analysis performed
- Security testing in lab environment

![Metasploit](https://github.com/user-attachments/assets/90e67cb1-9184-4445-a688-3ea41bc17c3e)
![Metasploit Console](https://github.com/user-attachments/assets/7cb863fe-fd5a-496e-8d65-12bbabe79f6c)

*Metasploit used for service analysis*

---

## Conclusion

This project demonstrates:

- Active Directory setup
- Network service configuration
- Group Policy management
- Basic cybersecurity testing

The lab helped develop practical skills in system administration and security.
