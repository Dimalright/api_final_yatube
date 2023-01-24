Проект «API для Yatube»
Описание
Реализация REST API для учебного проекта Yatube.

Доступен следующий функционал:

Просмотр, создание, редактирование и удаление постов;
Просмотр и создание групп;
Подписки;
Возможность комментирования постов, редактирования и удаления комментариев.
Технологии:
Python, Django, DRF, JWT + Joser

Как запустить проект:
Клонируйте репозиторий:
git@github.com:Dimalright/api_final_yatube.git
Установите и активируйте виртуальное окружение:

Win:
python -m venv venv
source venv/Scripts/activate
Установите зависимости из файла requirements.txt:
pip install -r requirements.txt
Перейдите в директорию с файлом manage.py, создайте и примените миграции:
cd yatube
python manage.py makemigrations
python manage.py migrate
Создайте суперпользователя:
python manage.py createsuperuser
Запустите сервер:
python manage.py runserver

Примеры обращений к эндпоинтам:
POST http://127.0.0.1:8000/api/v1/posts/
GET http://127.0.0.1:8000/api/v1/follow/

Разработчик:
Dimalright
