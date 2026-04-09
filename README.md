<div align="center">

# Vimal Raj M
### Offensive Security Professional · OSCP+ Certified · Chennai, India

[![LinkedIn](https://img.shields.io/badge/LinkedIn-vimalraj--sec-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vimalraj-sec)
[![Email](https://img.shields.io/badge/Email-vimalrajm.sec%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:vimalrajm.sec@gmail.com)
[![Open to Work](https://img.shields.io/badge/Status-Open%20to%20Work-22c55e?style=flat)](mailto:vimalrajm.sec@gmail.com)

</div>

## 👋 Who I Am

I'm an offensive security professional based in Chennai, India, specialising in penetration testing, Active Directory attacks, web application security, and privilege escalation.

I started my career in information security in 2017 at Iopex Technologies, then moved to Infosys Ltd. In 2019, a serious family medical crisis required me to step away from my career to become the primary caregiver and take over running our family business.

I never let go of cybersecurity. While managing the business and family responsibilities, I kept studying — methodically and consistently.

I saved money specifically to self-fund my OSCP+ preparation, built 2,600+ structured personal notes, completed 80+ full machine exploitation chains across OffSec Proving Grounds and TryHackMe, and passed the OSCP+ examination in November 2025. That certification cost me real sacrifice to earn. Which is exactly why I value it.

I'm not a career changer. I'm a security professional who faced a hard chapter, never walked away from the field, and came back with proof.

> 💼 **Actively seeking Penetration Tester / Red Team roles — open to Chennai, remote, and EU relocation.**


## 🏆 Certifications

| Certification | Issuer | Year |
|---|---|---|
| **OSCP+** — Offensive Security Certified Professional Plus | OffSec | Nov 2025 |


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

### 🔴 [active-directory-pentesting](https://github.com/vimalraj-sec/active-directory-pentesting)

**Complete Active Directory penetration testing reference** — full attack chain from zero credentials to Domain Admin, built from real lab practice across HTB, TryHackMe, and a custom local AD lab.

| Phase | Coverage |
|---|---|
| 🔍 Recon | DC identification, port scanning, SMB fingerprinting |
| 🗂️ Domain Enumeration | Kerbrute, ldapdomaindump, RID brute, BloodHound — with and without creds |
| 🔑 Credential Attacks | AS-REP Roasting, Kerberoasting, Password Spray, Responder |
| 🔀 Lateral Movement | Pass-the-Hash, Overpass-the-Hash, evil-winrm, RDP, PSExec |
| ⬆️ Privilege Escalation | BloodHound paths, ACL abuse, ADCS / Certipy (ESC1/ESC4) |
| 👑 Domain Dominance | DCSync, Golden Ticket, Silver Ticket, NTDS dump |

**Also includes:**
- Machine writeups — HTB Forest, Active, Sauna · THM Attacktive Directory, Enterprise
- Custom Python scripts — BloodHound collector, safe password spray tool
- Full local lab setup — DC01 (Windows Server 2025) + MS01 + MS02 (Windows 11)
- MITRE ATT&CK mapped throughout


### 🌐 [web-app-pentesting](https://github.com/vimalraj-sec/web-app-pentesting)

**Complete web application penetration testing reference** — methodology-driven, aligned with OWASP Top 10:2025 including both new categories added this cycle.

| # | Section | Coverage |
|---|---|---|
| 00 | 🗺️ Methodology | Full engagement workflow — 6 phases, Burp setup, notes format |
| 01 | 🔍 Recon & Enumeration | Subdomain enum, dir busting, JS analysis, Nikto, Nuclei |
| 02 | 🔐 Authentication Testing | Brute force, MFA bypass, JWT attacks, session management |
| 03 | 🚪 Broken Access Control | IDOR, SSRF + cloud metadata, CORS, path traversal — A01:2025 |
| 04 | 💉 Injection Attacks | SQLi, CMDi, SSTI, XXE, LFI/RFI, NoSQLi — A04:2025 |
| 05 | 🖥️ XSS & Client-Side | Reflected, Stored, DOM XSS, CSRF, Clickjacking, Open Redirect |
| 06 | ⚙️ Security Misconfiguration | Headers, Spring Actuator, cloud storage, HTTP methods — A02:2025 |
| 07 | 🔒 Cryptographic Failures | Weak hashing, hardcoded secrets, insecure transmission |
| 08 | 🏗️ Insecure Design | Business logic flaws, race conditions, workflow bypass — A05:2025 |
| 09 | 📦 Software Supply Chain | Vulnerable components, exposed .git, SRI checks — A03:2025 NEW |
| 10 | ✅ Software & Data Integrity | Insecure deserialization — Java, PHP, Python pickle — A08:2025 |
| 11 | 📋 Logging & Alerting | Log testing, log injection, detection gap evidence — A09:2025 |
| 12 | ⚠️ Exceptional Conditions | Fail-open, verbose errors, ReDoS, resource exhaustion — A10:2025 NEW |
| 13 | 🔌 API Testing | BOLA, BFLA, mass assignment, GraphQL, rate limiting |
| 14 | 📁 File Upload Attacks | Extension bypass, polyglot, zip slip, SVG XXE, webshell |
| 15 | 🛠️ Tools & Wordlists | Burp, ffuf, sqlmap, nuclei, jwt_tool — all commands in one place |
| 16 | 📝 Report Templates | Finding format, CVSS vectors, severity justification guide |


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


### 📘 [pentest-cheatsheet](https://github.com/vimalraj-sec/pentest-cheatsheet)

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


## 🛠️ Technical Skills

**Exploitation & Enumeration**
`Nmap` `Rustscan` `Burp Suite` `ffuf` `Gobuster` `Feroxbuster` `Metasploit` `msfvenom`

**Active Directory**
`BloodHound` `Impacket` `Netexec` `Rubeus` `Mimikatz` `Evil-WinRM` `Certipy`

**Web Application Security**
`sqlmap` `SQLi` `SSTI` `XXE` `LFI/RFI` `File Upload Bypass` `JWT Attacks` `OWASP Top 10:2025`

**API Security**
`BOLA` `BFLA` `Mass Assignment` `GraphQL Testing` `REST API Testing`

**Privilege Escalation**
`WinPEAS` `LinPEAS` `GTFOBins` `LOLBAS`

**Pivoting & Tunnelling**
`Ligolo-ng` `Chisel` `SSH Port Forwarding` `netsh`

**Password Attacks**
`Hashcat` `John the Ripper` `Hydra` `CrackMapExec`

**Scripting**
`Python` `Bash` `PowerShell`

**Platforms**
`Kali Linux` `OffSec Proving Grounds` `TryHackMe` `HackTheBox`


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
  │      ├─ API → BOLA / BFLA / mass assignment
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


## 📬 Connect

I'm actively looking for **Penetration Tester / Red Team** roles in Chennai or remote, and open to EU relocation. If you're a recruiter or hiring manager, feel free to reach out.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-vimalraj--sec-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vimalraj-sec)
[![Email](https://img.shields.io/badge/Email-vimalrajm.sec%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:vimalrajm.sec@gmail.com)

---

<div align="center">

*⚠️ All content in these repositories is for authorised security testing and educational purposes only.*

</div>
