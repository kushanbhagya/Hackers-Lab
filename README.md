
<div align="center">

```
██╗  ██╗ █████╗  ██████╗██╗  ██╗███████╗██████╗ ███████╗    ██╗      █████╗ ██████╗
██║  ██║██╔══██╗██╔════╝██║ ██╔╝██╔════╝██╔══██╗██╔════╝    ██║     ██╔══██╗██╔══██╗
███████║███████║██║     █████╔╝ █████╗  ██████╔╝███████╗    ██║     ███████║██████╔╝
██╔══██║██╔══██║██║     ██╔═██╗ ██╔══╝  ██╔══██╗╚════██║    ██║     ██╔══██║██╔══██╗
██║  ██║██║  ██║╚██████╗██║  ██╗███████╗██║  ██║███████║    ███████╗██║  ██║██████╔╝
╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚══════╝    ╚══════╝╚═╝  ╚═╝╚═════╝
```

### `⚔️ Offensive Security · Ethical Hacking · Real-World Attack Simulations`

<br>

![Last Updated](https://img.shields.io/badge/Last_Updated-2025-red?style=flat-square&logo=github)
![Labs](https://img.shields.io/badge/Labs-16_Planned-critical?style=flat-square&logo=gnubash)
![Status](https://img.shields.io/badge/Status-In_Progress-orange?style=flat-square&logo=statuspage)
![License](https://img.shields.io/badge/License-Educational_Only-blue?style=flat-square&logo=openssl)
![Platform](https://img.shields.io/badge/Platform-Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)

<br>

> *"To defend a system, you must first understand how to break it."*

</div>

---

## `> whoami`

This repository documents my hands-on journey through offensive security — practicing real-world attack techniques, exploitation methods, and system compromise simulations in a **controlled lab environment**.

Each lab is a battle fought, a skill earned.

---

## `> cat objectives.txt`

```
[*] Understand how real-world cyber attacks are executed
[*] Gain hands-on exploitation experience across multiple vectors
[*] Learn attacker methodologies: initial access → escalation → persistence
[*] Build a professional cybersecurity portfolio through practical work
[*] Bridge the gap between theory and real-world security scenarios
```

---

## `> ls skills/`

| Domain | Techniques |
|---|---|
| 🌐 **Network Exploitation** | Port scanning, service enumeration, banner grabbing |
| 💉 **Web Application Attacks** | SQLi, XSS, file upload abuse, directory brute-force |
| 🐚 **Reverse Shells & Access** | Netcat shells, TTY upgrades, web shells |
| 🔺 **Privilege Escalation** | Sudo misconfigs, SUID binaries, cron job abuse |
| 🔍 **Enumeration** | LinPEAS, manual recon, service fingerprinting |
| 🔑 **Password Attacks** | Hash cracking with John the Ripper & Hashcat |
| 👣 **Persistence** | Backdoors, startup manipulation |
| 🎯 **Red Team Methodology** | Full attack chain simulation |

---

## `> nmap --tools`

<div align="center">

![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-0E83CD?style=for-the-badge&logo=gnubash&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white)
![Netcat](https://img.shields.io/badge/Netcat-000000?style=for-the-badge&logo=gnubash&logoColor=white)
![Hashcat](https://img.shields.io/badge/Hashcat-FF0000?style=for-the-badge&logo=hashnode&logoColor=white)
![John](https://img.shields.io/badge/John_the_Ripper-CC0000?style=for-the-badge&logo=gnubash&logoColor=white)
![Gobuster](https://img.shields.io/badge/Gobuster-00AA00?style=for-the-badge&logo=gnubash&logoColor=white)
![DVWA](https://img.shields.io/badge/DVWA-8B0000?style=for-the-badge&logo=php&logoColor=white)

</div>

---

## `> tree lab-structure/`

```
lab-xx-topic/
│
├── 📄 README.md          ← Objective, Setup, Attack Steps, Results
├── 📁 screenshots/       ← Visual proof of exploitation
└── 📝 notes.md           ← Additional findings & references
```

Each lab contains:
- **Objective** — What we're exploiting and why
- **Setup** — Environment configuration
- **Attack Steps** — Step-by-step execution
- **Explanation** — How and why the attack works
- **Results** — Outcome and evidence
- **Key Learnings** — Takeaways and defense insights

---

## `> cat roadmap.md`

### 🔰 Phase 1 — Initial Access & Exploitation

| # | Lab | Status |
|---|-----|--------|
| 01 | 🐚 Reverse Shell (Netcat) | ⏳ Pending |
| 02 | 💉 Web Exploitation – SQL Injection | ⏳ Pending |
| 03 | 🎭 Cross-Site Scripting (XSS) | ⏳ Pending |
| 04 | 📂 Directory Bruteforce (Gobuster) | ⏳ Pending |

### ⚔️ Phase 2 — Advanced Access Techniques

| # | Lab | Status |
|---|-----|--------|
| 05 | 📤 File Upload Vulnerabilities | ⏳ Pending |
| 06 | 🌐 Web Shell Injection | ⏳ Pending |
| 07 | 🔧 Reverse Shell Upgrade (TTY Shell) | ⏳ Pending |
| 08 | 🔑 Password Cracking (John / Hashcat) | ⏳ Pending |

### 🔥 Phase 3 — Privilege Escalation

| # | Lab | Status |
|---|-----|--------|
| 09 | 🔍 Linux Enumeration (linPEAS) | ⏳ Pending |
| 10 | ⚙️ Sudo Misconfiguration Exploitation | ⏳ Pending |
| 11 | 🔏 SUID Binary Exploitation | ⏳ Pending |
| 12 | ⏰ Cron Job Exploitation | ⏳ Pending |

### 🚀 Phase 4 — Post-Exploitation & Real Scenarios

| # | Lab | Status |
|---|-----|--------|
| 13 | 🔗 Full Attack Chain (Web → Shell → Root) | ⏳ Pending |
| 14 | 👣 Persistence Techniques | ⏳ Pending |
| 15 | 💥 Metasploit Exploitation | ⏳ Pending |
| 16 | 🎮 Multi-Step Attack Simulation | ⏳ Pending |

### 🛡️ Extension — Blue Team Integration *(Optional)*

```
[+] Detecting attacks using system logs
[+] Monitoring suspicious network activity
[+] Basic incident response practices
```

---

## `> cat progress.log`

```
Total Labs Planned   : 16
Labs Completed       : 0
Labs In Progress     : 0
Completion           : [░░░░░░░░░░░░░░░░░░░░] 0%
```

> Progress bar updates as labs are completed. Follow to stay notified.

---

## `> cat disclaimer.txt`

```
╔══════════════════════════════════════════════════════════╗
║  ⚠️  EDUCATIONAL USE ONLY                                 ║
║                                                           ║
║  All techniques in this repository are performed          ║
║  exclusively in controlled, isolated lab environments.    ║
║                                                           ║
║  Unauthorized use of these techniques against systems     ║
║  without explicit permission is ILLEGAL.                  ║
║                                                           ║
║  The author holds no responsibility for misuse.           ║
╚══════════════════════════════════════════════════════════╝
```

---

## `> whoami --author`

<div align="center">

### **Kushan Bhagya**
*Cybersecurity Enthusiast | Ethical Hacking Learner*

[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github)](https://github.com/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/)

<br>

*Building skills. Breaking things. Doing it ethically.*

---

`[★ Star this repo if you find it useful]`

</div>
