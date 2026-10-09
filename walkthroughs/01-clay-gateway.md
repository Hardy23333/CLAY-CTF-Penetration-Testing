# CLAY Gateway — Penetration Testing Walkthrough

## 1. Target Information

| Property | Details |
|----------|---------|
| Machine | CLAY Gateway |
| IP Address | 192.168.56.101 |
| Operating System | Ubuntu Linux |
| Difficulty | Easy–Medium |
| Challenges | 5 Flags |

## 2. Objective

The objective of this challenge is to investigate
the target system, identify exposed information,
discover credentials, and analyze privilege
escalation vulnerabilities.

## 3. Reconnaissance

### Nmap Scanning

The initial reconnaissance was performed using Nmap.

```bash
nmap -sV -sC 192.168.56.101
```

The scan identified several services:

| Port | Service |
|------|---------|
| 21 | FTP |
| 22 | SSH |
| 80 | HTTP |
| 3000 | HTTP Dashboard |
| 8080 | Internal HTTP Service |

## 4. Information Gathering

The investigation involved examining multiple
information sources.

### Website Enumeration

The target website and its robots.txt file
provided information about available resources.

### Metadata Analysis

Image metadata was examined to identify
potentially exposed information.

### FTP Enumeration

The FTP service was investigated to identify
accessible files and information.

### OSINT Correlation

Information collected from multiple sources
was correlated to understand credential patterns.

## 5. Initial Access

The walkthrough documents the process of
identifying login credentials and accessing
the target through SSH.

## 6. Lateral Movement

Further investigation identified an internal
service and exposed configuration information.

## 7. Privilege Escalation

The final stage involved analyzing an
insecurely configured cron job.

The permissions allowed a lower-privileged
account to modify a script executed by root.

## 8. Security Findings

- Sensitive information exposure
- Weak credential practices
- Exposed configuration files
- Insecure file permissions
- Cron job privilege escalation

## 9. Mitigation Recommendations

- Remove sensitive information from public resources.
- Avoid predictable passwords.
- Protect configuration files containing credentials.
- Restrict write permissions on privileged scripts.
- Audit scheduled tasks and service configurations.

## 10. Evidence

Screenshots and command outputs will be
organized in the screenshots directory.
