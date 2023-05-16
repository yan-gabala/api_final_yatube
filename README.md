Краткое описание API соцсети YaTube.

Предоставляются возможности:
 - регистрации и ведения своего блога;
 - можно вступать в группы;
 - оформить подписку;
 - комментировать посты;
 - чтения ленты сайта и своей ленты подписок.
 - запроса к моделям проекта: Посты, Группы, Комментарии, Подписки.

Данные выдаются в формате JSON.

Технологии:
- Python
- Django REST Framework
- Django
- Djangorestframework-simplejwt
- Pillow


Как запустить проект:

git clone git@github.com:yan-gabala/api_final_yatube.git

cd api_yatube

python3 -m venv env

. venv/bin/activate

pip install -r requirements.txt

python manage.py migrate

python3 manage.py runserver
