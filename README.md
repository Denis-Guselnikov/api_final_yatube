Проект "API для Yatube"

API для сервиса блогов "Yatube".
"API для Yatube" позволяет создавать, редактировать, удалять и комментировать посты, предоставляет возможность получить информацию о группах.
"API для Yatube" позволяет подписоваться на других пользователей.
Для аутентификации использованы JWT-токены.
В проекте используется: Django REST Framework.

Установка проекта:
Клонировать репозиторий и перейти в него в командной строке:
git clone https://github.com/Denis-Guselnikov/api_final_yatube
cd api_final_yatube/
Cоздание виртуального окружения и его активация:
python -m venv venv
source venv/Scripts/activate
Установка зависимостей из requirements.txt:
pip install -r requirements.txt
Выполнение миграций:
python manage.py migrate
Запуск проекта:
cd yatube_api/
python3 manage.py runserver

Примеры:
