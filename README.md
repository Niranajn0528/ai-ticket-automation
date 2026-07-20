# 🤖 AI Ticket Automation

> AI-powered Telecom Ticket Automation system that automatically classifies incidents, detects severity, generates Root Cause Analysis (RCA), creates Jira tickets, and sends real-time notifications using LLMs and workflow automation.

![Status](https://img.shields.io/badge/Project-Completed-success)
![AI](https://img.shields.io/badge/LLM-Groq-blue)
![Automation](https://img.shields.io/badge/n8n-Workflow-orange)
![Telecom](https://img.shields.io/badge/Domain-Telecom-green)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

# 📌 Project Overview

AI Ticket Automation is an intelligent incident management solution designed for Telecom Network Operations Centers (NOC).

The system automatically receives telecom incidents, analyzes them using a Large Language Model (LLM), identifies severity, generates Root Cause Analysis (RCA), creates Jira tickets, stores incident records, and notifies engineers through email.

This eliminates repetitive manual ticket creation and significantly accelerates incident response.

---

# 🚀 Key Features

- 🤖 AI Incident Classification
- 🚨 Automatic Severity Detection
- 🔍 Root Cause Analysis (RCA)
- 🎯 Priority Assignment
- 🎫 Jira Ticket Creation
- 📧 Automated Email Alerts
- 📊 Google Sheets Incident Database
- 📈 Executive Dashboard
- ⚡ End-to-End Workflow Automation

---

# 🏗 Solution Architecture

```
Telecom Alarm / Incident

        │

        ▼

Webhook Trigger

        │

        ▼

n8n Workflow

        │

        ▼

Groq LLM

        │

        ▼

AI Incident Analysis

        │

 ┌──────┼───────────┐

 ▼      ▼           ▼

Severity

RCA

Priority

        │

        ▼

Jira Ticket

        │

        ▼

Google Sheets

        │

        ▼

Email Notification
```

---

# 🛠 Technology Stack

| Category | Technologies |
|-----------|--------------|
| AI | Groq LLM |
| Workflow Automation | n8n |
| Programming | JavaScript |
| APIs | REST APIs |
| Ticketing | Jira Cloud |
| Database | Google Sheets |
| Notifications | Gmail |
| Infrastructure | Linux |

---

# 📂 Repository Structure

```
ai-ticket-automation

├── docs
├── images
├── sample-data
├── workflow
└── README.md
```

---

# ⚙ Workflow

```
Webhook

↓

Groq LLM

↓

AI Analysis

↓

JSON Parser

↓

Severity Check

↓

Jira Ticket Creation

↓

Google Sheets Logging

↓

Email Notification
```

---

# 📸 Screenshots

- Cover Banner
- Workflow
- Architecture Diagram
- AI Output
- Jira Ticket
- Email Alert
- Dashboard

---

# 📈 Business Benefits

✔ Eliminates manual ticket creation

✔ Accelerates incident response

✔ Standardizes Root Cause Analysis

✔ Improves operational efficiency

✔ Enables intelligent ticket prioritization

✔ Enhances incident visibility

✔ Reduces Mean Time To Resolution (MTTR)

---

# 🔥 Sample AI Output

```json
{
  "ticket_id": "INC-20260722-001",
  "severity": "Critical",
  "priority": "P1",
  "issue_type": "PFCP Association Failure",
  "network_element": "UPF",
  "root_cause": "UPF lost communication with SMF due to PFCP session timeout.",
  "recommendation": "Restart PFCP association and verify N4 connectivity.",
  "assignment_team": "Core Network Team",
  "escalation": true
}
```

---

# 🚀 Future Enhancements

- ServiceNow Integration
- Microsoft Teams Notifications
- Slack Alerts
- Multi-Agent AI
- Historical Incident Search
- Vector Database
- RAG Knowledge Base
- Predictive Incident Analysis

---

# 👨‍💻 Author

**Niranjan Kumar K**

AI Automation Engineer | Telecom | AIOps

Building AI-powered telecom automation solutions using LLMs, n8n, REST APIs, workflow orchestration, and intelligent incident management.
