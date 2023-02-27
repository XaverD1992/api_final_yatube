### API для Yatube
#Описание
REST API для социальной сети Yatube. Предоставляет аутентифицированным пользователям возможность создавать, редактировать и удалять записи в социальной сети Yatube. Также через него можно просматривать и комментировать записи других пользователей и подписываться на других авторов. 
#Установка
Клонировать репозиторий и перейти в него в командной строке:
git clone git@github.com:KseniyaGurevich/api_final_yatube.git
cd api_final_yatube
Cоздать и активировать виртуальное окружение:
python3 -m venv env
source env/bin/activate
python3 -m pip install --upgrade pip
Установить зависимости из файла requirements.txt:
pip install -r requirements.txt
Выполнить миграции:
python3 manage.py migrate
Запустить проект:
python3 manage.py runserver
