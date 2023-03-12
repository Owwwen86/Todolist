Todolist + веб-приложение — планировщик задач

(python3.9, Django==4.0.1, Postgres)

pip install requirements.txt - создание файла зависимостей

docker-compose up -d db

docker-compose ps -a

python manage.py makemigrations --dry-run (--dry-run - говорит о том, что будет создано)

python manage.py makemigrations

python manage.py migrate - накатить миграции

python manage.py createsuperuser - создание суперюзера

list_display = ('username', 'email', 'first_name', 'last_name') - переопределение столбцов в админке

https://pre-commit.com/

git add .

git status - смотрим файлы перед отправкой

git rm --cashed {файл/папка} - убираем из списка

git commit -m '{название коммита}'