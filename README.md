# 🤖 WALL-E: Adaptive Learning & Educational AI Platform

**WALL-E** is an academic web-based adaptive learning platform designed to personalize educational content and provide interactive AI tutoring support for students and teachers.

[![Category](https://img.shields.io/badge/CATEGORY-ACADEMIC%20PROJECT-e0004d?style=for-the-badge)](#) [![UNIVAG](https://img.shields.io/badge/UNIVAG-PROJETO%20INTEGRADOR%20EXTENSIONISTA-00c8ff?style=for-the-badge)](#) [![License](https://img.shields.io/badge/LICENSE-MIT-76b900?style=for-the-badge)](#)

---

## 📌 Project Overview

Developed during the **'Programação Radical 2024'** event at **UNIVAG**, **WALL-E** serves as a prototype for tailored educational experiences. The application provides dedicated portals for both students and educators, featuring an AI chat interface to answer technical questions and streamline study workflows.

---

## ⚡ Tech Stack

- **Backend:** Python, Flask
- **Frontend:** JavaScript (ES6+), HTML5, CSS3
- **Architecture:** RESTful Simulation APIs / Server-Side Template Rendering

---

## 🚀 Key Features

* **Multi-Portal Architecture:** Separate workflows and dashboards for students and teachers.
* **Interactive Chat Simulation:** Simulated intelligent assistant providing contextual learning answers.
* **Responsive Learning Interface:** Clean dashboards optimized for study tracking and material access.

---

## 📦 Deliverables

| What | Where to see it |
|---|---|
| Student and educator portals with AI chat | `python backend/app.py`, then open the local Flask address |

---

## 🛠️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Paulorgdc/wall-e.git
   cd wall-e
   ```

2. Create a local Python environment and install the dependencies:
   ```powershell
   python -m venv venv
   ./venv/Scripts/python.exe -m pip install -r requirements.txt
   ```
3. Consult `.env.example` for variable names. Provide the variables through
   the environment used to launch Flask; copying a file alone does not prove
   that a loader reads it.
4. Start locally with `./venv/Scripts/python.exe backend/app.py`.
   The documented Gunicorn entry point (`backend.app:app`) is for compatible
   deployment environments; it is not the Windows development command.

Academic context: the existing description and project note identify
Programação Radical 2024; the badge currently identifies Projeto Integrador.
Confirm the original institutional record before changing that classification.
