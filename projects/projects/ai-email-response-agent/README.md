# 📧 AI Email Response Agent

An AI-powered workflow built with **n8n** and **Google Gemini** that automatically monitors incoming emails, identifies messages that require a response, and generates replies using Artificial Intelligence.

---

## 🚀 Overview

This workflow demonstrates how AI Agents can be integrated into email automation to improve response efficiency and reduce manual work.

---

## 🛠️ Technologies

- n8n
- Google Gemini
- Gmail
- AI Agent
- Simple Memory

---

## 📊 Workflow

```text
Gmail Trigger
      │
      ▼
Conditional Filter
      │
      ▼
AI Agent (Google Gemini)
      │
      ▼
Reply to Gmail
```

---

## 📸 Workflow Preview

> Replace the image below with the latest version of the workflow.

![Workflow](workflow.png)

---

## ⚙️ How It Works

1. Monitors incoming emails using Gmail Trigger.
2. Applies a conditional filter to determine whether the message should be processed.
3. Sends the email content to a Google Gemini AI Agent.
4. Generates an AI-powered response.
5. Sends the reply back to the original email thread.

---

## 📂 Files

| File | Description |
|------|-------------|
| `workflow.json` | n8n workflow ready to import |
| `workflow.png` | Workflow screenshot |
| `README.md` | Project documentation |

---

## 📥 Import into n8n

1. Download `workflow.json`.
2. Open n8n.
3. Select **Import from File**.
4. Configure your own credentials.
5. Execute the workflow.

> **Note:** Credentials are not included in the exported workflow.
