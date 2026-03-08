# 🤖 Secure AI Automation Ecosystem
> **A No-Code AI Automation System for Secure Email Filtering and Data Analysis**

---

## 🚀 Project Overview
The **Secure AI Automation Ecosystem** is a no-code automation system designed to securely filter, categorize, and analyze Gmail data. Developed as part of the **Co.Lab AI App Development Program**, this system demonstrates the intersection of functional automation and cybersecurity principles.

---

## 🎯 Project Goals
* **Automate** email filtering and categorization to reduce inbox clutter.
* **Centralize** blocked sender management via a custom dashboard.
* **Demonstrate** secure automation architecture in a no-code environment.
* **Apply** cybersecurity best practices, including the Principle of Least Privilege.

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

## 🧩 System Architecture
The data flows through a secured pipeline to ensure no-code reliability:
1. **User Interface (AppSheet):** User defines filtering rules.
2. **Google Sheets:** Rules are stored in a hardened database.
3. **Make.com:** Automation triggers via secure webhooks.
4. **Gmail API:** Executes actions (Delete/Archive/Label) based on AI analysis.
5. **Feedback Loop:** Logs are written back to Sheets for instant Dashboard updates.



---

## 📸 System Walkthrough

### 📱 The User Interface
![App UI](https://github.com/GideonOppong/gideonoppong/blob/main/assets/images/Screenshot%202026-02-23%20222150.png?raw=true)
*Figure 1: Custom AppSheet dashboard designed with input validation to prevent unauthorized data entry.*

### 🧱 The Backend Database
![Google Sheets](https://github.com/GideonOppong/gideonoppong/blob/main/assets/images/Screenshot%202026-02-20%20231147%20my%20app%20data%20base.png?raw=true)
*Figure 2: Google Sheets database utilizing protected ranges and audit logs to track automation history.*

### ⚙️ The Automation Logic
![Make Scenario](../../assets/images/automation%20make.com.png)
*Figure 3: Make.com workflow featuring error-handling routes to prevent data leakage during system failures.*

---

## 🛡️ Security Design & Features
Following my **Google Cybersecurity** training, I integrated several defensive layers:
* **Principle of Least Privilege (PoLP):** API access is restricted to the specific scopes required for email management only.
* **OAuth 2.0 Integration:** Secure authentication handling between all platforms.
* **Minimal Data Exposure:** OpenAI modules only process non-sensitive header metadata.
* **OWASP Alignment:** Designed to mitigate risks associated with broken access control and insecure outputs.

---

## 👤 Author
**Gideon Oppong**
*Cybersecurity Aspirant | AI App Developer | Tech Transitioner*

🤝 **LinkedIn:** [linkedin.com/in/gideonoppong](https://www.linkedin.com/in/gideonoppong/)
