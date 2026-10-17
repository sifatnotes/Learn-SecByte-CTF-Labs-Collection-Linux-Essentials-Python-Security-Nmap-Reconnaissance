# Learn-SecByte-CTF-Labs-Collection-Linux-Essentials-Python-Security-Nmap-Reconnaissance
A curated collection of hands-on cybersecurity CTF labs covering Building Virtual Hacking Labs, Linux Essentials, Python for Security, Command Line Basics, OSINT Footprints, and Nmap Network Reconnaissance from Learn SecByte.
# Learn SecByte CTF & Cybersecurity Labs Collection

Welcome to the **Learn SecByte CTF & Cybersecurity Labs Collection**. This repository is a dedicated, searchable index of hands-on cybersecurity foundations, virtual hacking lab setups (Kali Linux), command-line proficiency (Bash/PowerShell), Python scripting for security, OSINT footprinting, network protocol fundamentals (OSI/TCP-IP), Nmap port scanning, and service fingerprinting labs designed for cybersecurity students, CTF players, IT professionals, and entry-level security analysts.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Building an effective career in ethical hacking and cybersecurity starts with establishing rock-solid technical foundations across operating systems, network protocols, automation, and reconnaissance methodologies. Hosted on [Learn SecByte](https://learn.secbyte.org/), this foundational collection of CTF challenge labs provides comprehensive, practical training to prepare you for real-world technical challenges.

From setting up isolated virtual machine lab environments with Kali Linux, mastering Bash and PowerShell command line interfaces, learning Python programming for security automation, and understanding Windows/Linux system architecture, to performing OSINT digital footprinting, executing Nmap scans, profiling web protocols (HTTP/DNS), and fingerprinting running network services, these exercises form the fundamental bedrock of offensive and defensive security expertise.

---

## Lab Collection & Index

Below is the complete, searchable index of all foundational setup, scripting, OSINT, networking, scanning, and service enumeration challenges in this collection:

| # | Lab / Challenge Name | Category | Focus / Key Topics | Lab Link |
|---|----------------------|----------|---------------------|----------|
| 1 | **Introduction to Cybersecurity & Ethical Hacking** | Foundations & Lab Setup | CIA triad, threat actor personas, vulnerability vs. exploit, security ethics, pentesting phases | [Access Lab](https://learn.secbyte.org/ctf/introduction-to-cybersecurity-and-ethical-hacking) |
| 2 | **Building Your Hacking Lab: Virtual Machines & Kali Linux** | Foundations & Lab Setup | VirtualBox/VMware deployment, Kali Linux installation, VM networking (Host-Only vs. NAT), snapshot management | [Access Lab](https://learn.secbyte.org/ctf/building-your-hacking-lab-virtual-machines-kali-linux) |
| 3 | **Command Line Basics: Bash & PowerShell** | Scripting & OS Fundamentals | File system navigation, file manipulation, piping (`\|`), grepping, PowerShell cmdlets, variable handling | [Access Lab](https://learn.secbyte.org/ctf/command-line-basics-bash-powershell) |
| 4 | **Linux Essentials for Hackers** | Scripting & OS Fundamentals | POSIX file permissions (`chmod`/`chown`), process management, system service management (`systemctl`), user management | [Access Lab](https://learn.secbyte.org/ctf/linux-essentials-for-hackers) |
| 5 | **Windows Fundamentals: From Desktop to Domain** | Scripting & OS Fundamentals | Windows NT architecture, Registry hives, Active Directory domain structures, Group Policy Objects (GPOs), Event Viewer | [Access Lab](https://learn.secbyte.org/ctf/windows-fundamentals-from-desktop-to-domain) |
| 6 | **Introduction to Python for Security** | Scripting & OS Fundamentals | Python syntax basics, socket programming, HTTP requests library, writing custom port scanners and automation scripts | [Access Lab](https://learn.secbyte.org/ctf/introduction-to-python-for-security) |
| 7 | **Networking Fundamentals: OSI, TCP/IP, Ports & Protocols** | Networking & Web Basics | OSI 7-layer model vs. TCP/IP stack, common ports (21, 22, 80, 443, 445), IP addressing, subnet masking, TCP handshakes | [Access Lab](https://learn.secbyte.org/ctf/networking-fundamentals-osi-tcp-ip-ports-protocols) |
| 8 | **HTTP, DNS, HTML & Browsers: Web Fundamentals Lab** | Networking & Web Basics | HTTP methods (GET/POST/PUT), header inspection, DNS resolution hierarchy, DOM tree inspection, browser developer tools | [Access Lab](https://learn.secbyte.org/ctf/http-dns-html-browsers-web-fundamentals-lab) |
| 9 | **Information Gathering & Reconnaissance** | OSINT & Reconnaissance | Passive vs. active reconnaissance, target scoping, Google dorking, WHOIS data querying, domain registration analysis | [Access Lab](https://learn.secbyte.org/ctf/information-gathering-and-reconnaissance) |
| 10 | **Open Source Intelligence: Digital Footprints & Actionable Intel** | OSINT & Reconnaissance | OSINT threat context, social media intelligence (SOCMINT), leak data correlation, public repository scraping | [Access Lab](https://learn.secbyte.org/ctf/open-source-intelligence-digital-footprints-actionable-intel) |
| 11 | **Network Scanning with Nmap** | Scanning & Fingerprinting | Nmap host discovery, SYN stealth scans, Connect scans, timing flags (`-T0` to `-T5`), output formatting (`-oN`/`-oX`) | [Access Lab](https://learn.secbyte.org/ctf/network-scanning-with-nmap-3) |
| 12 | **Service Enumeration and Fingerprinting** | Scanning & Fingerprinting | Service version probing (`-sV`), banner grabbing, default Nmap Scripting Engine (NSE) scripts (`-sC`), protocol identification | [Access Lab](https://learn.secbyte.org/ctf/service-enumeration-and-fingerprinting) |

---

## Categories

### 1. Security Foundations & Hacking Environment Setup
Learn core cybersecurity principles and build a dedicated, safe virtual environment populated with Kali Linux and vulnerable targets.
- [Introduction to Cybersecurity & Ethical Hacking](https://learn.secbyte.org/ctf/introduction-to-cybersecurity-and-ethical-hacking)
- [Building Your Hacking Lab: Virtual Machines & Kali Linux](https://learn.secbyte.org/ctf/building-your-hacking-lab-virtual-machines-kali-linux)

### 2. Operating Systems, Command Line & Security Scripting
Master command line interfaces across Linux and Windows, manage system processes, and code custom automation tools using Python.
- [Command Line Basics: Bash & PowerShell](https://learn.secbyte.org/ctf/command-line-basics-bash-powershell)
- [Linux Essentials for Hackers](https://learn.secbyte.org/ctf/linux-essentials-for-hackers)
- [Windows Fundamentals: From Desktop to Domain](https://learn.secbyte.org/ctf/windows-fundamentals-from-desktop-to-domain)
- [Introduction to Python for Security](https://learn.secbyte.org/ctf/introduction-to-python-for-security)

### 3. Networking Architecture & Web Fundamentals
Understand data packet routing, TCP/IP protocol mechanics, network port structures, and web technologies (HTTP/DNS/HTML).
- [Networking Fundamentals: OSI, TCP/IP, Ports & Protocols](https://learn.secbyte.org/ctf/networking-fundamentals-osi-tcp-ip-ports-protocols)
- [HTTP, DNS, HTML & Browsers: Web Fundamentals Lab](https://learn.secbyte.org/ctf/http-dns-html-browsers-web-fundamentals-lab)

### 4. OSINT, Network Scanning & Service Fingerprinting
Gather intelligence across public digital footprints, scan active network hosts using Nmap, and extract service banners and software versions.
- [Information Gathering & Reconnaissance](https://learn.secbyte.org/ctf/information-gathering-and-reconnaissance)
- [Open Source Intelligence: Digital Footprints & Actionable Intel](https://learn.secbyte.org/ctf/open-source-intelligence-digital-footprints-actionable-intel)
- [Network Scanning with Nmap](https://learn.secbyte.org/ctf/network-scanning-with-nmap-3)
- [Service Enumeration and Fingerprinting](https://learn.secbyte.org/ctf/service-enumeration-and-fingerprinting)

---

## Learning Path

Follow this structured progression path to build foundational technical proficiency and transition into intermediate security testing:

1. **Phase 1: Foundations, Lab Setup & Command Line Mechanics** — Understand ethical security models, configure VirtualBox with Kali Linux, and navigate terminal environments:
   - [Introduction to Cybersecurity & Ethical Hacking](https://learn.secbyte.org/ctf/introduction-to-cybersecurity-and-ethical-hacking)
   - [Building Your Hacking Lab: Virtual Machines & Kali Linux](https://learn.secbyte.org/ctf/building-your-hacking-lab-virtual-machines-kali-linux)
   - [Command Line Basics: Bash & PowerShell](https://learn.secbyte.org/ctf/command-line-basics-bash-powershell)

2. **Phase 2: Operating Systems, Networking & Scripting** — Master Linux/Windows internal structures, learn TCP/IP network mechanics, and code Python scripts:
   - [Linux Essentials for Hackers](https://learn.secbyte.org/ctf/linux-essentials-for-hackers)
   - [Windows Fundamentals: From Desktop to Domain](https://learn.secbyte.org/ctf/windows-fundamentals-from-desktop-to-domain)
   - [Networking Fundamentals: OSI, TCP/IP, Ports & Protocols](https://learn.secbyte.org/ctf/networking-fundamentals-osi-tcp-ip-ports-protocols)
   - [Introduction to Python for Security](https://learn.secbyte.org/ctf/introduction-to-python-for-security)

3. **Phase 3: Web Fundamentals & OSINT Footprinting** — Inspect web request/response headers, learn DNS workflows, and collect passive intelligence:
   - [HTTP, DNS, HTML & Browsers: Web Fundamentals Lab](https://learn.secbyte.org/ctf/http-dns-html-browsers-web-fundamentals-lab)
   - [Information Gathering & Reconnaissance](https://learn.secbyte.org/ctf/information-gathering-and-reconnaissance)
   - [Open Source Intelligence: Digital Footprints & Actionable Intel](https://learn.secbyte.org/ctf/open-source-intelligence-digital-footprints-actionable-intel)

4. **Phase 4: Network Scanning & Service Fingerprinting** — Execute active Nmap network scans, run NSE scripts, and fingerprint service versions:
   - [Network Scanning with Nmap](https://learn.secbyte.org/ctf/network-scanning-with-nmap-3)
   - [Service Enumeration and Fingerprinting](https://learn.secbyte.org/ctf/service-enumeration-and-fingerprinting)

---

## How to Use the Labs

1. Select a challenge link from the index or category sections above.
2. Read the scenario directives and target specifications on [Learn SecByte](https://learn.secbyte.org/).
3. Deploy your security workstation (Kali Linux VM inside VirtualBox or VMware).
4. Run Bash/PowerShell commands, write custom Python socket scripts, perform OSINT queries, run Nmap scans, parse HTTP headers, and capture target flags.

---

## Disclaimer

This repository and its linked challenge resources are strictly intended for educational, threat research, and authorized technical training purposes. Never execute network port scans, OSINT investigations against unauthorized individuals, or security automation scripts against production environments or unapproved third-party infrastructure.
