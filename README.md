<div align="center">

# Vimal Raj
### Offensive Security Professional · OSCP+ Certified · Chennai, India

[![LinkedIn](https://img.shields.io/badge/LinkedIn-vimalraj--sec-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vimalraj-sec)
[![Email](https://img.shields.io/badge/Email-vimalrajm.sec%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:vimalrajm.sec@gmail.com)
[![Open to Work](https://img.shields.io/badge/Status-Open%20to%20Work-22c55e?style=flat)](mailto:vimalrajm.sec@gmail.com)

</div>

## 👋 Who I Am

I'm an offensive security professional based in Chennai, India, specialising in penetration testing, Active Directory attacks, web application security, and privilege escalation.

I started my career in information security in 2017 at Iopex Technologies, then moved to Infosys Ltd. In 2019, a serious family medical crisis required me to step away from my career to become the primary caregiver and take over running our family business.

I never let go of cybersecurity. While managing the business and family responsibilities, I kept studying — methodically and consistently. 

I saved money specifically to self-fund my OSCP+ preparation, built 2,600+ structured personal notes, completed 80+ full machine exploitation chains across OffSec Proving Grounds and TryHackMe, and passed the OSCP+ examination in November 2025.
That certification cost me real sacrifice to earn. Which is exactly why I value it.

I'm not a career changer. I'm a security professional who faced a hard chapter, never walked away from the field, and came back with proof.

> 💼 **Actively seeking Penetration Tester / Red Team roles — open to Chennai, remote, and EU relocation.**


## 🏆 Certifications

| Certification | Issuer | Year |
|---|---|---|
| **OSCP+** — Offensive Security Certified Professional Plus | OffSec | Nov 2025 |
| **ECSA v9** — EC-Council Certified Security Analyst | EC-Council | 2018 |


## 💼 Professional Background

| Period | Role | Organisation |
|---|---|---|
| Jul 2017 – Aug 2018 | Trainee Information Security Specialist | **Iopex Technologies** |
| Sep 2018 – Mar 2019 | Information Security Engineer | **Infosys Ltd** |
| Apr 2019 – Oct 2025 | Independent Security Research & Professional Development | Self-directed |

**During the independent research period:**
- Completed **80+ full machine exploitation chains** across OffSec Proving Grounds and TryHackMe — each documented end-to-end
- Compiled **2,600+ structured personal notes** into a public penetration testing reference across 12 attack categories
- Earned **OSCP+** — a 24-hour hands-on practical examination with no multiple-choice elements and no partial credit


## 📂 Featured Repositories

### 🔴 [penetration-testing-writeups](https://github.com/vimalraj-sec/penetration-testing-writeups)

**80+ OSCP-style machine writeups** — full exploitation chains from enumeration to root/SYSTEM proof.

| Platform | Category | Machines |
|---|---|---|
| TryHackMe | Active Directory | 5 |
| TryHackMe | Windows | 12 |
| TryHackMe | Linux | 17 |
| OffSec Proving Grounds | Play | 9 |
| OffSec Proving Grounds | Practice | 34+ |

Every writeup follows a strict methodology:

```
Enumeration → Service Analysis → Initial Access → Privilege Escalation → Proof
```

---

### 📘 [penetration-testing-cheatsheet-offsec](https://github.com/vimalraj-sec/penetration-testing-cheatsheet-offsec)

**A complete offensive security reference** — compiled from 2,600+ personal notes during OSCP preparation. Structured for real engagement use, not just exam revision.

| # | Section | Coverage |
|---|---|---|
| 00 | 🐚 Shells & File Transfer | Reverse shells, shell upgrades, Linux/Windows file transfer |
| 01 | 🔍 Reconnaissance | Nmap, Rustscan, web fingerprinting, environment setup |
| 02 | 🔌 Port Enumeration | Every port 21 → 27017 with attack commands |
| 03 | 🌐 Web Attacks | SQLi, LFI, SSTI, file upload bypass, CMS, XSS, RFI |
| 04 | 🪟 Windows Enumeration | Post-shell enum, credential harvesting, quick wins |
| 05 | 🐧 Linux Enumeration | System, users, network, process, file enumeration |
| 06 | ⬆️ Windows PrivEsc | Services, registry, tokens, UAC bypass, Mimikatz |
| 07 | ⬆️ Linux PrivEsc | SUID, sudo, cron, Docker, UDF, wildcard abuse |
| 08 | 🏢 Active Directory | AS-REP roasting, Kerberoasting, BloodHound, ADCS, PTH |
| 09 | 🔀 Pivoting | Ligolo-ng, Chisel, SSH tunnels, netsh port forwarding |
| 10 | 🛠️ Tools Reference | Hydra, ffuf, sqlmap, hashcat, msfvenom, netexec |
| 11 | ✅ Exam Checklists | Initial access, web, Windows/Linux privesc, AD attack chains |

---

## 🛠️ Technical Skills

**Exploitation & Enumeration**
`Nmap` `Rustscan` `Burp Suite` `ffuf` `Gobuster` `Feroxbuster` `Metasploit` `msfvenom`

**Active Directory**
`BloodHound` `Impacket` `Netexec` `Rubeus` `Mimikatz` `Evil-WinRM`

**Privilege Escalation**
`WinPEAS` `LinPEAS` `PEASS-ng` `GTFOBins` `LOLBAS`

**Web Application Security**
`sqlmap` `SQLi` `LFI/RFI` `SSTI` `File Upload Bypass` `OWASP Top 10`

**Pivoting & Tunnelling**
`Ligolo-ng` `Chisel` `SSH Port Forwarding` `netsh`

**Password Attacks**
`Hashcat` `John the Ripper` `Hydra` `CrackMapExec`

**Scripting**
`Python` `Bash` `PowerShell`

**Platforms**
`Kali Linux` `OffSec Proving Grounds` `TryHackMe`

---

## 🧠 Attack Methodology

```
TARGET
  │
  ├─ 01. RECON ──────────── nmap / rustscan → open ports + service versions
  │
  ├─ 02. ENUMERATE SERVICES
  │      ├─ SMB 445 ──────── null session → shares → RID brute → hashes
  │      ├─ HTTP 80/443 ─── whatweb → dir bust → app fingerprint
  │      ├─ SSH 22 ─────────  key enum / brute
  │      ├─ MSSQL 1433 ───── xp_cmdshell
  │      ├─ NFS 2049 ──────── showmount → no_root_squash
  │      ├─ LDAP 389 ──────── anonymous dump → users
  │      └─ SNMP 161 ──────── community string → info leak
  │
  ├─ 03. WEB ATTACKS (if HTTP)
  │      ├─ Dir bust → ffuf / gobuster / feroxbuster
  │      ├─ SQLi → sqlmap / manual
  │      ├─ LFI → log poisoning / php wrappers
  │      ├─ File upload bypass → webshell
  │      ├─ SSTI → RCE
  │      └─ CMS → wpscan / joomscan / droopescan
  │
  ├─ 04. POST-EXPLOITATION
  │      ├─ [Linux]   linpeas → sudo -l → SUID → cron → writable files → ROOT
  │      ├─ [Windows] winpeas → whoami /priv → services → SeImpersonate → SYSTEM
  │      └─ [AD]      BloodHound → Kerberoast / AS-REP → ADCS → PTH → Domain Admin
  │
  └─ 05. PIVOT (if multi-network)
         └─ Ligolo-ng → new subnet → repeat from step 01
```

---

## 📬 Connect

I'm actively looking for **Penetration Tester / Red Team** roles in Chennai or remote, and open to EU relocation. If you're a recruiter or hiring manager, feel free to reach out.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-vimalraj--sec-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vimalraj-sec)
[![Email](https://img.shields.io/badge/Email-vimalrajm.sec%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:vimalrajm.sec@gmail.com)

---

<div align="center">

*⚠️ All content in these repositories is for authorised security testing and educational purposes only.*

</div>
