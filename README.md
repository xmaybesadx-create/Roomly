#  HealthyFood — Планування харчування та підбір рецептів

## Опис
Веб-додаток, що допомагає користувачам планувати своє харчування, рахувати калорії, зберігати щоденник харчування та підбирати рецепти за наявними інгредієнтами.  
Проєкт реалізований як React + FastAPI додаток з PostgreSQL базою даних.

## Інсталяція та запуск

### 1. Клонування репозиторію
bash
git clone <посилання>
1.  Запуск фронтенду
cd frontend
npm install
npm run dev
2.  Запуск бекенду
cd backend
pip install -r requirements.txt
uvicorn main:app –reload
3.  Налаштування БД
•  Створіть .env файл у backend/
•  Вкажіть змінні оточення:
DATABASE_URL=postgresql://user:password@localhost:5432/dbname
JWT_SECRET=ваш_секрет
alembic upgrade head

#Технології
•  Frontend: React, Vite, TailwindCSS, Axios
•  Backend: Python, FastAPI, Postman
•  Database: PostgreSQL
•  CI/CD: GitHub Actions, Vercel (Frontend), Railway (Backend)
#Структура репозиторію
•  /frontend — код React застосунку
•  /backend — бекенд на FastAPI
•  /docs — документація, макети
•  /tests — автотести (frontend + backend)
#Автори
•  Людина 1 — UI/UX та React компоненти
•  Людина 2 — Інтеграція фронтенду з API
•  Людина 3 — Авторизація, JWT
•  Людина 4 — База даних, рецепти
•  Людина 5 — Food Log, підрахунок калорій
•  Людина 6 — Аналітика, статистика
•  Людина 7 — DevOps, тестування, деплой
