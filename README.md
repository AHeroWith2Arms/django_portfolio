# Портфолио Python проектов
## Проекты:
_____
### 1. Проект - TG Task / Habit Tracker
- **Бэкенд‑приложение на Django/DRF с интеграцией с Telegram‑ботом для трекинга привычек и задач.
#### Технологический стек
- **Python 3.11+**
- **Django 5**
- **Django REST Framework**
- **PostgreSQL**
- **Celery + Redis** (фоновые задачи и планировщик)
- **Telegram Bot API** (через `requests`)
- **JWT‑аутентификация** (`djangorestframework-simplejwt`)
- **drf-spectacular** для OpenAPI‑схемы
- **django-environ** для конфигурации
- **pytest / pytest-django / coverage / flake8 / black** для тестов и качества кода

#### Ссылки:
- [Репозиторий проекта на GitHub](https://github.com/AHeroWith2Arms/bot_tg_task_tracker)
- [Детальное описание особенностей и технологий](https://github.com/AHeroWith2Arms/bot_tg_task_tracker/blob/main/FEATURES.md)

### 2. Проект - LMS-платформа для курсов
- Проект представляет собой мини-LMS (платформу для онлайн-обучения) с курсами, уроками, подписками на обновления и интеграцией с платежами.
#### Технологический стек
- Python 3.13+
- Django 5
- Django REST Framework
- PostgreSQL
- Celery + Redis (фоновые задачи и планировщик Celery Beat)
- JWT‑аутентификация (djangorestframework-simplejwt)
- drf-spectacular для OpenAPI‑схемы и Swagger UI
- django-environ для конфигурации через .env
- Stripe (stripe Python SDK) для интеграции платежей
- Docker + Docker Compose для инфраструктуры
- pytest / pytest-django / coverage / flake8 / black для тестов и качества кода

#### Ссылки:
- [Репозиторий проекта на GitHub](https://github.com/AHeroWith2Arms/Django_Courses_site)
- [Детальное описание особенностей и технологий](https://github.com/AHeroWith2Arms/Django_Courses_site/blob/main/FEATURES.md)
