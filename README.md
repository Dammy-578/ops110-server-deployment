# ops110-server-deployment
Windows Server 2019-based domain setup project for a simulated company network
# Server-Based Network Deployment – Seneca Sound Company  
**Course:** OPS110 – Windows Operating Systems  
**Date:** October 2023  
**Institution:** Seneca Polytechnic

## 🧠 Overview
This project simulates an enterprise network upgrade from a basic workgroup setup to a secure, scalable server-based domain environment. As part of the OPS110 course, I was tasked with configuring three Windows Server 2019 instances for Seneca Sound Company.

## 🛠️ Key Configurations
- Installed Windows Server 2019 Datacenter (with Desktop Experience) on 3 VMs
- Configured static IPv4 addresses on all servers
- Deployed two **Domain Controllers** (ADDS1, ADDS2) and one **File/Print Server**
- Installed and configured:
  - **Active Directory Domain Services (ADDS)**
  - **DNS Server** (on the first DC)
  - **File Services** on the File Server
- Set up a domain: `senecasoundX.com`
- Created IT user accounts and added them to the **Server Operators** group
- Customized each server’s desktop background with identifying JPGs

## 🔐 Skills Demonstrated
- Server Role Installation (ADDS, DNS, File Services)
- IPv4 networking configuration
- Domain creation and trust establishment
- Windows Server user and group management
- Custom desktop and system validation

## 🧪 Validation Tasks
- Verified server names and domain membership
- Validated TCP/IP config across servers
- Confirmed successful login for all created user accounts
- Ensured server roles were installed and active

