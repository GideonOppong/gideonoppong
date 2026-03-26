![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![Security](https://img.shields.io/badge/Security-Verified_by_NIST_CSF-blue?style=for-the-badge&logo=google-cloud&logoColor=white)

# 🤖 Secure AI Automation Ecosystem
> **A No-Code AI Automation System for Secure Email Filtering and Data Analysis**

---

## 🚀 Project Overview
The **Secure AI Automation Ecosystem** is a no-code automation system designed to securely filter, categorize, and analyze Gmail data. Developed as part of the **Co.Lab AI App Development Program**, this system demonstrates the intersection of functional automation and cybersecurity principles.

### 📊 Key Features
* **Automated Workflow:** Seamless Gmail filtering and categorization.
* **Centralized Dashboard:** AppSheet interface for managing custom blocking rules.
* **Secure Architecture:** Modular design emphasizing data integrity and PoLP.
* **Automation Logging:** Real-time action tracking via Google Sheets.

---

## 🛡️ NIST CSF Implementation Mapping
I designed this ecosystem to align with the **NIST Cybersecurity Framework**, ensuring that every automated step serves a defensive purpose.

| NIST Function | Project Application | Analyst Responsibility |
| :--- | :--- | :--- |
| **IDENTIFY** | Defined Gmail data and API keys as critical assets. | **Asset Management:** Cataloging software/data sensitive points. |
| **PROTECT** | Applied **Least Privilege** via OAuth scopes (Gmail.Send only). | **Access Control:** IAM management and secure authentication. |
| **DETECT** | Used **SQL Auditing** to monitor for anomalies in access logs. | **Continuous Monitoring:** Analyzing logs for unauthorized patterns. |
| **RESPOND** | Built automated **AI filtering logic** to isolate threats. | **Incident Analysis:** Executing playbooks to contain threats. |
| **RECOVER** | Maintained a **Google Sheets Audit Log** for restoration. | **Recovery Planning:** Using logs to return to normal operations. |

---

## 🧰 Technology Stack
| Tool | Role |
| :--- | :--- |
| **AppSheet** | Frontend User Interface |
| **Google Sheets** | Backend Database (Protected Ranges) |
| **Make.com** | Workflow Automation Engine |
| **Gmail API** | Secure Email Data Source |
| **OpenAI** | Intelligent Email Classification |

---

## 🧩 System Architecture & Workflow
The data flows through a secured pipeline to ensure no-code reliability:
1. **Define:** User adds blocked senders or filtering rules in AppSheet.
2. **Store:** Data is stored in a hardened Google Sheets database.
3. **Trigger:** Make.com monitors updates and triggers the automation.
4. **Analyze:** OpenAI classifies incoming messages based on user rules.
5. **Execute:** Gmail API performs actions (Delete/Archive/Label).
6. **Log:** Actions are recorded back to Sheets for instant Dashboard updates.

---

## 📸 System Walkthrough

### 📱 The User Interface
![App UI](https://github.com/GideonOppong/gideonoppong/blob/main/assets/images/Screenshot%202026-02-23%20222150.png?raw=true)
*Figure 1: Custom AppSheet dashboard designed with input validation to prevent unauthorized data entry.*

### 🧱 The Backend Database
![Google Sheets](https://github.com/GideonOppong/gideonoppong/blob/main/assets/images/Screenshot%202026-02-20%20231147%20my%20app%20data%20base.png?raw=true)
*Figure 2: Google Sheets database utilizing protected ranges and audit logs to track automation history.*

### ⚙️ The Automation Logic
![Make Scenario](https://github.com/GideonOppong/gideonoppong/blob/main/assets/images/automation%20make.com.png?raw=true)
*Figure 3: Make.com workflow featuring error-handling routes to prevent data leakage during failures.*

---

## 🧠 Project Retrospective

#### 🎓 What I Learned
* **Security-First Design**: I mastered applying **OAuth 2.0** and **Least Privilege** to protect personal data while using automated tools.
* **Scientific Problem Solving**: Leveraging my **Integrated Science** background, I treated automation failures as lab variables to isolate and fix workflow logic.

#### 🚀 Future Roadmap (v2.0)
* **Threat Intel Integration**: Automatically updating blocking rules based on global phishing trend feeds.
* **Encryption**: Implementing additional layers for sensitive email summaries.

---

## 👤 Author
**Gideon Oppong**
*Cybersecurity Aspirant | AI App Developer | Tech Transitioner*

🤝 **LinkedIn:** [linkedin.com/in/gideonoppong](https://www.linkedin.com/in/gideonoppong/)
🔗 **Live Demo:** [AppSheet Project Link](https://www.appsheet.com/start/db65050a-d41a-4dc3-b753-ac7d6ce13cb2)
