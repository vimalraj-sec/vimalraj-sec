# Hi, I'm Vimalraj 👋

**Offensive Security Professional · OSCP+ Certified**

I'm a penetration tester with hands-on experience in network exploitation, Active Directory attacks, web application security, and privilege escalation.

I hold the **OSCP+** certification and have documented **80+ full exploitation chains** across OffSec Proving Grounds and TryHackMe — with every machine following a structured, methodology-driven approach.

Before pursuing offensive security full-time, I worked as an Information Security professional at **Infosys Ltd** and **Iopex Technologies**.

I hold the **ECSA v9** certification from EC-Council (2018), which reflects a long-standing commitment to the security field — not a recent pivot.

I'm currently open to **Penetration Tester / Red Team** roles — open to on-site and remote opportunities.

## 🏆 Certifications

| Certification | Issuer | Year |
|---|---|---|
| **OSCP+** — Offensive Security Certified Professional | OffSec | 2025 |
| **ECSA v9** — EC-Council Certified Security Analyst | EC-Council | 2018 |

## 📂 Featured Repositories

### 🔴 [penetration-testing-writeups](https://github.com/vimalraj-sec/penetration-testing-writeups)
**80+ OSCP-style machine writeups** — full exploitation chains from enumeration to proof.

Platforms covered: OffSec Proving Grounds (Play & Practice) · TryHackMe  
Topics: Active Directory · Windows Exploitation · Linux Exploitation · Privilege Escalation

Every writeup follows the same structured methodology:
`Enumeration → Initial Access → Privilege Escalation → Proof`

### 📘 [penetration-testing-cheatsheet-offsec](https://github.com/vimalraj-sec/penetration-testing-cheatsheet-offsec)
**A complete offensive security reference** compiled from 2,600+ personal notes built during OSCP preparation.

12 structured sections covering:

| Section | Coverage |
|---|---|
| Shells & File Transfer | Reverse shells, shell upgrade, file transfer (Linux/Windows) |
| Reconnaissance | Nmap, Rustscan, web fingerprinting, env setup |
| Port Enumeration | Every major port (21 → 27017) with attack commands |
| Web Attacks | SQLi, LFI, SSTI, file upload bypass, CMS, XSS |
| Windows Enumeration | Post-shell enum, credential harvesting |
| Linux Enumeration | System, users, network, process, file enumeration |
| Windows PrivEsc | Services, registry, tokens, UAC bypass, Mimikatz |
| Linux PrivEsc | SUID, sudo, cron, Docker, UDF, wildcard abuse |
| Active Directory | AS-REP roasting, Kerberoasting, BloodHound, ADCS, Pass-the-Hash |
| Pivoting | Ligolo-ng, Chisel, SSH tunnels, netsh port forwarding |
| Tools Reference | Hydra, ffuf, sqlmap, hashcat, msfvenom, netexec |
| Exam Checklists | Initial access, web, Windows/Linux privesc, AD attack chains |

## 🛠️ Technical Skills

**Exploitation & Enumeration**
`Nmap` `Rustscan` `Burp Suite` `ffuf` `Gobuster` `Feroxbuster` `Metasploit` `msfvenom`

**Active Directory**
`BloodHound` `Impacket` `Netexec` `Rubeus` `Mimikatz` `Evil-WinRM`

**Privilege Escalation**
`WinPEAS` `LinPEAS` `PEASS-ng` `GTFOBins` `LOLBAS`

**Web Application**
`sqlmap` `SQLi` `LFI/RFI` `SSTI` `File Upload Bypass` `OWASP Top 10`

**Pivoting & Tunneling**
`Ligolo-ng` `Chisel` `SSH Port Forwarding` `netsh`

**Password Attacks**
`Hashcat` `John the Ripper` `Hydra` `CrackMapExec`

**Platforms**
`Kali Linux` `OffSec Proving Grounds` `TryHackMe`

## 🧠 Methodology

```
TARGET
  │
  ├─ 01. RECON ──────────── nmap / rustscan → open ports + service versions
  │
  ├─ 02. ENUMERATE SERVICES
  │      ├─ SMB 445 ──────── null session → shares → RID brute → hashes
  │      ├─ HTTP 80/443 ─── whatweb → dir bust → app fingerprint
  │      ├─ LDAP 389 ──────── anonymous dump → users
  │      └─ [all other ports enumerated per service]
  │
  ├─ 03. EXPLOIT → INITIAL SHELL
  │
  ├─ 04. POST-EXPLOITATION
  │      ├─ [Linux]   linpeas → sudo -l → SUID → cron → writable files → ROOT
  │      ├─ [Windows] winpeas → whoami /priv → services → SeImpersonate → SYSTEM
  │      └─ [AD]      BloodHound → Kerberoast / AS-REP → ADCS → PTH → Domain Admin
  │
  └─ 05. PIVOT (if multi-network)
         └─ Ligolo-ng → new subnet → repeat
```

## 📬 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Vimalraj-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/YOUR-LINKEDIN-HANDLE)
[![Open to Work](https://img.shields.io/badge/Status-Open%20to%20Work-brightgreen?style=flat)](mailto:vimalrajm.sec@gmail.com)

> 💼 **Available for Penetration Tester / Red Team roles — open to on-site and remote opportunities**


---
> ⚠️ All content in this repository is for authorized security testing and educational purposes only.
