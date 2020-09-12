# УСТАНОВКА
install requirements then, install postgresql



# Пример проекта

heroku create 
git push heroku master
heroku run python manage.py migrate
heroku run python manage.py createsuperuser

# Чтобы добавить memcached в проект, подключите его как addon:

heroku addons:create memcachier:dev
