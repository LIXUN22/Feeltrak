# FeelTrak– Sentiment Analyzer App

**FeelTrak** is a fun, AI-powered web app that analyzes the sentiment of your input using cutting-edge NLP models from Hugging Face.

---

## 🚀 Features

- 🔍 Real-time sentiment detection using Transformers
- ✨ Friendly UI with emojis and confidence score
- 📜 View recent logs (last 10 entries)
- 🔁 Clear history instantly
- 🎨 Clean, mobile-responsive frontend (React)
- 🌐 Hosted using **Vercel** (frontend) and **Render** (backend)

---

## 🧰 Tech Stack

- **Frontend**: React, CSS
- **Backend**: Flask, Transformers (Hugging Face), SQLite
- **Model**: `distilbert-base-uncased-finetuned-sst-2-english`
- **Deployment**: Vercel (frontend), Render (backend)

---

## 🛠️ Local Setup

### 1. Backend (Flask API)

```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python app.py
```

### 2. Frontend (React App)
```bash
cd frontend
npm install
npm start
```
## 🔗 Make sure your frontend uses the correct backend API URL (http://localhost:5000 in dev, Render URL in production).

