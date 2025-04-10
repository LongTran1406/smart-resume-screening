# Smart Resume Screening Platform

An AI-powered SaaS platform to parse, analyze, and rank job resumes using NLP and deep learning — built with a robust backend, modern frontend, and end-to-end DevOps pipeline.

## 🔧 Tech Stack
- **Frontend**: React.js
- **Backend**: FastAPI + PostgreSQL
- **AI**: BERT / Sentence Transformers
- **Infra**: Docker, GitHub Actions, AWS/GCP

## 📦 Features
- Resume & job description uploads
- Semantic matching with job fit scores
- AI-powered ranking
- Chatbot assistant (planned)
- Admin dashboard

## 🚀 Getting Started
```bash
git clone https://github.com/yourname/smart-resume-screening.git
cd smart-resume-screening


smart-resume-screening/
├── backend/
│   ├── app/
│   │   ├── api/                # FastAPI routes
│   │   ├── models/             # Pydantic models
│   │   ├── services/           # Logic for parsing, matching
│   │   ├── database.py         # DB setup
│   │   └── main.py             # FastAPI entrypoint
│   ├── requirements.txt
│   └── Dockerfile
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.jsx
│   ├── package.json
│   └── Dockerfile
├── models/
│   ├── matcher/
│   │   ├── model.py
│   │   ├── train.py
│   │   └── inference.py
│   ├── requirements.txt
│   └── Dockerfile
├── infra/
│   ├── docker-compose.yml
│   ├── nginx.conf
│   └── README.md
├── docs/
│   ├── system_design.md
│   ├── architecture_diagram.png
│   └── setup_guide.md
├── .github/
│   └── workflows/
│       └── ci.yml              # GitHub Actions CI/CD
├── .gitignore
└── README.md
