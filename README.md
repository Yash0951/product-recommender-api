# 🤖 E-commerce Recommender with LLM Explanations

A **full-stack intelligent recommendation system** that delivers **personalized product suggestions** — and uniquely, uses a **Large Language Model (LLM)** (via [OpenRouter](https://openrouter.ai)) to generate **human-like explanations** for each recommendation.  

> Imagine a shopping platform that not only *recommends* products but also *tells you why* it thinks you’ll love them. 💬✨

---

## 🌟 Features

- 🧠 **Content-Based Filtering** – Builds a *taste profile* for every user based on product descriptions they interact with.  
- 🗣️ **Dynamic AI Explanations** – Integrates an LLM to generate *context-aware, natural language reasons* behind each recommendation.  
- ⚡ **FastAPI Backend** – High-performance, asynchronous Python backend for handling logic and data processing.  
- 🧱 **SQLAlchemy ORM** – Simplifies database management with a clean, Pythonic interface to SQLite.  
- 💻 **Interactive Frontend** – Minimal yet responsive web interface built with HTML, Tailwind CSS, and JavaScript.  

---

## 🛠️ Tech Stack

| Category | Technologies |
|-----------|---------------|
| **Backend** | Python, FastAPI, SQLAlchemy, Uvicorn |
| **Data / ML** | Pandas, Scikit-learn |
| **LLM Integration** | OpenAI Python SDK (configured for OpenRouter) |
| **Frontend** | HTML, Tailwind CSS, JavaScript |
| **Database** | SQLite |

---

## 🚀 Quickstart: Setup & Run

Follow these simple steps to get started 👇  

### **Step 1: Clone the Repository**
```
git clone https://github.com/Yash0951/product-recommender-api.git
cd product-recommender-api
```
### **Step 2: Configure API Key - ⚠️ The app won’t run without a valid API key from OpenRouter(https://openrouter.ai/)**
```
# On Windows CMD
copy .env.example .env

# On Git Bash / Mac / Linux
cp .env.example .env
```
Then open the .env file and replace the placeholder key with your actual OpenRouter API key.

