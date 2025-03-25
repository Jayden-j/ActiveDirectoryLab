# Basic Home Lab - Active Directory Setup (Oracle VirtualBox)

### [YouTube Demonstration](#) *(Insert Link Here)*

## Description
This project provides a step-by-step guide for setting up a home lab running Active Directory using Oracle VirtualBox. The lab simulates a small Windows domain environment, allowing users to practice system administration, group policies, and cybersecurity techniques in a safe, controlled setup. The virtual environment consists of a Windows Server Domain Controller and a Windows Client machine.

## Technologies and Tools Used

- **Oracle VirtualBox** - Virtualization platform
- **Windows Server 2019/2022** - Active Directory Domain Services
- **Windows 10/11** - Domain-joined client machine
- **PowerShell** - Scripting and configuration
- **Group Policy Management** - Security and policy enforcement
- **DNS & DHCP** - Network configuration

## Environments Used

- **Host OS:** Windows 10/11, Linux, or macOS
- **Guest OS:** Windows Server 2019/2022, Windows 10/11

## Lab Setup Walk-through

### 1. Download and Install VirtualBox
- Download and install [Oracle VirtualBox](https://www.virtualbox.org/)
- Install the VirtualBox Extension Pack for USB and network support

### 2. Create Virtual Machines
- Create a VM for Windows Server (2 CPU, 4GB RAM, 60GB HDD)
- Create a VM for Windows Client (2 CPU, 2GB RAM, 40GB HDD)

### 3. Configure the Domain Controller
- Install Windows Server and configure Active Directory Domain Services (AD DS)
- Promote the server to a domain controller
- Set up DNS and DHCP (if needed)

### 4. Configure the Client Machine
- Install Windows 10/11
- Join the client to the domain
- Verify connectivity and authentication

### 5. Implement Group Policies
- Create security policies and apply them to domain users
- Configure password policies and account lockout settings
- Set up login scripts and mapped network drives

### 6. Testing and Security Configuration
- Verify domain authentication and user policies
- Test remote desktop and administrative tools
- Harden security with firewall rules and auditing

## Screenshots
*(Insert relevant setup screenshots here)*

## Future Enhancements
- Adding Linux machine for cross-platform testing
- Configuring additional security policies (SIEM, IDS/IPS)
- Automating setup with PowerShell scripts

## Credits
This lab is inspired by cybersecurity training labs and system administration best practices. 

---

### Disclaimer
This project is for educational purposes only. Ensure that any testing is conducted in an isolated environment and not on production networks.
