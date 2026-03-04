# Hi, I'm Gideon Oppong 👋  
### **Cybersecurity Aspirant | AI App Developer | Tech Transitioner**

![Gideon Oppong – Cybersecurity & AI](https://img.shields.io/badge/Gideon_Oppong-Cybersecurity_%7C_AI_App_Developer-blue?style=for-the-badge&logo=security&logoColor=white)  
[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%2336BCF7&size=25&center=true&vCenter=true&lines=Hi+I'm+Gideon+Oppong+👋;Cybersecurity+Analyst+%7C+AI+App+Developer;Tech+Transitioner+%7C+Security+Researcher)](https://git.io/typing-svg)

---

# 📘 Table of Contents  
<details>
<summary><strong>Click to expand</strong></summary>

- [Professional Summary](#-professional-summary)  
- [Featured Repositories](#-featured-repositories)  
- [Featured AI Security Project](#-featured-project-secure-ai-automation-ecosystem)  
- [Cybersecurity Analysis Labs](#-cybersecurity-analysis-labs)  
- [Certifications & Education](#-certifications--education)  
- [Technical Toolkit](#-technical-toolkit)  
- [Connect With Me](#-connect-with-me)  

</details>

---

## 🛡️ Professional Summary  
I am a security-focused builder transitioning from teaching Integrated Science into **Cybersecurity** and **AI-focused automation**.  
By combining the **Google Cybersecurity Professional Certificate** with hands-on **AI App Development (Co.Lab)**, I create functional systems that are resilient against modern security threats.

---

# 📂 Featured Repositories  

## 🔸 **Security-Labs**  
Hands-on cybersecurity labs covering incident response, malware analysis, network forensics, log analysis, and threat detection.  
🔗 **[View Security Labs](assets/Security-Labs)**

---

## 🔸 **AI Security Automation Project (Co.Lab)**  
AI-powered automation for security workflows and Gmail data analysis.  
🔗 **[View AI Automation Project](assets/Projects/CoLab-AI-App)**

---

# 🚀 Featured Project: Secure AI Automation Ecosystem  

**Tools:** Make.com, AppSheet, Gmail API, Google Sheets, OpenAI

### 🔧 The Build  
Created an AI-driven automation suite to filter, categorize, and analyze Gmail data securely.

### 🛡️ The Security Enhancements  
- Conducted *OWASP Top 10* aligned system review  
- Restricted API scopes based on the **Principle of Least Privilege**  
- Secured data flow across Make → AppSheet → Google Sheets  

### 🖥️ App Interface  
![App Dashboard](https://raw.githubusercontent.com/GideonOppong/gideonoppong/2ec6bc2851bfeae47c3395d7a8a85f4a3a3ab873/assets/Screenshot%202026-02-23%20222150.png)  
*Dashboard demonstrating real-time syncing and AI-powered filtering.*

---

# 🛡️ Cybersecurity Analysis Labs  

> Hands-on technical labs completed during the **Google Cybersecurity Professional Certificate**, focused on detection, response, and network security.

---

## 🔍 **Lab 1: Network Traffic Analysis with Wireshark**  

### 🛠️ Tools  
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![TCPDump](https://img.shields.io/badge/TCPDump-grey?style=for-the-badge)

**Scenario:** Detected brute-force attack behavior by analyzing packet captures.  

**Key Findings:**  
- Unencrypted HTTP traffic on Port 80  
- Recommended HTTPS (TLS 1.3) + account lockouts  

---

## 🛡️ **Lab 2: SQL Injection Defense & Database Security**  

### 🛠️ Tools  
![SQL](https://img.shields.io/badge/SQL-006400?style=for-the-badge)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**Scenario:** Identified SQL injection entry points in a web app.  

**Key Findings:**  
- Missing prepared statements allowed raw SQL execution  
- Implemented sanitization + least privilege DB roles  

---

## 🐍 **Lab 3: Automating Security Tasks with Python**  

### 🛠️ Tools  
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

**Scenario:** Wrote automation scripts to parse server logs for flagged IPs.

### Sample Script  
```python
# Simple script to check if an IP is in the 'Allow List'
def check_access(ip_address):
    allow_list = ["192.168.1.1", "192.168.1.50"]
    if ip_address in allow_list:
        print("Access Granted")
    else:
        print("Access Denied - Flagged for Review")
