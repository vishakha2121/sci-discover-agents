# 🚀 Sci-Discover-Agents

> **Five AI agents. One scientific breakthrough.**

A multi-agent AI platform where independent research agents collaborate 
autonomously to propose, simulate, review, and validate scientific 
discoveries — just like a real research lab, but fully automated.

![Status](https://img.shields.io/badge/status-active-brightgreen)
![Python](https://img.shields.io/badge/python-3.11+-blue?logo=python)
![FastAPI](https://img.shields.io/badge/FastAPI-0.110-009688?logo=fastapi)
![React](https://img.shields.io/badge/react-18-61dafb?logo=react)
![License](https://img.shields.io/badge/license-MIT-green)
![Gemini](https://img.shields.io/badge/powered%20by-Google%20Gemini-4285F4?logo=google)

---

## 🧠 What is this?

**Sci-Discover-Agents** is a multi-agent scientific discovery platform 
where five specialized AI agents work together as a collaborative 
research team. Give it a scientific topic — and watch it:

1. Survey existing literature
2. Propose novel hypotheses
3. Simulate experiments and predict outcomes
4. Critically review findings
5. Design the next steps for future research

All autonomously. All in one pipeline. All visualized in real time.

---

## 🤖 The Five Agents

| Agent | Role |
|-------|------|
| 📚 **Literature Agent** | Surveys existing knowledge, papers, and prior research on the topic |
| 💡 **Hypothesis Agent** | Proposes novel, testable, and scientifically grounded hypotheses |
| 🧪 **Simulation Agent** | Simulates experiments in silico and predicts possible outcomes |
| 🔬 **Reviewer Agent** | Critically reviews findings, identifies flaws, and assigns scores |
| 📋 **Experiment Planner** | Designs concrete next-step experiments and prioritizes future work |

**Pipeline Flow:**




---

## ✨ Features

- 🔄 **Autonomous Multi-Agent Pipeline** — set it and watch it run
- 🎯 **Real-time Agent Activity Feed** — see each agent think and respond live
- 📊 **Simulation Visualization** — interactive charts for predicted outcomes
- 🧾 **Structured Research Reports** — exportable session summaries
- 🔁 **Cyclic Feedback Loop** — reviewer can trigger new hypotheses
- 🌐 **Modern, Beautiful UI** — smooth animations, clean design
- ⚡ **FastAPI Backend** — auto-generated Swagger docs at `/docs`
- 🗄️ **SQLite Database** — zero-setup, file-based persistence
- 🤖 **Google Gemini API** — cloud LLM, works on any CPU-only laptop

---

## 🛠️ Tech Stack

### Backend
| Technology | Purpose |
|------------|---------|
| **Python 3.11+** | Core language |
| **FastAPI** | Web framework & REST API |
| **Uvicorn** | ASGI server |
| **SQLAlchemy** | ORM for database |
| **SQLite** | Lightweight database |
| **Pydantic** | Data validation & schemas |
| **Google Gemini API** | LLM powering the agents |

### Frontend
| Technology | Purpose |
|------------|---------|
| **React 18** | UI library |
| **Vite** | Build tool & dev server |
| **TailwindCSS** | Utility-first styling |
| **shadcn/ui** | Beautiful, accessible components |
| **Framer Motion** | Smooth animations |
| **Recharts** | Simulation result charts |
| **React Router** | Client-side routing |
| **Axios** | HTTP client |

---

## 📸 Screenshots

> Coming soon — demo GIFs and UI screenshots will be added here.

| Dashboard | Live Agent Feed |
|-----------|-----------------|
| _placeholder_ | _placeholder_ |

| Simulation Charts | Research Report |
|-------------------|-----------------|
| _placeholder_ | _placeholder_ |

---

## 📁 Project Structure



See [`docs/ARCHITECTURE.md`](docs/ARCHITECTURE.md) for detailed documentation.

---

## 🚀 Quick Start

### Prerequisites

- Python **3.11+**
- Node.js **18+**
- A **Google Gemini API key** → [Get it free here](https://aistudio.google.com/app/apikey)

---

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/vishakha2121/sci-discover-agents.git
cd sci-discover-agents


cd backend

# Create virtual environment
python -m venv venv

# Activate it
# Windows:
venv\Scripts\activate
# macOS/Linux:
# source venv/bin/activate

# Install dependencies
pip install -r requirements.txt