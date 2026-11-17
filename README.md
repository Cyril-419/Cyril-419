# Hi, I'm Cyril Onyia 👋

<a href="https://linkedin.com/in/cyrilonyia"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://cyril-419.github.io"><img src="https://img.shields.io/badge/-Portfolio-222222?&style=for-the-badge&logo=githubpages&logoColor=white" /></a>

Cybersecurity student at **Western Governors University** (B.S. Cybersecurity, expected Dec 2027) based in the Dallas–Fort Worth area. I'm building toward a career in **security operations and GRC**, starting from hands-on IT support. I like turning messy data (logs, alerts, tickets) into something a person can act on.

🔎 **Open to:** IT support / help desk, cybersecurity, GRC, and software engineering roles and internships

---

## 🛠️ Featured projects

### [Active Directory Home Lab](https://github.com/Cyril-419/Active-Directory-Home-Lab)

A Windows domain built from scratch in **VirtualBox**: a **Windows Server 2022** domain controller and a domain-joined **Windows 11** client, used to practice everyday help desk and system administration work.
- Automated the build with **PowerShell**: OUs, security groups and 12 users bulk-created from CSV
- Worked help desk tickets: account lockouts, password resets, new-hire onboarding and offboarding
- Created and scoped **Group Policy** by department and verified it with `gpresult`
- Delegated password reset and unlock rights to a help desk group without making it Domain Admins (least privilege)
- Documented real troubleshooting: DNS-based domain join failures, a stale DHCP lease, and VM issues

### [Azure Sentinel Honeypot](https://github.com/Cyril-419/Azure-Sentinel-Honeypot)

Internet-exposed **Windows VM in Azure** sending its logs to **Microsoft Sentinel**.
- **KQL** detections for brute force and password spraying (MITRE ATT&CK T1110)
- Attack map workbook and incident triage

### [Security Log Analyzer](https://github.com/Cyril-419/security-log-analyzer)
[![CI](https://github.com/Cyril-419/Security-Log-Analyzer/actions/workflows/ci.yml/badge.svg)](https://github.com/Cyril-419/Security-Log-Analyzer/actions/workflows/ci.yml)

Python tool that parses **Linux, Windows and web server** authentication logs, normalizes them into one format, stores them in **SQLite**, and detects **brute force, password spraying** (MITRE ATT&CK T1110) and successful logins after repeated failures.
- Benchmarked at **1M events in ~26 seconds**, with all planted attacks detected and zero false positives
- Sliding-window detection rules with tunable thresholds
- REST API (`GET /health`, `POST /analyze`) and JSON output for integration with other tools
- 48 automated tests run by a GitHub Actions CI pipeline on Python 3.10–3.13

### [Log Analyzer Dashboard](https://github.com/Cyril-419/Log-Analyzer-Dashboard)
[![CI](https://github.com/Cyril-419/Log-Analyzer-Dashboard/actions/workflows/ci.yml/badge.svg)](https://github.com/Cyril-419/Log-Analyzer-Dashboard/actions/workflows/ci.yml)

Full-stack web app for the analyzer: **React + TypeScript** frontend, **Node.js** REST API with **SQLite**, calling the Python analyzer as a separate **microservice**.
- Upload logs, tune detection thresholds, and explore alerts, charts and saved history
- Hardened API: schema validation, upload limits, rate limiting, Content-Security-Policy, parameterized SQL
- 29 API tests and 8 **Playwright** browser tests; CI starts all three services and tests them end to end

## 🧪 Labs and other projects
- **Detection Lab**: home lab for log collection and attack detection
- **SOC Automation Project**: alert enrichment and response workflow with Shuffle SOAR
- **Threat Intelligence Feed Integration**: pulling threat intel into a SIEM for alert context
- **[Trade Journal](https://github.com/Cyril-419/trade-journal)**: browser app for logging trades, with analytics and charts (JavaScript)
- **[Python Calculator](https://github.com/Cyril-419/python-calculator)**: my first Python project

## 🎯 Job simulations
- **AIG Shields Up (Forage)**: researched a reported vulnerability using CISA guidance, drafted remediation guidance for affected teams, and wrote a Python script to brute-force a ransomware decryption key instead of paying the ransom
- **Mastercard Cybersecurity (Forage)**: analyzed a phishing email for red flags, designed a simulated phishing campaign, and turned department vulnerability metrics into security awareness recommendations

## 🧰 Skills

| Area | Experience |
|---|---|
| SIEM and log analysis | Microsoft Sentinel, Splunk, Python log parsing |
| Network monitoring | Wireshark, Zeek |
| Endpoint security | Microsoft Defender for Endpoint |
| Security automation | Shuffle SOAR, Python scripting |
| GRC | NIST CSF, HIPAA, risk and audit fundamentals (GRC internship) |
| IT support | Troubleshooting, account and password issues, ticket documentation and escalation in a high-volume support environment |
| Windows administration | Active Directory, Group Policy, DNS/DHCP, PowerShell, VirtualBox |

### Tools
<div>
  <img src="https://img.shields.io/badge/-Microsoft_Sentinel-0078D4?&style=for-the-badge&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/-Splunk-000000?&style=for-the-badge&logo=splunk&logoColor=white" />
  <img src="https://img.shields.io/badge/-Wireshark-1679A7?&style=for-the-badge&logo=wireshark&logoColor=white" />
  <img src="https://img.shields.io/badge/-Zeek-777BB4?&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-Defender_for_Endpoint-00A4EF?&style=for-the-badge&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/-Shuffle_SOAR-F85A3E?&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-Active_Directory-0078D4?&style=for-the-badge&logo=windows&logoColor=white" />
<img src="https://img.shields.io/badge/-PowerShell-5391FE?&style=for-the-badge&logo=powershell&logoColor=white" />
<img src="https://img.shields.io/badge/-Python-3776AB?&style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/-SQLite-003B57?&style=for-the-badge&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/-JavaScript-F7DF1E?&style=for-the-badge&logo=javascript&logoColor=black" />
</div>

## 📜 Certifications
<img src="https://img.shields.io/badge/-AMD_ROCm_Certified_Associate-ED1C24?&style=for-the-badge&logo=amd&logoColor=white" />
<img src="https://img.shields.io/badge/-Google_Cybersecurity_Certificate-4285F4?&style=for-the-badge&logo=google&logoColor=white" />

**In progress:** CompTIA Security+ (through WGU)
