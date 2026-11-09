# MEMORY — WALL-E
Plataforma de aprendizado adaptativo com chat de IA para alunos e professores (Programação Radical 2024, UNIVAG).

## Stack
- Backend: Python · Flask ≥3.0 · gunicorn (`backend/app.py`)
- Frontend: templates HTML + `assets/` servidos pelo Flask (venv local `venv/`)

## Comandos
- `python -m venv venv` · `venv\Scripts\activate` · `pip install -r requirements.txt`
- `python backend/app.py` (dev) · `gunicorn backend.app:app` (produção)

## Variáveis de ambiente
- FLASK_ENV, SECRET_KEY, PORT

## Regras de ouro
1. Portais separados para aluno e professor; cada um com seus templates em `frontend/templates`.
2. `SECRET_KEY` vem do ambiente, nunca hardcoded.
3. `.env` fora do Git; manter `.env.example` com os nomes.
