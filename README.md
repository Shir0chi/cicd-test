# CI/CD Test Project

Учебный проект для отработки CI/CD-пайплайна.

## Что делает
- Flask-приложение с эндпоинтом /health
- При каждом push в main автоматически:
  - Запускаются тесты (pytest)
  - Собирается Docker-образ
  - Образ публикуется в Docker Hub

## Стек
Python, Flask, pytest, Docker, GitHub Actions