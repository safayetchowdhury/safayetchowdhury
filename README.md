# Hi, I'm Safayet Chowdhury 🛡️

### **SOC Analyst | Security+ & Google Cybersecurity | Incident Response • Threat Detection • Vulnerability Triage | Splunk • Sentinel • Azure • Python • Linux • IDS/IPS | DoD 8140 Baseline Compliant | Permanent Resident | Open to Relocation**

**CompTIA Security+** certified Support Analyst with hands on experience in **security operations, threat triage, and incident response**. Background spans customer facing operations support, compliance auditing, and third party risk management (TPRM), providing a practical, cross functional foundation in SIEM monitoring, vulnerability assessment, and defensive security architecture including Snort IDS, SOAR automation, and cloud identity platforms like Azure, Sentinel, and Entra ID. Currently pursuing opportunities in **SOC Analysis, Incident Response, Vulnerability Management, or Governance, Risk & Compliance (GRC).**

---

## 🔬 Practical Projects
* [**Azure Sentinel SOC Detection Lab with Entra ID Least-Privilege Automation**](https://github.com/safayetchowdhury/Azure-Sentinel-KQL-Entra-ID-Threat-Detection-Lab): Designed a working SOC detection lab in Azure Sentinel from the ground up: stood up a live target VM, launched real SSH brute-force, port-scan, and SYN flood attacks from an isolated attacker machine, then built and validated three custom KQL detection rules directly against the resulting log data, including debugging a failed regex match and discovering that volumetric attacks require kernel-layer detection rather than auth-log analysis. Closed the loop with a scoped Entra ID service principal, so any future automation runs on a least-privilege identity instead of a personal account.
* [**Automated Defense Architecture: Splunk, Python, Claude API, AD, IAM, OWASP**](https://github.com/safayetchowdhury/Automated-Defense-Architecture-Splunk-Python-Claude-API-AD-IAM-OWASP): Built a 3-VM enterprise security lab (Splunk SIEM, Active Directory, IAM) simulating a HIPAA-regulated healthcare network; configured Splunk Universal Forwarder log ingestion and Windows audit policies to achieve 1:1 detection accuracy (9/9 brute-force login attempts captured), then engineered a custom scheduled Splunk alert (5-minute rolling window, >5-event threshold) and a Python + Claude API integration that automatically pulls, sanitizes (regex-based IP redaction for DLP compliance), and summarizes SIEM alerts into an executive HIPAA-impact report — reducing manual OWASP A07:2021 authentication-failure triage to a single automated script execution.
* [**CDE Vulnerability Management: Nessus Scanning and Jira Ticketing**](https://github.com/safayetchowdhury/CDE-Vulnerability-Management-Nessus-Scanning-and-Jira-Ticketing): Conducted a credentialed Nessus vulnerability scan against an Active Directory Cardholder Data Environment (CDE), identifying 48 total vulnerabilities (22 Critical, 26 High); engineered a data-transformation pipeline to clean and map findings to PCI DSS compliance fields, then deployed prioritized Jira tickets with risk-based SLAs (24-hour SLA for Critical/Highest, 7-day SLA for High) — filtering out Medium/Low noise to reduce alert fatigue and keep engineering focused on the 48 compliance-critical findings.
* [**Penetration Testing & Forensic Audit Lab**](https://github.com/safayetchowdhury/Penetration-Testing-Forensic-Audit-Using-Kali-Ubuntu-Metasploit): Conducted a full-lifecycle penetration test across a 3-VM isolated network (Kali Linux, Ubuntu, Metasploitable2) using Nmap for service discovery, Hydra for SSH brute-force credential testing, and the Metasploit Framework to exploit a legacy vsftpd backdoor (pivoting to a bind-shell payload to achieve root access after an initial reverse-shell failure); performed forensic log analysis on Linux auth.log to extract Indicators of Compromise (IoCs) and mapped all techniques to three *MITRE ATT&CK* IDs (T1110.001, T1210, T1046) for standardized incident documentation.
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
**Support Analyst** | *Tide (Procter & Gamble) , Charlotte, NC* (Jan 2024 – Present)
* Serve as front-line point of contact across customer-facing operations, managing day-to-day issue escalation and coordinating with plant operations and peer teams to drive rapid resolution. Own troubleshooting end-to-end at the location level, identifying root causes and following through until resolved, boosting operational profitability 15 percent by eliminating recurring order-loss incidents. Maintain 100 percent compliance with operational security protocols across all customer interactions.

**Assosiate** | *Nordstrom Rack, Charlotte, NC* (Nov 2023 – Aug 2024)
* Partnered with the Asset Protection and Loss Prevention team to conduct routine compliance audits and physical security risk assessments across the sales floor and stockroom, identifying control gaps before they became losses. Investigated shrinkage patterns and suspicious transaction activity, correlating point-of-sale data and inventory records to flag anomalies for further review, cutting inventory shrinkage 12 percent year over year. Documented findings and recommended mitigation plans to store leadership, achieving 100 percent adherence to security protocol standards during audit cycles. Balanced day-to-day customer service responsibilities with ongoing vigilance for policy violations and internal/external theft indicators, applying a risk-based approach to prioritize high-exposure areas.

**Account Manager** | *Square Apparels Ltd., Dhaka, Bangladesh* (Oct 2022 – July 2023)
* Managed end-to-end vendor relationships for 45+ high-volume RMG bulk shipments quarterly, using SAP ERP to track order accuracy, shipment data integrity, and compliance documentation across a multi-tier global supply chain. Conducted vendor risk assessments against SEDEX and brand compliance standards, auditing supplier practices and flagging non-conformances before they escalated into delivery or reputational risk. Optimized third-party risk management (TPRM) processes by standardizing vendor onboarding and audit checkpoints, cutting vendor delays 20 percent while maintaining 100 percent SEDEX and brand compliance. Served as the primary escalation point between internal teams and external vendors, resolving discrepancies in shipment records and compliance documentation to protect data accuracy across the order lifecycle.

**Instructor** | *Pathshaala, Chattogram, Bangladesh* (Feb 2016 – Sep 2022)
* Designed and delivered technical curricula and structured documentation for 50+ trainees, breaking down complex technical concepts into clear, repeatable training material — accelerating onboarding time by 30 percent. Built standardized process guides and reference documentation to ensure consistency across cohorts, reducing knowledge gaps and dependency on ad hoc explanation. Assessed trainee comprehension through hands-on exercises and iterative feedback, identifying common failure points and adjusting instructional approach accordingly, achieving a 95 percent satisfaction rate. Mentored individuals with varying technical backgrounds, reinforcing foundational concepts before advancing to applied skills a structured, patient approach to technical knowledge transfer.

---

## 🎓 Education & Certifications
* **[Google & CompTIA Dual Credential](https://www.credly.com/badges/3e474716-622f-40ae-a97c-6bbc5fb818d7)** – Issued July 2026
* **[CompTIA Security+ (SY0-701)](https://www.credly.com/badges/7d73866c-1a51-4bb1-bd1e-f4bd8713fae6)** – Issued Dec 2025
* **[Google Cybersecurity Professional Certificate](https://www.credly.com/badges/87996428-e64b-44f9-aa25-8ebcdeab31b1/)** (Linux, MySQL, Python Labs)
* **[Network Security – Cisco](https://www.coursera.org/account/accomplishments/verify/955KG2FNZJ41)**
* **[Security Governance & Compliance – UC Irvine](https://www.coursera.org/account/accomplishments/verify/HMJZ9SFQBUNU)**
* **B.S. in Textile Sciences and Engineering | Bangladesh University of Textiles |**  2016 - 2021

  *Relevant Coursework: ISO Quality Standards, Process Control & Auditing, Statistical Analysis, Industrial/OT Systems*

---

## 📫 Let's Connect
* **LinkedIn:** [linkedin.com/in/safayetc](https://www.linkedin.com/in/safayetc)
* **Email:** safayetchowdhury25@gmail.com
* **Location:** Charlotte, NC (*Open to Relocation*)
