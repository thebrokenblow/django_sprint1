# Blogicum — Социальная сеть для публикации постов

## Описание проекта
Blogicum — это социальная сеть, где пользователи могут публиковать посты, делиться мыслями и опытом. Каждый пользователь может создать свою страницу, публиковать записи с указанием категории и локации, читать и комментировать других пользователей.

## Функциональность
- Публикация постов
- Указание категорий и локаций
- Просмотр постов по категориям
- Чтение и комментирование чужих постов

## Технологии
- Python 3.11+
- Django 3.2.16
- Bootstrap 5

## Установка и запуск

### 1. Клонирование репозитория и настройка окружения
```bash
git clone https://github.com/thebrokenblow/django_sprint1.git
cd django_sprint1

# Создание виртуального окружения
python -m venv venv

# Активация виртуального окружения
# Для Windows:
.\venv\Scripts\Activate.ps1
# Для Linux/Mac:
source venv/bin/activate

# Установка зависимостей
pip install -r requirements.txt
```

### 2. Настройка проекта
```bash
cd blogicum
python manage.py migrate
```

### 3. Запуск сервера
```bash
python manage.py runserver
```
После запуска сервера проект будет доступен по адресу: [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

## Запуск тестов
```bash
pytest                         # Запуск всех тестов
pytest tests/test_urls.py      # Тесты URL
pytest tests/test_templates.py # Тесты шаблонов
pytest tests/test_settings.py  # Тесты настроек
```
