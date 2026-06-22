<div align="center">

# Андрей Ильин

### ML / AI Engineer · AI-продукты · Production-системы

Создаю ML/AI-продукты под ключ — от постановки задачи и работы с данными<br/>до интерфейса, мониторинга и запуска в production.

[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/andrej_ilin)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/андрей-ильин)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white)](https://www.kaggle.com/andrejilin)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:a.vikt.ilin@gmail.com)

</div>

## Обо мне

Проектирую и разрабатываю AI-системы целиком: готовлю данные, настраиваю поиск и модели, создаю backend и пользовательские интерфейсы, автоматизирую тестирование и развёртывание. Сильная сторона — превращать прототипы в надёжные продукты, которыми можно пользоваться в реальной работе.

- Магистрант МФТИ по программе «Современные методы искусственного интеллекта» (2024–2026).
- Нахожусь в Москве, открыт к позициям и проектам в ML/AI Engineering и Data Science.

## Боевые кейсы

### HH Auto Bot — AI-сервис автоматизации поиска работы

- **Задача:** сократить ручную работу при поиске вакансий и отправке откликов.
- **Что сделал:** разработал и запустил многопользовательский Telegram-сервис, который подбирает подходящие вакансии, оценивает их с помощью AI, готовит сопроводительные письма и автоматизирует отправку откликов через браузер.
- **Как обеспечил надёжность:** изолировал сессии разных пользователей, добавил очередь задач с восстановлением после перезапуска, повтор временно неудачных операций и автоматическое переключение между AI-сервисами. Для потенциально опасных ситуаций — капча, вопросы работодателя или незаполненное письмо — система останавливает автоматический сценарий.
- **Результат:** довёл сервис до работающего продукта с авторизацией, тарифами и платежами, личным кабинетом, мониторингом, уведомлениями и production-развёртыванием.

### Production ML/AI-система

- **Задача:** построить быстрый и устойчивый поиск по большим объёмам данных без лишних затрат на AI.
- **Что сделал:** создал двухэтапную обработку с повторным использованием уже загруженных данных и контролем затрат. Система сначала быстро ищет подходящие результаты по смыслу и ключевым словам, а затем использует языковую модель (LLM) только для перепроверки наиболее релевантных вариантов.
- **Как обеспечил качество и безопасность:** добавил автоматическую оценку качества поиска, разделил персональные данные и рабочие данные, настроил журналирование доступа, правила хранения и полное удаление данных.
- **Подготовка к production:** разработал API, фоновые задачи и web-интерфейс, покрыл ключевые сценарии автоматическими тестами, подготовил контейнеры, автоматическую сборку и проверку изменений (CI/CD), развёртывание в Kubernetes.

## Ключевой стек

| Направление | Технологии и практики |
|---|---|
| **ML / Deep Learning** | PyTorch, TensorFlow/Keras, scikit-learn, pandas, NumPy, computer vision, NLP, audio processing |
| **Search / GenAI** | embeddings, Qdrant, dense/sparse hybrid retrieval, LLM-reranking, RAG, AI agents, MCP, offline evaluation |
| **Backend / Data** | Python, FastAPI, Pydantic, OpenAPI, PostgreSQL, SQLAlchemy, Redis, Celery, async processing |
| **Интерфейсы / Automation** | React, TypeScript, Vite, Streamlit, aiogram, Playwright |
| **Platform / Quality** | Docker/Compose, Helm, Kubernetes, GitHub Actions, GitLab CI/CD, Prometheus/Grafana, pytest, Ruff, privacy-by-design |

## Открытый код

| Проект | Что показывает | Стек |
|---|---|---|
| [VS Code Feature Scout](https://github.com/Andrej-Ilin/vscode-feature-scout) | CLI-инструмент, который помогает разработчику и AI-ассистенту находить полезные возможности VS Code для конкретного проекта. Включает тесты, проверку качества кода и CI. | Python, pytest, Ruff, GitHub Actions, uv |
| [Emotion Recognition](https://github.com/Andrej-Ilin/emotion_recognition_project) | ML-прототип распознавания эмоций по речи: обработка аудио, обучение модели, web-интерфейс и запуск в Docker. | TensorFlow/Keras, librosa, scikit-learn, Streamlit, Docker |

## Образование

- **Московский физико-технический институт (МФТИ)** — магистратура «Современные методы искусственного интеллекта», 2024–2026.

## Языки

- Русский — родной.
- Английский — Intermediate, свободно читаю техническую документацию.
