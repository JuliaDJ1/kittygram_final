# Kittygram

Финальный проект спринта «Контейнеры и CI/CD» курса Яндекс.Практикум.

## О проекте

**Kittygram** — социальная сеть для любителей котиков.  
Пользователи могут публиковать фото своих питомцев, ставить лайки и комментировать.

## Технологии

- **Backend**: Django + Django REST Framework + Djoser
- **Frontend**: React
- **База данных**: PostgreSQL
- **Контейнеризация**: Docker + Docker Compose
- **Web-сервер**: Nginx (gateway)
- **CI/CD**: GitHub Actions
- **Деплой**: Ubuntu-сервер + автоматическое обновление по пушу в `main`

## Запуск проекта локально

```bash
docker compose up --build

## Автор проекта

Вадим Гусейнов evingb dockerhub
