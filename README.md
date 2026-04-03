# 🤖 Agent Web UI (By  Yaswanth Ganesh Kumar Vutukuri)

## 🚀 Overview

This project is an AI-powered **Browser Agent Web UI** that enables seamless interaction with websites using intelligent automation.

It provides a user-friendly interface to control browser-based AI agents and perform tasks efficiently.

---

## ✨ Features

* 🌐 **AI Browser Automation**
  Automate website interactions using intelligent agents.

* 🧠 **LLM Integration**
  Supports multiple Large Language Models (LLMs) like:

  * OpenAI
  * Google
  * Anthropic
  * DeepSeek
  * Ollama

* 🖥️ **User-Friendly Web Interface**
  Built using Gradio for smooth and interactive experience.

* 🔐 **Custom Browser Support**
  Use your own browser session without repeated logins.

* 🔄 **Persistent Sessions**
  Maintain browser state across multiple AI tasks.

---

## 🛠️ Tech Stack

* Python
* Gradio
* Playwright
* LLM APIs

---

## ⚙️ Installation Guide

### 🔹 Option 1: Local Setup

#### Step 1: Clone Repository

```bash
git clone https://github.com/Ganesh-Yash/web-ui-An-Agent-Browser-.git
cd web-ui-An-Agent-Browser-
```

#### Step 2: Create Virtual Environment

```bash
python -m venv .venv
.venv\Scripts\activate
```

#### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
playwright install
```

#### Step 4: Configure Environment

```bash
copy .env.example .env
```

Add your API keys inside `.env`

#### Step 5: Run Project

```bash
python webui.py --ip 127.0.0.1 --port 7788
```

👉 Open: http://127.0.0.1:7788

---

### 🐳 Option 2: Docker Setup

#### Step 1: Run Docker

```bash
docker compose up --build
```

#### Step 2: Access

* Web UI → http://localhost:7788
* VNC Viewer → http://localhost:6080

---

## 📌 Usage

* Launch the UI
* Select your LLM
* Start browser automation tasks
* Monitor actions in real-time

---

## 🙏 Credits

This project is inspired by and built upon the original work of the **browser-use** project.

Special thanks to the original contributors for their foundational work.

---

## 📄 License

This project is for educational and development purposes.
