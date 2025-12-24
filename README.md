#  Security Alert Monitoring & Incident Response (SOC Simulation)

##  Internship Task – Future Interns (Cyber Security)
**Task 2: Security Operations Center (SOC) – Alert Monitoring & Incident Response**

---

##  Project Overview
This project simulates the responsibilities of a **Security Operations Center (SOC) analyst**, focusing on monitoring security alerts, analyzing suspicious activities, and responding to incidents using a **SIEM tool**.

The objective is to gain hands-on experience in:
- Log analysis
- Alert triage
- Incident classification
- Incident response documentation

---

##  Tools & Technologies Used
- **SIEM Tool:** Splunk (Free / Local Setup)
- **Log Source:** Simulated SOC sample logs
- **Operating System:** Kali Linux / Windows
- **Documentation:** PDF Report, Markdown files

---

##  Incident Summary
- **Incident Title:** Trojan Malware Detection
- **Severity Level:** High
- **Detected Using:** Splunk SIEM
- **Threat Type:** Malware (Trojan)
- **Affected Entities:** Multiple users and IP addresses

Multiple malware detection alerts were observed across different user accounts and IP addresses, indicating a potential malware infection within the environment.

---

##  Alert Analysis & Classification
The following alerts were identified and classified during log analysis:

| Alert ID | Alert Type | Severity | Log Source |
|--------|-----------|----------|-----------|
| A-01 | Trojan Malware Detected | High | Endpoint Logs |
| A-02 | Multiple Login Failures | Medium | Authentication Logs |
| A-03 | Unusual IP Activity | Medium | Network Logs |

---

##  Incident Timeline
| Time (Approx.) | Activity |
|---------------|----------|
| 09:04 | Malware detection alert triggered in SIEM |
| 09:10 | SOC analyst reviewed logs and identified Trojan activity |
| 09:20 | Incident classified as High severity |
| 09:30 | Containment and remediation actions documented |

---

##  Impact Analysis
Trojan malware can allow unauthorized access, data theft, and further malware installation.  
If left unaddressed, this could result in system compromise and data loss.

---

##  Recommended Response Actions
- Isolate affected systems from the network
- Perform malware scans and removal
- Reset compromised user credentials
- Monitor network traffic for suspicious behavior
- Apply security patches and updates

---

##  Project Files
- `Incident_Response_Report.pdf` – Detailed incident response documentation
- `alert_classification.md` – Alert severity and classification
- `incident_timeline.md` – Incident lifecycle timeline
- `screenshots/` – Evidence from Splunk SIEM (dashboard, logs, alerts)

---

##  Learning Outcomes
- Understanding of SOC operations
- Hands-on SIEM log analysis
- Alert triage and prioritization
- Incident response documentation
- Real-world cybersecurity workflow simulation

---

##  Internship Information
This project was completed as part of the **Cyber Security Internship** at **Future Interns**.

---

##  Author
**Name:** *Your Name*  
**Role:** Cyber Security Intern  
**Organization:** Future Interns
