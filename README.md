# CLAY CTF — Penetration Testing & Vulnerability Analysis

## Project Overview

CLAY CTF is a team-based cybersecurity project developed
and completed collaboratively by a team of seven members.

The project features a virtualized CTF environment consisting
of four machines running Ubuntu Linux and Windows Server 2022.

The lab covers a range of cybersecurity techniques, including
network reconnaissance, web application exploitation,
binary exploitation, reverse engineering, and privilege escalation.

This repository documents the CTF environment, security
challenges, exploitation methodologies, Python scripts,
and technical findings.

## Team Information

- Project Type: Team-Based Cybersecurity CTF
- Team Size: 7 Members
- Environment: VirtualBox
- Attacker Machine: Kali Linux
- Target Systems: Ubuntu Linux and Windows Server 2022
- Total Challenges: 11 Flags

## Lab Environment

| Machine | Operating System | Main Focus | Flags |
|---------|------------------|------------|-------|
| CLAY Gateway | Ubuntu Linux | OSINT and Privilege Escalation | 5 |
| Cipher Node | Ubuntu Linux | SQL Injection and Command Injection | 2 |
| Whoami Core | Ubuntu Linux | Binary Exploitation | 2 |
| Bastion | Windows Server 2022 | Reverse Engineering and Windows Security | 2 |
| **Total** | | | **11** |

## Tools and Technologies

### Operating Systems
- Kali Linux
- Ubuntu Linux
- Windows Server 2022

### Network Security
- Nmap
- SSH
- FTP
- SMBClient
- Netcat

### Programming and Exploitation
- Python
- Python Requests
- Pwntools
- Shell Scripting

### Security Techniques
- OSINT
- SQL Injection
- Command Injection
- Buffer Overflow
- Reverse Engineering
- Insecure Deserialization
- Linux Privilege Escalation
- Windows Privilege Escalation

## Penetration Testing Walkthroughs

### 1. CLAY Gateway

Focus:
- Network reconnaissance
- Information gathering
- Credential discovery
- Lateral movement
- Linux privilege escalation

[View Walkthrough](walkthroughs/01-clay-gateway.md)

### 2. Cipher Node

Focus:
- SQL injection
- Authentication bypass
- Command injection
- SUID exploitation

[View Walkthrough](walkthroughs/02-cipher-node.md)

### 3. Whoami Core

Focus:
- Binary analysis
- Buffer overflow
- Shellcode execution
- Privilege escalation

[View Walkthrough](walkthroughs/03-whoami-core.md)

### 4. Bastion — Windows Server

Focus:
- SMB enumeration
- Reverse engineering
- Insecure deserialization
- Remote code execution
- Windows privilege escalation

[View Walkthrough](walkthroughs/04-bastion-windows.md)

## Project Documentation

This repository includes:

- Penetration testing walkthroughs
- Python exploitation scripts
- Screenshots and experimental evidence
- Vulnerability analysis
- Security findings and mitigation recommendations

## Virtual Machine Environment

The complete CTF virtual machine archive is approximately
20 GB and is not included in this GitHub repository.

The repository focuses on documenting the cybersecurity
techniques, experiments, and findings from the CTF project.

## Team Collaboration

This project was completed through collaboration among
seven team members.

The project involved technical research, security testing,
problem-solving, and documentation.

## Disclaimer

This project was conducted in an isolated CTF lab
environment for educational and authorized security testing.

All techniques and scripts are intended for educational
and security research purposes only.
