# Cybersecurity Portfolio - Daniyar Yakubov

3rd-year Cybersecurity student at **Narxoz University** (Almaty, Kazakhstan).
This repository documents practical projects from my coursework: the tools,
methods, and concepts I worked with across security disciplines.

> **Note on context:** Most projects below were completed in **teams of 3** as part
> of university courses. This repo describes the approach, tooling, and what I worked
> on; it intentionally **does not include exam solutions, flags, or any sensitive
> material**, in line with course policies.

**Contact:** daniarakubov5@gmail.com

---

## Penetration Testing - Black-Box Web App Audit
*Course: Ethical Hacking*

Simulated an external black-box penetration test against an isolated web
application stack (Java/Spring Boot + PostgreSQL, deployed via Docker) in Kali Linux.

**What the project covered**
- Reconnaissance: port/service scanning with `nmap`, web directory fuzzing with `ffuf`/`gobuster`
- Web vulnerability analysis: intercepting and analyzing traffic and JWT session tokens with Burp Suite
- Exploitation and access: gaining initial access and establishing a reverse shell
- Post-exploitation: local enumeration and privilege escalation on Linux
- Reporting: writing a structured technical report (executive summary, attack chain, CVSS-rated findings, remediation)

**Skills:** Kali Linux, nmap, Burp Suite, ffuf/gobuster, Linux privilege escalation, technical reporting

---

## 🔍 Reverse Engineering - CrackMe Analysis
*Course: Reverse Engineering*

Static and dynamic analysis of a 32-bit Windows PE executable to understand its
protection layers and internal logic.

**What the project covered**
- Static analysis with Ghidra; dynamic debugging with x32dbg/x64dbg and GDB
- Working through packers / manual unpacking, anti-debugging, and code obfuscation
- Tracing stack frames and calling conventions; reversing custom algorithms

**Skills:** Ghidra, x64dbg, GDB, static and dynamic analysis, anti-reversing concepts

---

## Linux System Administration - Secure Multi-User Environment
*Course: Network Administration*

Configured a Linux VM modeling a university server shared by different user
categories (teachers, students, staff, admins).

**What the project covered**
- Users, groups, and permissions (`chmod`, `chown`, `chgrp`, setuid/setgid/sticky bit, `umask`)
- Disk partitioning (`fdisk`/`gdisk`), filesystems (`ext4`/`xfs`), mounting and `/etc/fstab` with UUIDs
- Text processing and regular expressions (`grep`, `sed`, `cut`, `sort`, pipelines)
- Process management and monitoring (`ps`, `top`, `kill`, `nice`, `journalctl`)
- Package management and archiving (`apt`/`yum`, `tar`, `gzip`/`xz`)

**Skills:** Linux administration, permissions and access control, filesystems, shell and regex

---

## ☁️ Cloud-Native Security - Hardened Infrastructure
*Course: IT Infrastructure*

Deployed a resilient web application with cloud storage, with security as the
top priority (role-based access and infrastructure-as-code).

**What the project covered**
- Infrastructure as Code: provisioning resources with Terraform (LocalStack as a local AWS substitute: S3, DynamoDB)
- Role-based access control (RBAC): three access roles enforced with Spring Security
- Containers and orchestration: Docker (non-root user) and Kubernetes (replicas for HA, Secrets, ConfigMaps, network policies, least-privilege service accounts)
- Observability: metrics export and dashboards with Prometheus / Grafana

**Skills:** Terraform, Docker, Kubernetes, RBAC, secrets management, Prometheus/Grafana

---

## Social Engineering - Simulated Campaign and Defense
*Course: Social Engineering*

Designed a controlled, **ethical** social engineering campaign against a fictional
organization, then built a defense strategy.

**What the project covered**
- OSINT-based reconnaissance and design of phishing / pretexting scenarios (fictional target)
- Analysis of exploited human and organizational weaknesses
- A defense and awareness strategy: technical, organizational, and educational controls

**Skills:** OSINT, phishing/pretexting awareness, human risk analysis, security awareness and defense

---

## Malware Analysis - Stealth Threat Detection (Design)
*Course: Introduction to Undetectable Malware*

Designed an analysis and detection workflow for a stealthy-malware scenario.

**What the project covered**
- Static analysis concepts (strings, imports, entropy) and dynamic behavior logging
- Malware lifecycle mapping (execution, stealth, persistence, communication)
- Mapping malware techniques to detection gaps; designing a detection/monitoring pipeline

**Skills:** malware analysis fundamentals, detection engineering concepts, network monitoring

---

## Foundations
Relevant coursework also includes Introduction to Information Security, Introduction
to Cybersecurity, Cryptography, Computer Architecture and Operating Systems, Networking
(routing and switching, network services), and programming in Python and Java.
