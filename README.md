# 🏠 RentWise AI

**Smart AI-powered rental platform for property management and tenant experience.**  
Pay rent, understand leases, submit issues, and predict rent pricing — all powered by AI.

---

## 🚀 Features

- ✅ Rent payments via mpesa
- 📝 Lease auto-summarization (NLP)
- 📄 Document Q&A (e.g. lease questions)
- 📷 AI-powered property condition reports
- 💬 Voice assistant for accessibility
- 📊 Predictive rent pricing based on real estate data

---

## 🤖 Powered by Hugging Face Tasks

| Task                         | Purpose                               |
|------------------------------|----------------------------------------|
| Document Question Answering  | Understand leases and policies         |
| Text Generation              | Summarize or generate contract text    |
| Image-to-Text                | Property damage/image analysis         |
| Text-to-Speech               | Read lease clauses aloud               |
| Tabular Classification       | Rent price prediction                  |
| Visual Question Answering    | Legal damage detection from images     |

---

## 💻 Tech Stack

- **Frontend:** React + TailwindCSS
- **Mobile:** React Native (or Flutter)
- **Backend:** FastAPI (Python)
- **AI Integration:** Hugging Face Transformers (inference API or self-hosted)
- **Database:** PostgreSQL + Redis
- **Payments:** mpesa
- **Voice:** Web Speech API / Hugging Face TTS
- **Deployment:** AWS, Vercel, Docker

---

## 🛠️ Installation

```bash
# Backend
cd backend
pip install -r requirements.txt
uvicorn main:app --reload

# Frontend
cd frontend
npm install
npm run dev
