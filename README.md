<div align="center">

# Vimal Raj
### Offensive Security Professional · OSCP+ Certified · Chennai, India

[![LinkedIn](https://img.shields.io/badge/LinkedIn-vimalraj--sec-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vimalraj-sec)
[![Email](https://img.shields.io/badge/Email-vimalrajm.sec%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vimalrajm.sec@gmail.com)
[![Open to Work](https://img.shields.io/badge/Status-Open%20to%20Work-22c55e?style=for-the-badge)](mailto:vimalrajm.sec@gmail.com)

</div>

## 👋 Who I Am

I'm an offensive security professional based in **Chennai, India**, specializing in penetration testing, Active Directory attacks, and web application security.

I started my career in Information Security in 2017 at Iopex Technologies and later worked at Infosys Ltd.

From 2019 to 2025, I stepped away from the workforce to manage a serious family medical situation while also running our family business. During this time, I stayed committed to cybersecurity — saving money, self-funding my learning, and continuously building my skills.

I created 2,600+ structured notes, completed 80+ full machine exploitation chains, and earned the OSCP+ certification in November 2025.

> 💼 **Actively seeking VAPT / Penetration Tester roles — open to Chennai-based and remote opportunities.**

---

## 🏆 Certifications

| Certification | Issuer | Year |
|---|---|---|
| **OSCP+** — Offensive Security Certified Professional | OffSec | Nov 2025 |
| **ECSA v9** — EC-Council Certified Security Analyst | EC-Council | 2018 |

---

## 💼 Professional Background

| Period | Role | Company |
|---|---|---|
| Jul 2017 – Aug 2018 | Trainee Information Security Specialist | **Iopex Technologies** |
| Sep 2018 – Mar 2019 | Information Security Engineer | **Infosys Ltd** |
| Apr 2019 – Oct 2025 | Independent Security Researcher *(career break — family medical crisis)* | Self-directed |
| Nov 2025 – Present | OSCP+ Certified · Actively seeking roles | — |

During my independent research period, I:
- Completed **80+ full machine exploitation chains** across OffSec Proving Grounds and TryHackMe
- Compiled **2,600+ structured notes** into a public penetration testing cheatsheet
- Earned the **OSCP+** certification — one of the most respected hands-on offensive security credentials in the industry

---

## 📂 Featured Work

### 🔴 [penetration-testing-writeups](https://github.com/vimalraj-sec/penetration-testing-writeups)
> 80+ OSCP-style machine writeups — full exploitation chains from enumeration to root/SYSTEM proof.

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

### 📘 [pentest-cheatsheet](https://github.com/vimalraj-sec/pentest-cheatsheet)
> A complete offensive security reference — compiled from 2,600+ personal notes during OSCP preparation.

| # | Section | What's Inside |
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

**Active Directory Attacks**
`BloodHound` `Impacket` `Netexec` `Rubeus` `Mimikatz` `Evil-WinRM`

**Privilege Escalation**
`WinPEAS` `LinPEAS` `GTFOBins` `LOLBAS`

**Web Application Security**
`sqlmap` `SQLi` `LFI/RFI` `SSTI` `File Upload Bypass` `OWASP Top 10`

**Pivoting & Tunneling**
`Ligolo-ng` `Chisel` `SSH Port Forwarding` `netsh`

**Password Attacks**
`Hashcat` `John the Ripper` `Hydra` `CrackMapExec`

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

## 📬 Let's Connect

I'm actively looking for **VAPT / Penetration Tester** roles in Chennai or remote. If you're a recruiter or hiring manager, feel free to reach out.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-vimalraj--sec-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/vimalraj-sec)
[![Email](https://img.shields.io/badge/Email-vimalrajm.sec%40gmail.com-D14836?style=flat&logo=gmail)](mailto:vimalrajm.sec@gmail.com)

---

<div align="center">

*⚠️ All content in these repositories is for authorized security testing and educational purposes only.*

</div>
