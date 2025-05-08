# Cybersecurity Portfolio – Coursera Professional Certificate

This repository contains a collection of cybersecurity projects completed as part of the Google/Coursera Cybersecurity Professional Certificate. Each project simulates real-world scenarios aligned with NIST and industry practices, focusing on threat detection, incident response, access control, and risk management.

---

## Project Summaries

### 1. **Incident Report – Ransomware Attack**
Investigated a ransomware incident at a small healthcare clinic initiated via a phishing email. The report follows the full NIST CSF lifecycle from identification to recovery, highlighting containment, forensic imaging, and backup restoration efforts.

### 2. **Analyzing Network Structure and Security**
Mapped and assessed a simulated network infrastructure to identify firewall and segmentation weaknesses. Provided recommendations for improved defense in depth based on observed vulnerabilities.

### 3. **Applying Filters to SQL Queries**
Used SQL queries to extract cybersecurity relevant data such as failed logins, departmental employee lists, and geolocation-based activity. Demonstrated logical filtering using `AND`, `OR`, `NOT`, and pattern matching (`LIKE`) for real-world threat detection tasks.

### 4. **Conducting a Security Audit – Botium Toys**
Performed a full internal security audit using the NIST CSF for a fictional company. Evaluated technical, administrative, and physical controls. Identified compliance gaps with PCI DSS, SOC 2, and GDPR and provided risk-based recommendations.

### 5. **Identifying Vulnerabilities for a Small Business**
Completed a remote access server risk assessment for an e-commerce business using a qualitative method based on NIST SP 800-30. Assessed external threats from hackers, competitors, and hacktivists, and proposed remediation strategies including VPNs, MFA, and encrypted access.

### 6. **Importing and Parsing IP Lists Using Python**
Built a Python script to manage access control by reading from an allow list and removing IPs found in a separate deny list. Ensured access to sensitive healthcare infrastructure remained restricted and auditable through secure file handling.

### 7. **Managing File Permissions with Linux Commands**
Used commands like `ls -la` and `chmod` to analyze and secure sensitive files and directories on a Linux system. This project enforced proper access rights by applying least privilege principles and removing unauthorized access.

### 8. **Incident Response Journal (Multiple Cases)**
Documented six security incidents including:
- A phishing based ransomware attack
- Packet analysis using Wireshark
- Malware identification using SHA256 and VirusTotal
- Response actions via alert ticketing
- Post-incident review of a large scale data breach
- Threat hunting using Splunk for failed SSH login attempts

---

## Tools & Technologies Used

- **SQL** (MariaDB) – Filtering and querying login and employee data
- **Python** – File parsing and automation of access control updates
- **Linux** – File permission management using `chmod` and `ls`
- **Wireshark** – Network traffic inspection and packet filtering
- **Splunk Cloud** – Threat hunting and log analysis using SPL
- **VirusTotal** – Malware detection and IoC investigation
- **SIEM & EDR** – Incident detection and monitoring
- **NIST CSF** – Risk management and incident lifecycle framework
- **GDPR, PCI DSS, SOC** – Compliance assessments and audits
