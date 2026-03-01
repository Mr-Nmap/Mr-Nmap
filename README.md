# Hi, ich bin Alex 👋

**Cyber Security Professional | SOC Analyst | Ethical Hacker in Training**

Ich bin ein leidenschaftlicher IT-Security-Spezialist mit praktischer Erfahrung in SIEM-Betrieb, Incident Response, Log-Analyse, digitaler Forensik und Penetration Testing. Mein Ansatz: **wie ein Angreifer denken, wie ein Defender handeln.**

---

## 🛡️ Über mich

- 🔐 **Cyber Security Expert** (MindRefined GmbH – Abschluss 2026)
- 📜 **CompTIA Security+, Network+, Linux+, A+** – alle im ersten Versuch bestanden
- 📜 **ISO/IEC 27001:2022 Lead Auditor** (DNV, 2024)
- 💼 Berufshintergrund: ISMS Junior Consultant, Senior Consultant IT-Security & Risk
- 🏠 Homelab-Enthusiast: Red/Blue/Purple Team Simulationen, ELK Stack SIEM, SOC-Labs
- 🎯 Aktuell in Vorbereitung auf: **CompTIA PenTest+** (2026)
- 🌍 Deutsch (Muttersprache) · Englisch (C1 / IELTS Band 7)

---

## 🔧 Skills

### Security Operations & Detection
![SIEM](https://img.shields.io/badge/SIEM-Wazuh%20%7C%20ELK%20Stack%20%7C%20Splunk-922b21?style=flat-square)
![SOC](https://img.shields.io/badge/SOC-Incident%20Response%20%7C%20Alert%20Triage%20%7C%20Threat%20Hunting-1a5276?style=flat-square)
![MITRE](https://img.shields.io/badge/Framework-MITRE%20ATT%26CK%20%7C%20Kill%20Chain%20%7C%20NIST-196f3d?style=flat-square)

### Network & Analysis
![Network](https://img.shields.io/badge/Network-Wireshark%20%7C%20tcpdump%20%7C%20Nmap%20%7C%20Snort-1a5276?style=flat-square)
![Forensics](https://img.shields.io/badge/Forensik-Sleuth%20Kit%20%7C%20Autopsy%20%7C%20TestDisk-6c3483?style=flat-square)
![Malware](https://img.shields.io/badge/Malware-Joe%20Sandbox%20%7C%20VirusTotal%20%7C%20IoC%20Analysis-922b21?style=flat-square)

### Penetration Testing & Vulnerability
![Pentest](https://img.shields.io/badge/Pentest-Metasploit%20%7C%20Hydra%20%7C%20Burp%20Suite%20%7C%20SQLi-922b21?style=flat-square)
![VulnMgmt](https://img.shields.io/badge/Vuln%20Mgmt-Nessus%20%7C%20OpenVAS%20%7C%20CVSS%20%7C%20CVE-196f3d?style=flat-square)

### Scripting & Automation
![Python](https://img.shields.io/badge/Python-3.x-1a5276?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-Shell%20Scripting-196f3d?style=flat-square&logo=gnubash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-Automation-1a5276?style=flat-square&logo=powershell&logoColor=white)

### OS & Infrastructure
![OS](https://img.shields.io/badge/OS-Windows%20%7C%20Linux%20%7C%20Kali%20%7C%20Ubuntu-333?style=flat-square)
![AD](https://img.shields.io/badge/AD-Active%20Directory%20%7C%20GPO%20%7C%20Group%20Policy-1a5276?style=flat-square)
![Docker](https://img.shields.io/badge/Infrastructure-Docker%20%7C%20Hyper--V%20%7C%20VirtualBox-196f3d?style=flat-square)

---

## 🏗️ Projekte & Homelabs

### 🔴🔵 [Dual HomeLab Agent – Red/Blue/Purple Team Framework](https://github.com/Mr-Nmap/dual-homelab-agent)
> Python-basiertes Sicherheits-Framework mit offensiven und defensiven Komponenten

- **Red Team:** TCP-Port-Scanner mit IP-Range-Validierung, Banner Grabbing, JSON-Logging
- **Blue Team:** Verhaltensbasierte Angriffserkennung – 100% Detektionsrate bei Reconnaissance
- **Purple Team:** Korrelations-Engine verbindet Angriffs-Logs mit Security-Alerts, Confidence-Scores, Gap-Analyse
- **MITRE ATT&CK aligned:** Security+, PenTest+, Network+ Zertifizierungsziele

`Python` `Socket` `psutil` `MITRE ATT&CK` `Security Automation`

---

### 📊 [Blue/Red Team SIEM Demo System](https://github.com/Mr-Nmap/dual-homelab-agent/tree/main/WormGPT)
> Vollständiges SIEM mit Web-Dashboard, speziell für SOC-Interview-Demonstrationen

- 5 Detection Rules: Brute Force, Port Scan, Malicious IP (Threat Intel), Data Exfiltration, Web Attacks (SQLi/Path Traversal)
- Web-Dashboard (Flask) mit Auto-Refresh, Alert-Timeline, RESTful API (`/api/stats`, `/api/alerts`)
- MITRE ATT&CK Mapping: T1110, T1046, T1048, T1190
- JSON/CSV-Export für SIEM-Integration und Compliance

`Python` `Flask` `SQLite` `Pandas` `Matplotlib` `Threat Intelligence`

---

### 🛡️ [Home SOC Lab – ELK Stack SIEM](https://github.com/Mr-Nmap/dual-homelab-agent/tree/main/elk-soc-lab)
> Enterprise-SIEM-Simulation mit vollständiger Log-Pipeline in Docker

- **Log-Pipeline:** Filebeat → Logstash (Grok-Parsing) → Elasticsearch → Kibana
- **Attack Scenarios:** SSH Brute-Force mit Hydra, KQL-Detection, Real-time Alerting
- **MITRE ATT&CK:** T1110 (Brute Force), T1087 (Account Discovery), T1078 (Valid Accounts)
- Kibana Dashboards: Line Charts, Data Tables, Top Source IPs

`Elasticsearch` `Logstash` `Kibana` `Filebeat` `Docker` `KQL` `Hydra`

---

### 🔓 [BruteForce Attack Simulation Lab](https://github.com/Mr-Nmap/dual-homelab-agent/tree/main/bruteforce-lab)
> Kontrolliertes Labor für Brute-Force-Angriffe und Detection-Mechanismen

- Angreifer-Komponente gegen SSH, FTP, HTTP mit Wordlist-Support
- Zielserver mit Live-Monitoring-Dashboard & automatischer IP-Blockierung nach 5 Fehlversuchen
- Forensische Log-Analyse und JSON-Report-Export
- MITRE ATT&CK T1110 – Credential Access

`Python` `Flask` `SSH` `HTTP` `Forensics` `JSON Reporting`

---

### 🔐 [Ransomware Simulation Lab](https://github.com/Mr-Nmap/dual-homelab-agent/tree/main/ransomware-lab)
> AES-256-Verschlüsselungssimulation für Incident-Response-Training

- AES-256-CBC Verschlüsselung mit zufälligem IV pro Datei, PKCS7-Padding
- Notfall-Stopp (2x ESC), vollständiges Forensik-Audit-Log
- Decryptor-Tool mit Integritätsprüfung
- MITRE ATT&CK T1486 – Data Encrypted for Impact

`Python` `AES-256-CBC` `Cryptography` `Forensic Logging`

---

### 🔑 [SSO USB-Key Authentication Lab](https://github.com/Mr-Nmap/dual-homelab-agent/tree/main/sso-usb-lab)
> Enterprise-SSO mit USB-Key-Authentifizierung (Yubikey-ähnlich)

- Zentraler Auth-Server mit Multi-Faktor-Auth: Passwort + USB-Token + TOTP
- Multi-VM-Support: Kali Linux (PAM), Windows (Credential Provider), Unraid NAS
- Echtzeit-Monitoring-Dashboard für Auth-Events
- Demonstriert IAM-Konzepte auf Enterprise-Niveau

`Python` `Flask` `TOTP` `PAM` `Session Management` `MFA`

---

### 🎮 [CyberSec Training Simulator](https://github.com/Mr-Nmap)
> Browserbasiertes Lern-Spiel für CompTIA-Zertifizierungen

- Blue Team & Red Team mit eigenen Missionen und Lernpfaden
- 200+ simulierte Befehle: nmap, iptables, clamscan, hydra, metasploit
- XP-System, Skill-Freischaltung, 10+ Missionen mit steigendem Schwierigkeitsgrad
- Vollständig clientseitig – kein Backend, kein Server

`HTML5` `CSS3` `Vanilla JavaScript` `LocalStorage`

---

### 🔍 [PDF Keyword Search & GAP Analysis Tool](https://github.com/Mr-Nmap)
> Web-Tool für Compliance-Audits und ISO-27001-Dokumentenprüfung

- Gleichzeitige Suche in mehreren Dokumentformaten (PDF, Word, Excel, TXT)
- GAP-Analyse: Prozentuale Übereinstimmung mit Anforderungskatalogen
- Vollständig lokal – keine Cloud-Abhängigkeit, datenschutzkonform

`JavaScript` `HTML5` `PDF.js` `Node.js`

---

## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Mr-Nmap&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=1a5276&icon_color=922b21)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Mr-Nmap&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=1a5276)

---

## 📜 Zertifizierungen

| Zertifikat | Aussteller | Jahr |
|---|---|---|
| CompTIA Security+ (SY0-701) | CompTIA | 2026 |
| CompTIA Linux+ (XK0-005) | CompTIA | 2025 |
| CompTIA Network+ | CompTIA | 2025 |
| CompTIA A+ Core 1 & 2 | CompTIA | 2025 |
| ISO/IEC 27001:2022 Lead Auditor | DNV | 2024 |
| CompTIA PenTest+ | CompTIA | 2026 (geplant) |

---

## 📫 Kontakt

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Alexander%20Deske-1a5276?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/alexander-deske-697711198/)
[![Email](https://img.shields.io/badge/Email-alexander%40deske.de-922b21?style=flat-square&logo=gmail&logoColor=white)](mailto:alexander@deske.de)
[![Website](https://img.shields.io/badge/Website-deske--cnc.com-196f3d?style=flat-square&logo=googlechrome&logoColor=white)](https://deske-cnc.com)

---

> *"The best defense is understanding the offense."*
