# 🛡️ SOC Labs & Blue Team Projects

By Yusuf Usman — Cybersecurity Analyst (Blue Team)

Hands-on SOC operations • Detection engineering • Threat hunting

## 👨‍💻 About

This repository contains my end-to-end SOC Analyst portfolio, built from real-world defensive security labs.
Each project replicates enterprise environments using Microsoft Sentinel, Wazuh, Suricata, Defender, KQL, MITRE ATT&CK, and SIEM engineering.

My goal is to demonstrate practical Blue Team capability — not theory.

This repo includes:
	•	Full SOC home lab builds
	•	Network + endpoint log pipelines
	•	Custom detections
	•	MITRE ATT&CK–mapped investigations
	•	Threat hunting playbooks
	•	Incident response write-ups

## Featured Projects (Most Recent)

### 1️⃣ Suricata IDS + Wazuh SIEM Integration (Live Project)

Tools: Suricata, Wazuh, Elastic, Azure VM, pfSense
Skills Shown:
	•	Deployed Suricata IDS (ET Open ruleset)
	•	Configured Wazuh Logcollector to ingest /var/log/suricata/eve.json
	•	Verified alert ingestion with Wazuh rule 86601
	•	Correlated events with:
	•	testmyids.com (attack response)
	•	TLS JA3 fingerprints
	•	Invalid ACK packet detection
	•	Parsed Suricata alerts inside Wazuh using jq and JSON decoders

📁 Folder: Suricata_IDS+Wazuh_SIEM/

### 2️⃣ Microsoft Sentinel SOC Lab
	•	Built Sentinel workspace from scratch
	•	Connected data sources (Linux, Azure AD, MDE)
	•	Created custom Analytics Rules
	•	Built Hunting Queries (KQL)
	•	Automated incident assignments & enrichment (SOAR)
	•	Built dashboards and workbooks

📁 Folder: Microsoft-Sentinel/

### 3️⃣ Defender for Endpoint Lab
	•	Analyzed MDE alerts
	•	Mapped attacks to MITRE ATT&CK
	•	Performed device isolation & Live Response
	•	Investigated phishing simulations
	•	Collected evidence for timeline reconstruction

📁 Folder: Defender-for-Endpoint-Lab/

### 4️⃣ Defender for Cloud Lab
	•	Interpreted Secure Score
	•	Analyzed compliance frameworks (CIS, NIST, ISO)
	•	Simulated misconfigurations and investigated alerts
	•	Built remediation pipelines

📁 Folder: Defender-for-Cloud/

### 5️⃣ KQL Threat Hunting Collection
	•	Common SOC KQL queries
	•	Hunting logic mapped to MITRE ATT&CK
	•	Custom queries for:
	•	Brute force attempts
	•	Token misuse
	•	Rare process executions
	•	Suspicious network communication

📁 Folder: KQL-Practice/


## 🎯 Current Certification Path
	•	✔ Security+ (Passed)
	•	✔ ISC2 Certified in Cybersecurity
	•	⏳ SC-200: Microsoft Security Operations Analyst



## 🔗 Connect With Me

📧 dev.yusuf.usman@gmail.com

🌍 London, UK

🔗 
- [LinkedIn Profile](https://www.linkedin.com/in/yusuf-adetunji-usman/)
- [GitHub Profile](https://github.com/Y-usman)
