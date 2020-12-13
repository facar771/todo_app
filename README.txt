Todo Application

make virtualenv
on linux
$ python3.9 -m django_project todoenv
$ . venvbinactivate

make virtualenv
on windows
$ python3.9 -m django_project todoenv
$ . todoenvScriptsactivate.bat

(todoenv)$ pip install -r requirements.txt

migrate
(todoenv)$ cd django_project
(todoenv)$ python manage.py migrate

make admin user
(todoenv)$ cd django_project
(todoenv)$ python manage.py runserver