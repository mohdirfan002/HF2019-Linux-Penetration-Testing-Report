# Linux Penetration Testing Report (HF2019)

> A complete penetration testing walkthrough demonstrating reconnaissance, enumeration, exploitation, and privilege escalation against a Linux target in a controlled lab environment.

---

## Project Overview

This repository documents the penetration testing process performed on the **HF2019 Linux machine** in a controlled laboratory environment.

The assessment follows a structured methodology, covering every phase from information gathering to obtaining root privileges while documenting the techniques, tools, and findings.

The complete walkthrough is available on Medium.

**Medium Write-up:**
https://medium.com/@mohdirfanrx/penetration-testing-report-hf2019-linux-exploitation-97678e90e05a

---

## Objectives

- Identify exposed services
- Enumerate available resources
- Discover vulnerabilities
- Gain initial access
- Perform privilege escalation
- Obtain root access
- Document the complete attack path

---

## Lab Environment

| Component | Details |
|-----------|---------|
| Attacker Machine | Kali Linux |
| Target Machine | HF2019 Linux |
| Platform | VirtualBox |
| Network | Host-Only Network |

---

## Tools Used

- Kali Linux
- Nmap
- Gobuster
- Netcat
- Searchsploit
- Linux Terminal
- Bash

---

## Methodology

### 1. Reconnaissance

- Host discovery
- Network identification

---

### 2. Port Scanning

Performed TCP port scanning to identify open services.

**Tool Used**

- Nmap

---

### 3. Service Enumeration

Enumerated:

- HTTP
- SSH
- Directories
- Web application resources

**Tools**

- Gobuster
- Browser
- Curl

---

### 4. Vulnerability Assessment

Identified vulnerable services and potential attack vectors through manual analysis.

---

### 5. Exploitation

Successfully gained initial access to the target system.

---

### 6. Privilege Escalation

Performed Linux privilege escalation techniques to obtain root privileges.

---

### 7. Post Exploitation

- User enumeration
- Sensitive file discovery
- Root access verification

---

## Skills Demonstrated

- Penetration Testing
- Linux Enumeration
- Network Scanning
- Web Enumeration
- Vulnerability Analysis
- Exploitation
- Privilege Escalation
- Documentation

---

## Screenshots

### Nmap Scan

![Nmap Scan](screenshots/nmap.png)

---

### Enumeration

![Enumeration](screenshots/enumeration.png)

---

### Exploitation

![Exploitation](screenshots/exploit.png)

---

### Root Access

![Root Access](screenshots/root.png)

---

## Project Workflow

Reconnaissance

↓

Port Scanning

↓

Service Enumeration

↓

Vulnerability Analysis

↓

Exploitation

↓

Privilege Escalation

↓

Root Access

---

## Medium Article

Read the complete walkthrough on Medium:

➡️ **[Read the Full Write-up on Medium](https://medium.com/@mohdirfanrx/penetration-testing-report-hf2019-linux-exploitation-97678e90e05a)**

---

## Disclaimer

This project was conducted in a controlled lab environment for educational and ethical purposes only. Do not attempt these techniques on systems without proper authorization.

---

## Author

**Mohamed Irfan PK**

MCA Graduate

Cybersecurity Enthusiast

SOC | VAPT | Penetration Testing

GitHub: https://github.com/mohdirfan002

Medium: https://medium.com/@mohdirfanrx
