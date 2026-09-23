# Cerevum

# Cerevum

Cerevum — это веб-приложение для [краткое описание назначения, например: управления задачами и заметками с синхронизацией между устройствами].

## Особенности

- 🌐 Работает как сайт на ноутбуке и как PWA-приложение на Android
- 🔄 Автоматическая синхронизация данных между устройствами
- 🚀 Быстрый стек: FastAPI + React/Vue + PWA
- 📦 Офлайн-режим и установка на главный экран

## Стек технологий

- **Бэкенд**: FastAPI, SQLAlchemy, SQLite/PostgreSQL
- **Фронтенд**: React/Vue, Vite, PWA
- **Деплой**: Render/Railway (бэкенд), Vercel/Netlify (фронтенд)

## Быстрый старт

### Бэкенд

```bash
cd backend
python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate

pip install -r requirements.txt
uvicorn main:app --reload
```

### Фронтенд

```bash
cd frontend
npm install
npm run dev
```

## Структура проекта

cerevum/
├── backend/ # FastAPI сервер
│ ├── main.py
│ ├── models.py
│ ├── schemas.py
│ └── requirements.txt
├── frontend/ # React/Vue PWA
│ ├── src/
│ ├── public/
│ └── package.json
└── README.md

## Лицензия

MIT License — см. файл [LICENSE](LICENSE)

## Контакты

Автор: Kostya Ooo
Email: [твой email]
Telegram: [твой ник]
