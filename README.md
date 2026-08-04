# AI Customer Support Agent using Zapier

## Overview

Customer support teams often spend significant time responding to repetitive inquiries such as product information, policies, FAQs, and service-related questions.

This project aims to reduce manual workload by creating an **AI-powered Customer Support Agent** using **Zapier**, a no-code automation platform for building AI-driven workflows.

The agent automates customer email handling by analyzing incoming mails, understanding customer queries and intent, retrieving relevant information from a predefined knowledge base, deciding the appropriate action based on its confidence level and escalating uncertain cases to humans in order to improve customer support efficiency while reducing the risk of inaccurate responses.

---

## Key Features

### 📩 Email Understanding
- Monitors incoming customer emails
- Extracts customer queries and relevant details

### 📚 Knowledge-Based Responses
- Uses uploaded reference documents as the source of truth
- Retrieves relevant information before generating responses
- Reduces hallucination by grounding answers in provided data

### 🧠 Intent Detection
The AI agent identifies the purpose of customer emails, such as:

- Service-related questions
- Policy-related requests
- General support queries

### 📊 Confidence-Based Decision Making

The agent evaluates its confidence before performing actions.

**High Confidence**
- Generates a Gmail reply draft to human review before sending

**Low Confidence**
- Escalates the issue through WhatsApp notification for human intervention

### 👥 Human-in-the-Loop Automation

Instead of fully autonomous responses, the workflow maintains human oversight for uncertain cases, improving reliability and response quality.

---

## Technologies Used

- **Zapier** - No-code AI workflow automation
- **AI Agent Workflow**
- **Gmail Integration**
- **WhatsApp Integration**
- **Google Drive Knowledge Base**
- **Prompt Engineering**

---

## Knowledge Base

The AI agent uses documents stored in Google Drive.

These documents act as the agent's knowledge source to generate accurate and context-aware responses.

---

## Business Impact

This AI agent can help organizations:

✅ Reduce repetitive customer support workload  
✅ Provide faster response times  
✅ Improve consistency of customer responses  
✅ Maintain human oversight for complex cases  
✅ Scale customer support operations efficiently  

---
