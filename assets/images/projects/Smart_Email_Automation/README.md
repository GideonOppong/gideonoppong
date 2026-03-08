Secure AI Automation Ecosystem

A No-Code AI Automation System for Secure Email Filtering and Data Analysis

🚀 Project Overview

The Secure AI Automation Ecosystem is a no-code automation system designed to securely filter, categorize, and analyze Gmail data using modern automation tools.

The system connects multiple platforms to create a secure automated workflow that improves inbox management while demonstrating principles of cybersecurity, automation, and secure system design.

This project was developed as part of the AI App Development Program at Co.Lab.

🎯 Project Goals

Automate email filtering and categorization

Reduce unwanted promotional and newsletter emails

Provide a dashboard for managing blocked senders

Demonstrate secure automation architecture

Apply cybersecurity best practices in a no-code environment

🧰 Technology Stack
Tool	Role
AppSheet	Frontend user interface
Google Sheets	Backend database
Make	Workflow automation
Gmail	Email data source
OpenAI (optional)	Email classification and analysis
🧩 System Architecture
User Interface (AppSheet)
        ↓
Google Sheets Database
        ↓
Make Automation Scenario
        ↓
Gmail API (Email Processing)
        ↓
Action Logs → Google Sheets
        ↓
Dashboard Updates → AppSheet
🔄 Workflow

User adds blocked senders or filtering rules in AppSheet

Data is stored in Google Sheets

Make monitors updates and triggers automation

Gmail API searches incoming messages

Emails matching rules are:

Deleted

Archived

Labeled

Automation logs the action back to Google Sheets

Dashboard updates appear instantly in AppSheet

🛡️ Security Design Considerations

This project integrates basic cybersecurity practices:

Principle of Least Privilege

Controlled API access scopes

Secure automation triggers

Minimal data exposure between services

System design aligned with OWASP security principles


---

## 📌 . AI Automation Project – ai-automation/README.md**

 ## 🤖 AI Automation Project (Co.Lab)

This project automates Gmail analysis using:
- Make.com
- AppSheet
- Google Sheets
- OpenAI API

## 📸 System Walkthrough
### The User Interface
![App UI]([assets/images/Screenshot 2026-02-23 222150.png](https://github.com/GideonOppong/gideonoppong/blob/0a86ecff69938fb3e8f01fb1c28d58e728b42717/assets/images/Screenshot%202026-02-23%20222150.png))
 Custom AppSheet dashboard designed to prevent unauthorized data entry.*


## 🧱 Backend
![google sheet]([assets/images/Google Sheets my app data base.png](https://github.com/GideonOppong/gideonoppong/blob/2a82cf76e1e9878e65b48bb44de94e42560fd49d/assets/images/Google%20Sheets%20my%20app%20data%20base.png))
**Database:** Google Sheets (Protected ranges and audit logs)


### The Automation Logic
![Make Scenario]([../../assets/images/automation make.com.png](https://github.com/GideonOppong/gideonoppong/blob/ddec62098566590b113c979f325a97eec65026a2/assets/images/automation%20make.com.png))
 Make.com workflow featuring error-handling routes to prevent data leakage during failures.*



## 🔐 Security Features
- OAuth-limited scopes
- Input validation
- Restricted access flows
- Secure API handling

🔗 Live Demo
(Add your AppSheet public link here)

📜 License

This project is part of a personal learning portfolio and is open for educational use.

👤 Author

Gideon Oppong
Cybersecurity Aspirant | AI App Developer

🔗 LinkedIn
https://www.linkedin.com/in/gideonoppong/
