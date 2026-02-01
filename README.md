# 🤖 Telegram AI Lead Collection Bot (n8n)

An AI-powered Telegram bot built with **n8n** that collects user messages, extracts structured information using an AI Agent, stores it in **Google Sheets**, and responds back to the user automatically.

---

## 🚀 Features

- 📩 Telegram message intake
- 🧠 AI Agent for structured data extraction
- 🧾 Data parsing using Set node
- 📊 Google Sheets integration
- 💬 Automated Telegram responses
- ⚡ No memory, no tools, clean and reliable workflow

---

## 🧩 Workflow Overview

Telegram Trigger
↓
AI Agent
↓
Set Node (Parse Fields)
↓
Google Sheets (Append Row)
↓
Telegram Respond



---

## 🛠️ Tech Stack

- **n8n**
- **Telegram Bot API**
- **AI Agent (LLM)**
- **Google Sheets API**

---

## 📂 Files

- `telegram-ai-lead-bot.json` → n8n workflow export

---

## ⚙️ Setup Instructions

1. Import the workflow JSON into n8n
2. Configure:
   - Telegram Bot credentials
   - Google Sheets credentials
   - AI Agent credentials
3. Activate the workflow
4. Send a message to the Telegram bot

---

## 🧪 Example Input

Hi, my name is John Doe.
My email is john@example.com.
I want to book a tour this weekend.


---

## ✅ Output

- Structured data saved in Google Sheets
- Confirmation message sent back to Telegram

---

## 🧠 What I Learned

- Building AI-powered automations with n8n
- Handling structured AI outputs safely
- Integrating Telegram, AI, and Google Sheets
- Designing clean, reliable workflows

---

## 📌 Author

**Shahriar Hossain Alif**  
Frontend Developer | Automation & AI Enthusiast
