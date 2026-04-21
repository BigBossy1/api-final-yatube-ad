# API для Yatube

## Описание
REST API для социальной платформы Yatube. Позволяет работать с публикациями, комментариями, группами и подписками пользователей.

## Стек
- Python 3.10+
- Django 3.2
- Django REST Framework
- JWT (SimpleJWT)

## Установка

```bash
git clone https://github.com/prosto10ia/api-final-yatube-ad.git
cd api-final-yatube-ad
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
cd yatube_api
python manage.py migrate
python manage.py runserver