# Cybersecurity analyst who investigates real threats, not just lab simulations.

**M.S. Cybersecurity | University of Central Missouri | OPT: July 2026**  
**Targeting:** SOC Analyst | Incident Response | Threat Intelligence | IAM | GRC | Risk  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/sai-naga-sabarish-yerramsetty-617013210)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-green)](https://sabarish-portfolio-9f7a.vercel.app)
[![Medium](https://img.shields.io/badge/Medium-Blog-black)](https://medium.com/@ysabarish369)

---

## What I Do

I investigate phishing campaigns, trace malicious infrastructure, write IOC reports, and document everything the way a real SOC team would. Every project in this repo comes with full write-ups, screenshots, and investigation reports because showing the process matters more than just listing the tools.

I have worked as a Security Analyst at UCM monitoring SIEM and EDR tools across 10+ university systems, leading incident response from detection through recovery, and delivering risk reports to senior IT leadership. Before that I built IBM QRadar correlation rules and wrote CVSS-scored forensic reports at SmartInternz.

---

## Investigations and Projects

### Phishing Email Forensics
**Tools:** MXToolbox, AbuseIPDB, VirusTotal, DomainTools WHOIS  
**MITRE ATT&CK:** T1566.001  
Investigated a real phishing email impersonating Banco Bradesco. SPF, DKIM, and DMARC all failed. Traced the originating IP to a DigitalOcean VPS in California flagged malicious by Criminal IP, GreyNoise, and AlphaSOC. Documented IOCs and wrote detection rules for email gateway, firewall, and SIEM.  
[View Project](https://github.com/SabarishYerramsetty/cybersecurity-projects/tree/main/Phishing-Email-Forensics)

---

### IOC Report Writing
**Tools:** ThreatFox, Shodan, URLScan, STIX 2.1  
**MITRE ATT&CK:** T1566.001  
Enriched phishing campaign IOCs through Shodan, ThreatFox, and URLScan. Discovered the attack server was still active 3 years later with SSH publicly exposed. Found phishing content was being served from Amazon S3 buckets. Formatted findings in STIX 2.1 with severity ratings and detection rules.  
[View Project](https://github.com/SabarishYerramsetty/cybersecurity-projects/tree/main/IOC-Report-Phishing-Campaign)

---

### Brute Force Detection
**Tools:** Splunk, Windows Event Logs  
**MITRE ATT&CK:** T1110  
Simulated 500+ brute force login attempts, generated Event ID 4625 failures, and built Splunk SPL detections to flag the pattern. Cut manual log review time by 60%.  
[View Project](https://github.com/SabarishYerramsetty/cybersecurity-projects/tree/main/SIEM-Brute-Force-Detection)

---

### Malware Detection
**Tools:** Windows Defender, Splunk, EICAR Test File  
**MITRE ATT&CK:** T1204  
Simulated malware activity using an EICAR test file, triggered Windows Defender Event ID 1116, and verified the full detection pipeline from endpoint to SIEM.  
[View Project](https://github.com/SabarishYerramsetty/cybersecurity-projects/tree/main/Malware-Traffic-Analysis-Lab)

---

### Network Traffic Analysis
**Tools:** Wireshark, Splunk, Kali Linux  
**MITRE ATT&CK:** T1040  
Captured live network traffic between virtual machines, analyzed PCAP files for suspicious patterns, applied Wireshark filters to isolate abnormal connections, and correlated findings in Splunk.  
[View Project](https://github.com/SabarishYerramsetty/cybersecurity-projects/tree/main/Network-Threat-Hunting-Wireshark)

---

## Skills

| Category | Tools and Techniques |
|---|---|
| SIEM | Splunk SPL, IBM QRadar, Windows Event Logs, Log Correlation |
| Threat Intelligence | ThreatFox, Shodan, URLScan, AbuseIPDB, VirusTotal, WHOIS |
| Email Forensics | MXToolbox, SPF, DKIM, DMARC Analysis, Header Analysis |
| Network Analysis | Wireshark, PCAP Analysis, Traffic Filtering |
| Frameworks | MITRE ATT&CK, STIX 2.1, NIST CSF, SANS Incident Handling |
| Endpoint Security | Windows Defender, EDR Monitoring, Event ID Analysis |
| Scripting | Python, PowerShell, Bash |
| Cloud | AWS IAM, AWS Cloud Practitioner |
| Reporting | IOC Reports, Risk Documentation, Executive Briefings |

---

## Certifications

- CompTIA Security+ (SY0-701) — 2026
- Google Cybersecurity Professional Certificate
- AWS Certified Cloud Practitioner

---

## Currently Working On

- Home Network Threat Hunt using Wireshark
- DNS Threat Hunting
- Failed Login Correlation Hunt
- Building out SOC detection playbooks

---

## Let's Connect

I am actively looking for SOC Analyst, Incident Response, Threat Intelligence, IAM, and GRC roles with OPT starting July 2026.

If you are hiring or want to collaborate on security research, reach out on LinkedIn or check out my portfolio.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sai%20Naga%20Sabarish-blue)](https://www.linkedin.com/in/sai-naga-sabarish-yerramsetty-617013210)
[![Portfolio](https://img.shields.io/badge/Portfolio-sabarish--portfolio-green)](https://sabarish-portfolio-9f7a.vercel.app)

---

*Every investigation in this repo is documented the way a real SOC team would do it. Tools, findings, IOCs, and recommendations. Not just screenshots.*
