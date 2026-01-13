# n8n-templates

A chill collection of my favorite n8n automation. Ready to import, remix, and run 🤖 🚀

---

## 📂 What's Inside

This repo is just a flat collection of `.json` files-each one an exported n8n workflow. No nested folders, no surprises. Grab any file you like and import it straight into your n8n instance.

---

## 🛠️ Prerequisites

- **n8n** installed (self-hosted or Desktop App).  
- Node.js ≥ v14 if you’re running n8n locally.  
- Basic familiarity with n8n’s UI (credentials, triggers, nodes).

---

## 🔄 Importing Workflows

### Via the UI

- In your n8n dashboard, click Workflows in the side menu.
- Hit the Import button (top right).
- Navigate to your cloned folder and select any .json file.
- Click Import → voilà, your flow appears.
- Toggle Activate if you want it to run on its trigger.

### Via CLI

```console
n8n import:workflow --input=./any-workflow.json
```

---

## 📋 Workflow Catalog

### AI Accounting Staff
**File:** `ai-accounting-staff.json`

> Automatically generate journal entries in ERPNext using AI. Just send a transaction description and amount — the AI maps it to the correct Chart of Accounts.

---

### AI News WhatsApp Channel
**File:** `ai-news-whatsapp-channel.json`

> Scheduled AI agent that curates daily AI news from multiple sources (TheDecoder, TechCrunch, Google) and broadcasts summaries to a WhatsApp channel via WAHA.

---

### AI WordPress Post Maker
**File:** `ai-wordpress-post-maker.json`

> Auto-generates SEO-friendly blog articles with AI, creates featured images using DALL-E, and publishes them to WordPress on a schedule.

---

### Biteship Ongkir Chatbot
**File:** `biteship-ongkir-chatbot.json`

> E-commerce chatbot that handles product inquiries, calculates shipping costs via Biteship API, and guides customers through checkout with payment instructions.

---

### Chatwoot AI Agent
**File:** `chatwoot-ai-agent.json`

> Connects an AI agent to Chatwoot for automated customer support. Responds to incoming messages with context-aware replies using conversation memory.

---

### Google Sheets to Data Tables Migration
**File:** `google-sheets-to-data-tables-migration.json`

> Migrates data from Google Sheets to n8n Data Tables with duplicate checking to avoid re-importing existing rows.

---

### HR AI Agent
**File:** `hr-ai-agent.json`

> AI-powered job application screening. Accepts CV uploads via form, extracts PDF content, and scores candidates against job requirements (age, education, experience, skills).

---

### Scrap Mitra10 Price
**File:** `scrap-mitra10-price.json`

> Price monitoring bot that scrapes product prices from Mitra10 website hourly and sends Telegram alerts when prices drop below a threshold.

---

### Shopping E-commerce Chatbot
**File:** `shopping-ecommerce-chatbot.json`

> Full-featured WhatsApp e-commerce bot with product catalog, order creation, payment validation, and customer ignore list. Handles @lid to @c.us conversion for WAHA.

---

### Simple RAG
**File:** `simple-rag.json`

> Basic Retrieval-Augmented Generation setup using Pinecone vector store. Upload PDFs via form, then chat with an AI that answers based on the uploaded documents.

---

### SSH AI Agent
**File:** `ssh-ai-agent.json`

> Telegram-based sysadmin assistant that translates natural language commands to SSH operations. Includes approval workflow before executing commands on remote servers.

---

### Voice AI Agent (MAIA Router)
**File:** `voice-ai-agent-maia-router.json`

> Voice-to-voice AI assistant. Receives audio via webhook, transcribes with Whisper, processes with AI agent, and returns synthesized speech response.

---

### WAHA Convert LID + Hold Chat
**File:** `waha-convert-lid-hold-chat-data-table.json`

> WhatsApp chatbot template with @lid to @c.us conversion, ignore list management using n8n Data Tables, and typing indicators for human-like responses.

---

### WhatsApp AI Google Calendar
**File:** `whatsapp-ai-google-calendar.json`

> Personal assistant that manages Google Calendar via WhatsApp. Check schedules, create events, and get reminders through natural conversation.

---

### WhatsApp WAHA Hold Chat
**File:** `whatsapp-waha-hold-chat.json`

> WhatsApp chatbot with agent handoff support. Uses WAHA labels to "hold" conversations when a human agent takes over from the app.

---

#### Happy automating! ✨

---

## 👨‍💻 Credits

Made with ☕ by **Aji Prakoso**

| | |
|---|---|
| 🎓 | [n8n & Automation eCourse](https://classroom.jipraks.com) |
| 📸 | [@jipraks on Instagram](https://instagram.com/jipraks) |
| 🎬 | [Aji Prakoso's YouTube](https://youtube.com/@jipraks) |
| 🌐 | [About Aji Prakoso](https://www.jipraks.com) |
