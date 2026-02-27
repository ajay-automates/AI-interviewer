<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=8,14,22&height=170&section=header&text=AI%20Interviewer&fontSize=52&fontAlignY=35&animation=twinkling&fontColor=ffffff&desc=RAG-Powered%20Mock%20Interview%20System&descAlignY=55&descSize=18" width="100%" />

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](.)
[![RAG](https://img.shields.io/badge/RAG-Pipeline-FF6B6B?style=for-the-badge)](.)
[![AI Powered](https://img.shields.io/badge/AI-Powered-8B5CF6?style=for-the-badge)](.)
[![Docker](https://img.shields.io/badge/Docker-Ready-2496ED?style=for-the-badge&logo=docker&logoColor=white)](.)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

**Practice interviews with an AI that knows your resume, the job description, and asks relevant follow-up questions.**

</div>

---

## What This Does

AI Interviewer is a RAG-powered mock interview system that conducts realistic job interviews. It ingests your resume and target job description, generates contextual questions, evaluates your responses, and provides structured feedback — all powered by retrieval-augmented generation for grounded, relevant questioning.

---

## Architecture

```
Resume + Job Description
        │
        ▼
Document Ingestion & Chunking
        │
        ▼
Vector Embedding + Storage
        │
        ▼
RAG Interview Engine
        │
        ├──→ Generate role-specific questions
        ├──→ Retrieve relevant context per question
        ├──→ Evaluate responses with citations
        └──→ Adaptive follow-up questions
        │
        ▼
Structured Feedback + Score
```

---

## Key Features

| Feature | Details |
|---------|---------|
| **RAG-Grounded Questions** | Questions generated from actual resume + JD context |
| **Adaptive Follow-ups** | AI asks deeper questions based on your responses |
| **Multi-Format Support** | Upload PDF, DOCX, TXT resumes and job descriptions |
| **Response Evaluation** | Scored on relevance, depth, specificity, and communication |
| **Session Summary** | Comprehensive feedback after each interview session |
| **Docker Ready** | Containerized for easy deployment |

---

## Quick Start

```bash
git clone https://github.com/ajay-automates/AI-interviewer.git
cd AI-interviewer
pip install -r requirements.txt
# Configure your API keys in .env
python main.py
```

---

## Tech Stack

`Python` `RAG` `Vector Database` `LLM API` `Docker` `Document Processing`

---

## Related Projects

| Project | Description |
|---------|-------------|
| [InterviewTwin](https://github.com/ajay-automates/InterviewTwin) | Next.js-based interview practice platform |
| [Advanced Resume Analyzer](https://github.com/ajay-automates/advanced-resume-analyzer-qlora) | QLoRA fine-tuned Gemma 3 for resume-job fit |
| [AI Support Agent](https://github.com/ajay-automates/ai-support-agent) | Production RAG chatbot with LangSmith observability |

---

<div align="center">

**Built by [Ajay Kumar Reddy Nelavetla](https://github.com/ajay-automates)** · February 2026

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=8,14,22&height=100&section=footer" width="100%" />

</div>
