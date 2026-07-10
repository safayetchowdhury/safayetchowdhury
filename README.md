# Hi, I'm Safayet Chowdhury 🛡️

### **Cybersecurity Specialist | CompTIA Security+ | SOC Operations, Incident Response & Vulnerability Management | Support Analyst | Permanent Resident | Open To Relocation**

**CompTIA Security+** certified professional with hands-on experience in **security operations, threat triage, and incident response**. My background spans technical support, compliance auditing, and third-party risk management (TPRM), giving me a practical, cross-functional foundation in SIEM monitoring, vulnerability assessment, and defensive security architecture. Currently pursuing opportunities in **SOC Analysis, Incident Response, Vulnerability Management, or Governance, Risk & Compliance (GRC).**

---

## 🔬 Practical Projects
* [**Automated Defense Architecture: Splunk, Python, Claude API, AD, IAM, OWASP**](https://github.com/safayetchowdhury/Automated-Defense-Architecture-Splunk-Python-Claude-API-AD-IAM-OWASP): Built a 3-VM enterprise security lab (Splunk SIEM, Active Directory, IAM) simulating a HIPAA-regulated healthcare network; configured Splunk Universal Forwarder log ingestion and Windows audit policies to achieve 1:1 detection accuracy (9/9 brute-force login attempts captured), then engineered a custom scheduled Splunk alert (5-minute rolling window, >5-event threshold) and a Python + Claude API integration that automatically pulls, sanitizes (regex-based IP redaction for DLP compliance), and summarizes SIEM alerts into an executive HIPAA-impact report — reducing manual OWASP A07:2021 authentication-failure triage to a single automated script execution.
* [**CDE Vulnerability Management: Nessus Scanning and Jira Ticketing**](https://github.com/safayetchowdhury/CDE-Vulnerability-Management-Nessus-Scanning-and-Jira-Ticketing): Conducted a credentialed Nessus vulnerability scan against an Active Directory Cardholder Data Environment (CDE), identifying 48 total vulnerabilities (22 Critical, 26 High); engineered a data-transformation pipeline to clean and map findings to PCI DSS compliance fields, then deployed prioritized Jira tickets with risk-based SLAs (24-hour SLA for Critical/Highest, 7-day SLA for High) — filtering out Medium/Low noise to reduce alert fatigue and keep engineering focused on the 48 compliance-critical findings.
* [**Penetration Testing & Forensic Audit Lab**](https://github.com/safayetchowdhury/Penetration-Testing-Forensic-Audit-Using-Kali-Ubuntu-Metasploit): Conducted a full-lifecycle penetration test across a 3-VM isolated network (Kali Linux, Ubuntu, Metasploitable2) using Nmap for service discovery, Hydra for SSH brute-force credential testing, and the Metasploit Framework to exploit a legacy vsftpd backdoor (pivoting to a bind-shell payload to achieve root access after an initial reverse-shell failure); performed forensic log analysis on Linux auth.log to extract Indicators of Compromise (IoCs) and mapped all techniques to three MITRE ATT&CK IDs (T1110.001, T1210, T1046) for standardized incident documentation.
* [**Defensive Architecture Using Snort IDS and SOAR**](https://github.com/safayetchowdhury/Defensive-Architecture-Using-Snort-IDS-and-SOAR): Architected a Defense-in-Depth network security stack integrating ModSecurity WAF, Snort IDS/IPS, and UFW firewall on an isolated lab network; built a custom SOAR (Security Orchestration, Automation, and Response) Bash script that parses Snort alert logs in real time via regex and auto-inserts a top-priority UFW deny rule, achieving fully automated IP isolation with zero manual intervention — validated live against a simulated RCE web exploit that triggered simultaneous WAF blocking and automatic firewall banning.
* **[Wireshark and Nmap Packet Analysis and Network Reconnaissance](https://github.com/safayetchowdhury/Wireshark-and-Nmap-Packet-Analysis-and-Network-Reconnaissance):** Performed 7-phase packet-level traffic analysis using Wireshark and Nmap across ICMP, DNS, TCP, ARP, and HTTP protocols; built a custom Wireshark coloring rule (tcp.flags.syn==1 && tcp.flags.ack==0) to visually isolate Nmap reconnaissance traffic from background noise, reducing Mean Time to Detect (MTTD) for scan activity; identified a critical vulnerability by capturing an HTTP Basic Auth credential pair transmitted in plaintext, demonstrating a real-world cleartext-credential exposure risk.
* **[Incident Response with Splunk](https://github.com/safayetchowdhury/Incident-Response-with-Splunk):** Conducted end-to-end forensic incident response using Splunk SPL and OSINT (VirusTotal, Robtex) to reconstruct a full attack lifecycle across the 7-phase Cyber Kill Chain; correlated Suricata, Sysmon, firewall, and web server logs to identify a successful breach out of 142 unique brute-force attempts, extract a malware MD5 hash IoC, and unmask C2 (Command & Control) infrastructure and a secondary malware payload tied to typosquatted phishing domains.
* **[SQL-Based Security Incident Investigation](https://github.com/safayetchowdhury/SQL-based-Security-Incident-Investigation):** Investigated a security incident using targeted SQL queries (AND/OR/NOT/LIKE operators) against enterprise log and asset data; isolated after-hours failed authentication attempts and out-of-region login anomalies, then segmented 3 departments' worth of employee assets by building/office location to drive a targeted security patch rollout — reducing manual endpoint review through query-based asset filtering, with an explicit Principle of Least Privilege framework applied for production scaling.
* **[Linux System Hardening](https://www.linkedin.com/in/chowdhurysafayet/overlay/Project/169833476/treasury?profileId=ACoAAC5wpjABUcO4Av7ACNfCmop02uQ2z1vQZ50):** Audited and hardened Linux system directory structures via CLI, enforcing the Principle of Least Privilege; identified and remediated over-permissive file/directory permissions, mitigating unauthorized data access and reducing the organization's attack surface.
* **[Cybersecurity Incident Handler’s Journal](https://www.linkedin.com/in/chowdhurysafayet/overlay/Project/198476149/treasury?profileId=ACoAAC5wpjABUcO4Av7ACNfCmop02uQ2z1vQZ50):** Investigated and remediated ransomware, phishing, and web application vulnerabilities across simulated incident scenarios; quarantined malicious payloads pre-execution and identified critical access control flaws, protecting 50,000+ sensitive records and preventing an estimated $100,000 in potential financial loss through rapid incident response and remediation.

---

## 🛠️ Technical Skills
* **Security & Compliance:** Security+ Certified, HIPAA Compliance, IAM, SIEM (Splunk), Wireshark, Nmap, IDS/IPS, Vulnerability Assessment, Incident Response.
* **Software & OS:** Windows 10/11, macOS, iOS, Android, Linux (Unix), Google Workspace, Microsoft Office Suite.
* **Networking:** TCP/IP, DNS, DHCP, ISP/Broadband Troubleshooting, VPN, Secure Remote Assistance.
* **Systems/Coding:** Python, Java (Intermediate), SQL.
* **Languages:** Bengali (Native), English (Professional), Hindi & Urdu (Limited).

---

## 💼 Professional Experience
**Support Analyst** | *Tide, Charlotte, NC* (Jan 2024 – Present)
* Eliminated lost orders through proactive on-site troubleshooting, driving a 15% increase in profitability. Spearheaded diagnostic triage for complex enterprise systems, reducing MTTR by 35% and ensuring 100% compliance during secure remote assistance.

**Assosiate** | *Nordstrom, Charlotte, NC* (Nov 2023 – Aug 2024)
* Executed rigorous compliance audits, directly reducing inventory shrinkage by 12% year-over-year. Identified critical operational risks and implemented targeted mitigation strategies, achieving 100% security protocol adherence across audited departments.

**Account Manager** | *Square Apparels Ltd., Dhaka, Bangladesh* (Oct 2022 – July 2023)
* Directed supply chain logistics via SAP ERP, managing 45+ high-volume RMG bulk shipments quarterly. Optimized Third-Party Risk Management (TPRM) to reduce vendor delays by 20% while maintaining 100% SEDEX and brand compliance.

**Instructor** | *Pathshaala, Chattogram, Bangladesh* (Feb 2016 – Sep 2022)
* Designed technical curriculum and procedure documentation to train 50+ individuals, accelerating onboarding time by 30%. Translated complex concepts into accessible content, achieving a 95% positive feedback rate for instructional clarity.

---

## 🎓 Education & Certifications
* **[Google & CompTIA Dual Credential](https://www.credly.com/badges/3e474716-622f-40ae-a97c-6bbc5fb818d7)** – Issued July 2026
* **[CompTIA Security+ (SY0-701)](https://www.credly.com/badges/7d73866c-1a51-4bb1-bd1e-f4bd8713fae6)** – Issued Dec 2025
* **[Google Cybersecurity Professional Certificate](https://www.credly.com/badges/87996428-e64b-44f9-aa25-8ebcdeab31b1/)** (Linux, MySQL, Python Labs)
* **[Network Security – Cisco](https://www.coursera.org/account/accomplishments/verify/955KG2FNZJ41)**
* **[Security Governance & Compliance – UC Irvine](https://www.coursera.org/account/accomplishments/verify/HMJZ9SFQBUNU)**
* **B.S. in Textile Sciences and Engineering | Bangladesh University of Textiles |**  2016 - 2021

---

## 📫 Let's Connect
* **LinkedIn:** [linkedin.com/in/safayetc](https://www.linkedin.com/in/safayetc)
* **Email:** safayetchowdhury25@gmail.com
* **Location:** Charlotte, NC
