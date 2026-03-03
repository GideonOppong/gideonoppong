
![Gideon Oppong – Cybersecurity & AI](https://img.shields.io/badge/Gideon_Oppong-Cybersecurity_%7C_AI_App_Developer-blue?style=for-the-badge&logo=google&logoColor=white)

[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%2336BCF7&size=25&center=true&vCenter=true&lines=Hi+I'm+Gideon+Oppong+👋;Cybersecurity+Analyst+%7C+AI+App+Developer;Tech+Transitioner+%7C+Security+Researcher)](https://git.io/typing-svg)

# Hi, I'm Gideon Oppong 👋 

## 🛡️ Professional Summary
I am a security-focused builder transitioning from a background in **Integrated Science Education** into **Cybersecurity**. I specialize in bridging the gap between developing functional AI-driven tools and securing them against modern threats. 

My analytical background in science enables me to approach incident response and threat hunting with a rigorous, evidence-based methodology.

---

## 📂 Featured Repositories

### 🛡️ **Cybersecurity Analysis Labs**
A comprehensive collection of hands-on technical labs focusing on threat detection, incident response, and network security using the NIST Framework.
🔗 [View Security Labs Folder](./assets/Security-Labs)

### 🤖 **Secure AI Automation Ecosystem (Co.Lab)**
A production-ready automation suite demonstrating secure data pipelines and API management.
🔗 [View Project Folder](./assets/Projects/CoLab-AI-App)

---

## 🚀 Featured Project: Secure AI Automation Ecosystem
**Tools:** Make.com, AppSheet, Google Sheets, Gmail API, OpenAI

* **The Build:** Developed an AI-driven automation suite to streamline secure email filtering and data categorization.
* **The Security Twist:** Audited the data pipeline for **OWASP Top 10 for LLMs**; restricted API scopes to **Principle of Least Privilege (PoLP)** to mitigate account takeover risks.

### 🖥️ App Interface Overview
![App Dashboard](https://raw.githubusercontent.com/GideonOppong/gideonoppong/2ec6bc2851bfeae47c3395d7a8a85f4a3a3ab873/assets/Screenshot%202026-02-23%20222150.png)
*Figure 1: The AppSheet interface displaying real-time secure data sync from Google Sheets.*

---

## 🔍 Featured Lab: Network Analysis with Wireshark
**Scenario:** Identified a potential brute-force attack on a simulated internal server by analyzing packet captures.

* **Tools:** Wireshark, TCPDump
* **Key Finding:** Identified unauthorized HTTP 401 errors indicating a credential stuffing attempt.
* **Mitigation:** Recommended transitioning to HTTPS (TLS 1.3) and implementing account lockout policies.



---

## 🐍 Security Automation: Python
I use Python to automate repetitive security tasks, such as log parsing and access control validation.

```python
# Simple script to check if an IP is in the 'Allow List'
def check_access(ip_address):
    import_list = ["192.168.1.1", "192.168.1.50"]
    if ip_address in import_list:
        print(f"Access Granted to {ip_address}")
    else:
        print(f"Access Denied - {ip_address} Flagged for Review")
