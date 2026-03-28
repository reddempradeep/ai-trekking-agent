# ai-trekking-agent
AI agent that recommends trekking trails based on weather and air quality

# 🥾 AI Trekking Recommendation Agent

## 🚀 Overview
This project is an AI-powered trekking recommendation agent that suggests the best hiking trail based on real-time weather and air quality conditions.

It integrates APIs, applies decision logic, and automatically sends daily recommendations via email.

---

## 🧠 Features
- 🌡️ Weather-based filtering
- 🌫️ Air Quality (AQI) safety checks
- 🏔️ Intelligent trail recommendation
- 📧 Automated email notifications
- 🤖 AI agent with tool-based reasoning

---

## 🏗️ Architecture

Schedule Trigger → AI Agent → APIs → Decision → Email

---

## ⚙️ Tech Stack
- n8n (workflow automation)
- OpenAI / Gemini (LLM)
- OpenWeatherMap API
- AirNow API
- Google Sheets
- Gmail API

---

## 🧠 How It Works

1. Fetches real-time weather data
2. Fetches AQI data
3. Loads trail dataset
4. Applies safety and selection logic
5. Recommends best trail or cancels hike
6. Sends email automatically

---

## 📸 Screenshots

### Workflow
![Workflow](workflow.png)

### Email Output
![Email](email.png)

---

## ▶️ How to Run

1. Import `workflow.json` into n8n
2. Add your API keys:
   - OpenWeatherMap
   - AirNow
   - OpenAI/Gemini
3. Connect Gmail
4. Activate workflow

---

## 💡 Future Improvements
- Trail scoring system
- User preferences
- Mobile notifications

---

## 👤 Author
Reddem Pradeep Kumar Reddy
