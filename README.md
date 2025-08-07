# 🛡️ LLM-Powered Insurance Policy Assistant

This is a full-stack project that helps users upload their insurance policy documents (PDF/DOCX), ask natural language questions about coverage, and get intelligent answers using LLMs like **Gemini** or **GROQ**.

---

## 📁 Project Structure

- hack-rx-bajaj/
- ├── app/
- │    ├── main.py # FastAPI entry point
- │    ├── routes/
- │    │     ├── query.py # Query endpoint
- │    │     └── uploads.py # File upload handling
- │    └── services/
- │    └── llm_reasoner.py # Logic for LLM API interaction
- │
- ├── frontend/
- │   ├── index.html
- │   ├── about.html
- │   ├── services.html
- │   ├── contact.html
- │   ├── style.css
- │   └── script.js
- │
- ├── data/uploads/ # Uploaded documents
- ├── prompts/ # Custom prompt templates
- │   ├── parse_query.txt
- │   └── generate_decision.txt
- │
- ├── .env # Environment secrets (not committed)
- ├── requirements.txt
- ├── run.py # Uvicorn server launcher
- └── README.md



---

## ⚙️ Features

- Upload insurance documents (PDF/DOCX)
- Parse and chunk documents for retrieval
- Ask free-text questions about policy coverage
- LLM (Gemini/Groq) parses and reasons over relevant clauses
- Clean frontend UI (HTML/CSS/JS)
- Hosted via **FastAPI backend + Render static frontend**

---

## 🚀 Getting Started

### ✅ Install Dependencies
```bash
pip install -r requirements.txt
python run.py

