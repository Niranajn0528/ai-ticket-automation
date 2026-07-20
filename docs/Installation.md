# ⚙ Installation Guide

## Prerequisites

- n8n
- Groq API Key
- Jira Cloud Account
- Google Sheets
- Gmail Credentials

---

## Clone Repository

```bash
git clone https://github.com/yourusername/ai-ticket-automation.git
```

---

## Import Workflow

Import

```
workflow/ai-ticket-automation.json
```

into n8n.

---

## Configure Credentials

### Groq

Configure your API Key.

---

### Jira Cloud

Provide

- URL
- Email
- API Token

---

### Google Sheets

Authenticate Google Account.

---

### Gmail

Configure Gmail OAuth or SMTP.

---

## Execute

Trigger the webhook with a telecom incident payload.

The workflow automatically

- analyzes incident
- detects severity
- generates RCA
- creates Jira ticket
- stores incident
- sends email notification

---