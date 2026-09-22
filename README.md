# 🤖 Rishabh AI — Enterprise 24/7 WhatsApp Multimodal Bot & CRM

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Runtime](https://img.shields.io/badge/Node.js%20%2F%20Python-Backend-3776AB?style=flat&logo=python&logoColor=white)](#)
[![Google Gemini](https://img.shields.io/badge/Google_Gemini-AI_Engine-8E75C2?style=flat&logo=google&logoColor=white)](#)
[![WhatsApp Cloud API](https://img.shields.io/badge/Meta_WhatsApp-Cloud_API-25D366?style=flat&logo=whatsapp&logoColor=white)](#)
[![Docker](https://img.shields.io/badge/Docker-Containerized-2496ED?style=flat&logo=docker&logoColor=white)](#)
[![SQLite](https://img.shields.io/badge/SQLite-CRM_Database-003B57?style=flat&logo=sqlite&logoColor=white)](#)

An intelligent, cloud-native **24/7 WhatsApp AI Assistant and CRM Lead Automation System** engineered with **Meta WhatsApp Cloud API** and **Google Gemini AI**. Built to handle high-concurrency customer inquiries, multimodal image/voice document understanding, and automated CRM database lead logging.

---

## 🚀 Key Features

- 🧠 **Google Gemini AI Integration:** Context-aware bilingual conversational intelligence (Hindi & English).
- 👁️ **Multimodal Capabilities:** Real-time OCR receipt scanning, document reading, and voice note transcription.
- ⚡ **24/7 Webhook Service:** High-performance Meta WhatsApp Cloud API webhook handler for instant response delivery.
- 🗄️ **Automated CRM Database:** Automatically captures customer contact info, query intent, and timestamps into SQLite/MySQL.
- 🐳 **Docker Containerization:** One-command production deployment with isolated dependencies and minimal memory footprint.

---

## 🏗️ Architecture Flow

```text
User WhatsApp Message 📲
        │
        ▼
Meta WhatsApp Cloud API (Webhooks)
        │
        ▼
Node.js / Python Backend Engine ⚙️
        ├──► Google Gemini AI (Multimodal NLU & Vision) 🧠
        └──► SQLite / MySQL Lead CRM Database 🗄️
        │
        ▼
Instant Automated Reply to User ⚡
```

---

## 🛠️ Tech Stack

- **Runtime & Language:** Node.js / JavaScript (ES6+), Python 3.10+
- **AI Model:** Google Gemini AI API (Multimodal Flash)
- **API & Messaging:** Meta WhatsApp Cloud API, RESTful Webhooks
- **Database:** SQLite / MySQL with schema migrations
- **DevOps:** Docker, Docker Compose, Git & GitHub

---

## 💻 Local Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/rishu-builds/rishabh-whatsapp-bot.git
cd rishabh-whatsapp-bot
```

### 2. Install dependencies
```bash
npm install
```

### 3. Configure Environment Variables
Create a `.env` file in the root directory:
```env
PORT=3000
WHATSAPP_TOKEN=your_meta_whatsapp_cloud_token
PHONE_NUMBER_ID=your_whatsapp_phone_number_id
VERIFY_TOKEN=your_custom_webhook_verify_token
GEMINI_API_KEY=your_google_gemini_api_key
```

### 4. Run the Bot
```bash
npm start
# or
node bot.js
```

---

## 🐳 Docker Deployment

To build and run the Docker container:

```bash
# Build Docker image
docker build -t rishabh-whatsapp-bot .

# Run container
docker run -d -p 3000:3000 --name whatsapp-bot --env-file .env rishabh-whatsapp-bot
```

---

## 👨‍💻 Author

**Rishabh Yadav**  
- 💼 LinkedIn: [Rishabh Yadav](https://www.linkedin.com/in/rishabh-yadav-00a235349)  
- 💻 GitHub: [@rishu-builds](https://github.com/rishu-builds)  
- ✉️ Email: [ysrishabh017@gmail.com](mailto:ysrishabh017@gmail.com)
