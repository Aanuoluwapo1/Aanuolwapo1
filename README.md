# Hi, I'm Anuoluwapo Johnson 
### Cybersecurity Analyst & SecOps Engineer | SOC Operations & Threat Detection

<div align="left">
  <a href="https://www.linkedin.com/in/johnson-anuoluwapo-235189240/">
    <img src="https://img.shields.io/badge/LinkedIn-0072b1?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:anuoluwapojohnson11@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <img src="https://img.shields.io/badge/Focus-SOC_Operations_%26_Threat_Hunting-06B6D4?style=for-the-badge&logo=target&logoColor=white" alt="Focus" />
</div>

---

## Executive Summary

CompTIA Security+, Network+, and A+ certified **Cybersecurity Analyst** with hands-on experience in **Security Operations Center (SOC) engineering, SIEM/EDR implementation, threat triage, and incident response**. 

Specialized in analyzing Windows Security and Sysmon logs, detecting adversary behaviors aligned with the **MITRE ATT&CK® framework**, deploying and tuning open-source XDR/SIEM solutions (**Wazuh, Splunk, Microsoft Sentinel**), and building custom full-stack detection and triage tooling.

---

## Featured Projects

### 1. [SignalOps — Enterprise Security Operations Center (SOC) Platform](https://github.com/Aanuoluwapo1/signalops)
> **Next-Generation Full-Stack Cyber Threat Triage, Incident Response & Telemetry Platform**

[![React 19](https://img.shields.io/badge/React-19.2-61DAFB?style=flat-square&logo=react&logoColor=black)](https://github.com/Aanuoluwapo1/signalops)
[![TypeScript 6](https://img.shields.io/badge/TypeScript-6.0-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://github.com/Aanuoluwapo1/signalops)
[![Node.js 26](https://img.shields.io/badge/Node.js-26-339933?style=flat-square&logo=node.js&logoColor=white)](https://github.com/Aanuoluwapo1/signalops)
[![Express 5](https://img.shields.io/badge/Express-5.3-000000?style=flat-square&logo=express&logoColor=white)](https://github.com/Aanuoluwapo1/signalops)
[![SQLite WAL](https://img.shields.io/badge/SQLite-WAL-003B57?style=flat-square&logo=sqlite&logoColor=white)](https://github.com/Aanuoluwapo1/signalops)
[![Wazuh Ready](https://img.shields.io/badge/SIEM-Wazuh_MCP-0078D4?style=flat-square)](https://github.com/Aanuoluwapo1/signalops)

* **Architecture**: Production-grade full-stack architecture combining a React 19 / TypeScript 6 dark-navy interface with an Express 5 REST API and an embedded SQLite database (`node:sqlite` in WAL mode).
* **Incident Lifecycle Management**: Four-stage containment stepper (*Triage* → *Containment* → *Eradication* → *Resolved*) with one-click host isolation toggles and an audit-trailed investigation notes ledger.
* **Forensic Dossier & SIEM Explorer**: Real-time parsing of Windows Security Event IDs (4624, 4625, 4688) and Sysmon logs (1, 3, 10), with raw JSON inspection and copyable forensic evidence.
* **Threat Analytics**: MITRE ATT&CK® tactic distribution matrices, MTTA/MTTR response velocity vs 15-minute SLA benchmarks, and compliance export simulation (NIST SP 800-61, ISO 27001).

---

### 2. [SSH Log Analysis & Threat Detection Lab](https://github.com/Aanuoluwapo1/SSH-Log-Analysis)
> **SIEM Implementation, Threat Hunting & Log Forensics**

[![SIEM](https://img.shields.io/badge/SIEM-Log_Analysis-orange?style=flat-square)](https://github.com/Aanuoluwapo1/SSH-Log-Analysis)
[![Linux](https://img.shields.io/badge/Linux-Syslog-FCC624?style=flat-square&logo=linux&logoColor=black)](https://github.com/Aanuoluwapo1/SSH-Log-Analysis)

* Ingested and parsed Linux authentication logs (`auth.log`) to identify anomalous connection spikes and brute-force authentication attempts.
* Correlated source IP addresses, geographic origins, and automated threat vectors to formulate firewall defense rules and fail2ban policies.

---

### 3. Wazuh XDR / SIEM Homelab & AI Integration
> **Live Threat Telemetry, Vulnerability Scanning & Model Context Protocol (MCP)**

* Configured a hybrid **Wazuh XDR/SIEM cluster** in an Ubuntu VM monitoring a live Windows 11 endpoint via the Wazuh agent.
* Connected an AI SOC Assistant using the **Model Context Protocol (MCP)** to query live Wazuh Indexer and Manager APIs over HTTP/SSE.
* Conducted real-time vulnerability scans across 118 CVEs, evaluated ISO 27001 compliance controls, and analyzed File/Registry Integrity Monitoring (FIM) telemetry.

---

## Technical Skills & Arsenal

### Security Operations & SIEM
```text
• SIEM Platforms:      Wazuh SIEM/XDR, Splunk, Microsoft Sentinel, OpenSearch
• EDR & Telemetry:     Wazuh Agent, Microsoft Defender for Endpoint, Sysmon
• Log Analytics:       Windows Event Logs (4624, 4625, 4688, 7040), Syslog, auth.log
• Threat Hunting:      MITRE ATT&CK® Mapping, Sigma Detection Rules, Indicators of Compromise (IOCs)
• Compliance & Baselines: NIST CSF, NIST SP 800-61, ISO 27001:2022, CIS Benchmarks, PCI-DSS
```

### Network Security & Traffic Analysis
<div align="left">
  <img src="https://img.shields.io/badge/-Wireshark-1679A7?style=flat-square&logo=Wireshark&logoColor=white" />
  <img src="https://img.shields.io/badge/-Suricata-EF3B2D?style=flat-square&logo=Suricata&logoColor=white" />
  <img src="https://img.shields.io/badge/-Zeek-777BB4?style=flat-square&logo=Zeek&logoColor=white" />
  <img src="https://img.shields.io/badge/-Nmap-4D4D4D?style=flat-square&logo=nmap&logoColor=white" />
  <img src="https://img.shields.io/badge/-Subnetting_&_VLANs-0284C7?style=flat-square" />
  <img src="https://img.shields.io/badge/-Firewalls_&_ACLs-DC2626?style=flat-square" />
</div>

### Full-Stack & Security Automation
<div align="left">
  <img src="https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/-Express.js-000000?style=flat-square&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/-React_19-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/-SQLite_WAL-003B57?style=flat-square&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/-Bash_/_PowerShell-4EAA25?style=flat-square&logo=gnubash&logoColor=white" />
  <img src="https://img.shields.io/badge/-Model_Context_Protocol_(MCP)-8B5CF6?style=flat-square" />
</div>

---

## Certifications

<div align="left">
  <img src="https://img.shields.io/badge/-CompTIA_Security%2B-FF0000?style=for-the-badge&logo=CompTIA&logoColor=white" />
</div>

---

## Connect With Me

- **LinkedIn**: [linkedin.com/in/johnson-anuoluwapo-235189240](https://www.linkedin.com/in/johnson-anuoluwapo-235189240/)
- **Email**: [anuoluwapojohnson11@gmail.com](mailto:anuoluwapojohnson11@gmail.com)
- **GitHub**: [github.com/Aanuoluwapo1](https://github.com/Aanuoluwapo1)
