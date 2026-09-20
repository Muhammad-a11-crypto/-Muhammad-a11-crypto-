<div align="center">

<!-- ===================== INLINE NEON HACKER BANNER ===================== -->

<svg width="100%" viewBox="0 0 1400 430" xmlns="http://www.w3.org/2000/svg">

  <defs>

```
<linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
  <stop offset="0%" stop-color="#020202"/>
  <stop offset="55%" stop-color="#090000"/>
  <stop offset="100%" stop-color="#170000"/>
</linearGradient>

<linearGradient id="redGlow" x1="0%" x2="100%">
  <stop offset="0%" stop-color="#ff0000"/>
  <stop offset="50%" stop-color="#ff3030"/>
  <stop offset="100%" stop-color="#7a0000"/>
</linearGradient>

<filter id="glow">
  <feGaussianBlur stdDeviation="6" result="blur"/>
  <feMerge>
    <feMergeNode in="blur"/>
    <feMergeNode in="SourceGraphic"/>
  </feMerge>
</filter>

<filter id="smallGlow">
  <feGaussianBlur stdDeviation="2" result="blur"/>
  <feMerge>
    <feMergeNode in="blur"/>
    <feMergeNode in="SourceGraphic"/>
  </feMerge>
</filter>

<pattern id="grid" width="45" height="45" patternUnits="userSpaceOnUse">
  <path d="M45 0H0V45" fill="none" stroke="#ff0000" stroke-opacity=".08"/>
</pattern>

<linearGradient id="hood" x1="0" y1="0" x2="1" y2="1">
  <stop offset="0" stop-color="#181818"/>
  <stop offset=".5" stop-color="#050505"/>
  <stop offset="1" stop-color="#220000"/>
</linearGradient>
```

  </defs>

  <!-- BACKGROUND -->

  <rect width="1400" height="430" rx="18" fill="url(#bg)"/>
  <rect width="1400" height="430" rx="18" fill="url(#grid)"/>

  <!-- RED AMBIENT GLOW -->

  <circle cx="1120" cy="220" r="170" fill="#ff0000" opacity=".08" filter="url(#glow)">
    <animate attributeName="r" values="150;185;150" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values=".04;.12;.04" dur="3s" repeatCount="indefinite"/>
  </circle>

  <!-- TERMINAL LINES -->

  <g fill="#ff1a1a" opacity=".35" font-family="monospace" font-size="13">
    <text x="55" y="55">root@0xdzubair:~$ ./recon.sh</text>
    <text x="55" y="78">[+] initializing reconnaissance...</text>
    <text x="55" y="101">[+] targets discovered: ██████████</text>
    <text x="55" y="124">[+] attack_surface mapped</text>
    <text x="55" y="147">[+] looking for high-impact vulnerabilities...</text>
  </g>

  <!-- RANDOM CODE -->

  <g fill="#ff0000" opacity=".16" font-family="monospace" font-size="11">
    <text x="760" y="50">01010101 00110010</text>
    <text x="1080" y="78">0x4f 0x52 0x54 0x41</text>
    <text x="850" y="110">/api/v1/authentication</text>
    <text x="1180" y="145">0xdeadbeef</text>
    <text x="730" y="390">RECON :: ENUM :: EXPLOIT :: REPORT</text>
  </g>

  <!-- HOOD -->

<path d="
   M930 395
   C900 350 885 300 895 230
   C905 145 970 75 1060 70
   C1150 75 1215 145 1225 230
   C1235 300 1220 350 1190 395
   Z"
   fill="url(#hood)"
   stroke="#ff1010"
   stroke-width="3"
   filter="url(#smallGlow)"/>

  <!-- HOOD INNER SHADOW -->

  <ellipse cx="1060" cy="215" rx="125" ry="155" fill="#000000"/>

  <!-- MASKED FACE -->

<path d="
   M965 190
   Q1060 135 1155 190
   L1135 305
   Q1060 345 985 305
   Z"
   fill="#101010"
   stroke="#5e0000"
   stroke-width="3"/>

  <!-- MASK NEON LINES -->

<path d="M990 275 Q1060 305 1130 275" fill="none"
     stroke="#ff1515" stroke-width="4" filter="url(#smallGlow)"/>

<path d="M1005 295 Q1060 320 1115 295" fill="none"
     stroke="#8b0000" stroke-width="2"/>

  <!-- EYES -->

<path d="M985 218 Q1020 190 1050 218 Q1020 240 985 218Z"
     fill="#ff0000" filter="url(#glow)"> <animate attributeName="opacity" values="1;.25;1" dur="2.2s" repeatCount="indefinite"/> </path>

<path d="M1070 218 Q1100 190 1135 218 Q1100 240 1070 218Z"
     fill="#ff0000" filter="url(#glow)"> <animate attributeName="opacity" values=".25;1;.25" dur="2.2s" repeatCount="indefinite"/> </path>

  <!-- MASK DETAILS -->

<path d="M1045 250 L1060 260 L1075 250"
     fill="none" stroke="#ff2525" stroke-width="3"/>

  <!-- MOVING SCANLINE -->

  <rect x="760" y="0" width="5" height="430" fill="#ff0000" opacity=".25">
    <animate attributeName="x" from="700" to="1280" dur="4s" repeatCount="indefinite"/>
  </rect>

  <!-- LEFT TITLE -->

<text x="70" y="220"
     fill="#ffffff"
     font-family="monospace"
     font-size="58"
     font-weight="bold"
     filter="url(#smallGlow)">
0xdzubair </text>

<text x="74" y="258"
     fill="#ff1616"
     font-family="monospace"
     font-size="20"
     letter-spacing="5">
ANONYMOUS RED TEAM OPERATOR </text>

<text x="74" y="292"
     fill="#888888"
     font-family="monospace"
     font-size="15">
WEB PENTESTING • RCE • OSINT • RED TEAMING </text>

  <!-- COMMAND -->

<text x="74" y="340"
     fill="#ff1a1a"
     font-family="monospace"
     font-size="16">
root@0xdzubair:~$ <tspan fill="#ffffff">
hunt --target web --focus rce </tspan> </text>

  <!-- BOTTOM LINE -->

<line x1="70" y1="375" x2="1330" y2="375"
     stroke="#ff0000" stroke-width="1" opacity=".6"/>

<text x="70" y="402"
     fill="#666666"
     font-family="monospace"
     font-size="12">
[ RECON → ENUMERATION → EXPLOITATION → VALIDATION → REPORT ] </text>

<text x="1160" y="402"
     fill="#ff1616"
     font-family="monospace"
     font-size="12">
STATUS: ONLINE </text>

</svg>

<br>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=21&pause=900&color=FF1A1A&center=true&vCenter=true&width=900&lines=Anonymous+by+design.;Breaking+systems+to+understand+them.;Web+Pentesting+%7C+Red+Teaming+%7C+OSINT;Hunting+for+high-impact+web+vulnerabilities.;Recon+%E2%86%92+Exploit+%E2%86%92+Report+%E2%86%92+Repeat" alt="Typing SVG"/>

<br>

<img src="https://img.shields.io/badge/STATUS-ACTIVE-ff1a1a?style=for-the-badge&labelColor=050505">
<img src="https://img.shields.io/badge/ROLE-RED%20TEAM%20OPERATOR-ff1a1a?style=for-the-badge&labelColor=050505">
<img src="https://img.shields.io/badge/FOCUS-WEB%20%7C%20RCE%20%7C%20OSINT-ff1a1a?style=for-the-badge&labelColor=050505">
<img src="https://img.shields.io/badge/MODE-COVERT-ff1a1a?style=for-the-badge&labelColor=050505">

<br><br>

<a href="https://medium.com/@oxdzubair">
<img src="https://img.shields.io/badge/MEDIUM-WRITEUPS-000000?style=for-the-badge&logo=medium&logoColor=white">
</a>

<a href="https://www.linkedin.com/in/muhammad-zubair-aa592430b/">
<img src="https://img.shields.io/badge/LINKEDIN-CONNECT-000000?style=for-the-badge&logo=linkedin&logoColor=ff1a1a">
</a>

</div>

---

## `>_ MISSION BRIEF`

```bash
root@0xdzubair:~$ cat mission.txt

[+] Identity      : Anonymous Red Team Operator
[+] Primary Focus : Web Application Security
[+] Objective     : Find → Understand → Validate → Report
[+] Specialty     : RCE & High-Impact Web Vulnerabilities
[+] Secondary     : OSINT & Reconnaissance

I break things to understand how they're built.

Training to become a professional Red Teamer and Web Pentester,
with a primary focus on web vulnerabilities that can lead to
Remote Code Execution.

Recon is not a phase.
Recon is the operation.
```

---

## `// CURRENT OPERATIONS`

```text
┌─────────────────────────────────────────────────────────┐
│                                                         │
│  [01] WEB PENTESTING                                    │
│       └── RCE • SSTI • SQLi • Auth • Access Control    │
│                                                         │
│  [02] RED TEAMING                                       │
│       └── AD • PrivEsc • Lateral Movement • Pivoting   │
│                                                         │
│  [03] OSINT                                             │
│       └── Recon • GEOINT • Digital Footprint Analysis  │
│                                                         │
│  [04] AUTOMATION                                        │
│       └── Python • Recon Frameworks • CLI Tooling      │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

---

# `🏴 CERTIFICATIONS`

* 🎖️ **Certified Red Team Analyst (CRTA)** — CyberWarFare Labs
* 🎖️ **Certified Offensive OSINT Operator (CO3)** — CyberWarFare Labs
* 🎖️ **OSINT Level 1** — CyberWarFare Labs
* 🎖️ **F1NDX — OSINT Level 2 (Investigations Certification)**
* 🎖️ **F1NDX — OSINT Level 3 (Advanced Techniques)**
* 🎖️ **Certified Cybersecurity Foundations (CORE)**
* 🎖️ **Certified LLM Security Professional (CLLMSP)** — Hackviser
* 🎖️ **Red Team Leaders**
* 🎖️ **Introduction to Critical Infrastructure Protection (ICIP)**
* 🎖️ **Certified Online Fraud Prevention Specialist (COFPS)** — OPSWAT Academy
* 🎖️ **Certified Red Team Analyst** — Hack & Fix

---

# `⚔️ RED TEAMING & PENETRATION TESTING`

### Active Directory

`AS-REP Roasting` `Kerberoasting` `DCSync`

`Domain Enumeration` `Credential Access` `Lateral Movement`

`Domain Dominance` `Post-Exploitation`

### Privilege Escalation

`Windows PrivEsc` `Linux PrivEsc` `SUID Abuse`

`Service Abuse` `CVE Exploitation` `PrintNightmare`

### Web Application Security

`SQL Injection` `SSTI / Jinja2` `Authentication`

`Authorization / IDOR` `File Upload` `Command Injection`

`Server-Side Vulnerabilities` `RCE Research`

`PortSwigger Labs` `DVWA`

---

# `🔍 OSINT & RECON`

```text
Google Dorking
Subdomain Enumeration
DNS Reconnaissance
GEOINT
Digital Footprint Analysis
Phone Number OSINT
Steganography
EXIF Analysis
Satellite / Aviation OSINT
PIE Framework
Berkeley Protocol
CTF Investigations
```

---

# `🧰 TOOLKIT`

### Offensive Security

`Metasploit` `Mimikatz` `Impacket` `Evil-WinRM`

`Nmap` `Proxychains` `msfvenom` `Burp Suite`

`Wireshark` `DVWA`

### Development & Automation

`Python` `Node.js` `ReportLab` `docx`

### Environments

`Kali Linux` `Windows` `Active Directory`

---

# `☠️ PERSONAL PROJECTS`

| Project                        | Description                                                       |
| ------------------------------ | ----------------------------------------------------------------- |
| 🩸 **Wraith**                  | CLI Python MITRE ATT&CK simulation framework for web applications |
| 🩸 **SubReconX**               | Full-featured subdomain enumeration & reconnaissance framework    |
| 🩸 **ReconDash**               | Chained reconnaissance automation tool                            |
| 🩸 **Cyber Defense Dashboard** | SOC simulation and monitoring platform                            |

---

# `🧠 DEVELOPMENT & AUTOMATION`

```python
class Operator:

    identity = "0xdzubair"

    focus = [
        "Web Pentesting",
        "RCE Research",
        "Red Teaming",
        "OSINT"
    ]

    workflow = [
        "Recon",
        "Enumerate",
        "Exploit",
        "Validate",
        "Report"
    ]

    mindset = "Understand the system."
```

---

# `📡 OPERATIONAL PHILOSOPHY`

<div align="center">

```text
                 ┌──────────┐
                 │   RECON  │
                 └────┬─────┘
                      │
                      ▼
              ┌───────────────┐
              │ ENUMERATION   │
              └───────┬───────┘
                      │
                      ▼
              ┌───────────────┐
              │ EXPLOITATION  │
              └───────┬───────┘
                      │
                      ▼
              ┌───────────────┐
              │  VALIDATION   │
              └───────┬───────┘
                      │
                      ▼
              ┌───────────────┐
              │    REPORT     │
              └───────┬───────┘
                      │
                      └──────────► REPEAT
```

> **"Access is temporary. Understanding is permanent."**

</div>

---

# `🌐 INTERESTS`

* 🩸 Web Pentesting
* 💀 RCE Research
* ⚔️ Red Team Operations
* 🔍 OSINT
* 📡 UAV / RF Security
* 🛰️ Satellite & Aviation OSINT
* 🐍 Security Automation

---

# `📊 OPERATIONAL STATS`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Muhammad-a11-crypto&show_icons=true&hide_border=true&count_private=true&title_color=ff1a1a&icon_color=ff1a1a&text_color=ffffff&bg_color=0d0d0d" width="48%" alt="GitHub Stats"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Muhammad-a11-crypto&hide_border=true&background=0d0d0d&ring=ff1a1a&fire=ff1a1a&currStreakLabel=ff1a1a&sideLabels=ffffff&currStreakNum=ffffff&sideNums=ffffff&dates=ffffff" width="48%" alt="GitHub Streak"/>

</div>

---

<div align="center">

```text
╔══════════════════════════════════════════════════════╗
║                                                      ║
║       0xdzubair // RED TEAM OPERATOR                ║
║                                                      ║
║       RECON • EXPLOIT • UNDERSTAND • REPORT          ║
║                                                      ║
╚══════════════════════════════════════════════════════╝
```

<a href="https://medium.com/@oxdzubair">
<img src="https://img.shields.io/badge/READ%20MY%20WRITEUPS-MEDIUM-ff1a1a?style=for-the-badge&logo=medium&logoColor=white&labelColor=050505">
</a>

<br><br>

<img src="https://komarev.com/ghpvc/?username=Muhammad-a11-crypto&style=for-the-badge&color=ff1a1a&labelColor=000000" alt="Profile Views"/>

<br><br>

`[ SYSTEM STATUS: ONLINE ]`

</div>
