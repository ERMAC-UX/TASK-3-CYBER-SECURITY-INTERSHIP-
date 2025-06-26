# TASK-3-CYBER-SECURITY-INTERSHIP-
# Cybersecurity Task 3 - Vulnerability Scan Report

## 📄 Overview
This project documents the results of a security vulnerability scan conducted on a local Windows 11 machine using **Tenable Nessus Essentials**. The objective was to identify vulnerabilities, assess potential threats, and recommend remediation steps to improve system security.

## 🛠 Tools Used
- **Scanner:** Tenable Nessus Essentials
- **Scan Target:** Localhost (127.0.0.1)
- **Scan Type:** Basic Network Scan

## 🔍 Scan Summary
- **Total Vulnerabilities Detected:** 73
  - High Severity: 2
  - Medium Severity: 71
- **Total Plugins Executed:** 3872
- **Total Open Ports Detected:** 62
- **Active Connections:** 47
- **Operating System Identified:** Windows 11

## 🌐 Network Exposure
### TCP Ports:
135, 139, 445, 5040, 902, 912, 7680, 8834, 5050, 49664-49669, and more.

### UDP Ports:
123, 500, 4500, 5353, 5355, 62831, and more.

> ⚠️ **Notable Security Risks:**
> - **SMB on port 445** — historically exploited in ransomware attacks.
> - **VMware ports** — potentially expose sensitive services.

## ✅ Key Recommendations
- Apply OS and application updates regularly.
- Disable or firewall unused ports and services.
- Restrict service exposure to external interfaces.
- Use loopback binding where possible.
- Perform recurring vulnerability scans.

## 📎 File Structure
