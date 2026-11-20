# Network Management & Administration Project

A practical academic project focused on designing, configuring, and managing a virtualized Linux-based network environment using Oracle VirtualBox, CentOS 7, and Ubuntu.

## Project Overview

This project was completed as part of the **IE2110 – Network Management and Administration** module at the Sri Lanka Institute of Information Technology (SLIIT).

The objective was to gain hands-on experience in Linux server administration and implementing essential network services in a virtualized environment.

## Technologies & Environment

- **Virtualization:** Oracle VirtualBox
- **Server Operating System:** CentOS 7
- **Client Operating System:** Ubuntu
- **Network Configuration:** NAT and Host-Only Network Adapters

## Network Services Implemented

### 1. DHCP Server
Configured dynamic IP address allocation for client machines within the virtual network.

### 2. DNS Server (BIND)
Configured DNS services and hostname resolution for the internal network.

### 3. Zimbra Mail Server
Installed and configured a Zimbra mail server, created mail accounts, and tested email communication between users.

### 4. Samba Active Directory
Configured domain services, organizational units (OUs), and domain user accounts.

### 5. Client Domain Integration
Connected Ubuntu client machines to the domain and verified domain membership.

### 6. Apache Web Server
Configured and tested an Apache web server and accessed the hosted web page from a client browser.

## Virtual Network Environment

The project used three virtual machines:

- CentOS 7 – Server
- Ubuntu – Client 1
- Ubuntu – Client 2

The virtual machines were configured to communicate within the virtual network.

## Repository Structure

```text
Network-Management-Administration-Project/
│
├── README.md
├── report/
│   └── assignment-report-redacted.pdf
│
└── screenshots/
    ├── 01-zimbra-admin-console.jpg
    ├── 02-samba-organizational-units.png
    ├── 03-samba-domain-users.png
    ├── 04-domain-membership-realm-list.jpg
    ├── 05-apache-service-status.jpg
    └── 06-apache-browser-output.jpg
```

## Key Learning Outcomes

Through this project, I gained practical experience in:

- Linux server administration
- Virtual machine configuration
- Network configuration and troubleshooting
- DHCP and DNS service configuration
- Mail server administration
- Active Directory and domain management
- Web server deployment and testing
- Client-server communication

## Project Documentation

The assignment report and practical implementation screenshots are included in this repository as project documentation and evidence.

## Academic Information

- **Module:** IE2110 – Network Management and Administration
- **Institution:** Sri Lanka Institute of Information Technology (SLIIT)
- **Project Type:** Academic Practical Assignment

---

**This project strengthened my practical understanding of Linux-based network administration and provided a foundation for exploring system administration, networking, Cloud, and DevOps technologies.**
