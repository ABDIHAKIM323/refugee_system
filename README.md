# REFUGEE SYSTEM

This is a refugee management system built using django

  - Python3
  - Django 2.0+
  - Sqlite

# Installation
To run the development version :

  - clone this repo
  - navigate into the root folder
  - run the following in terminal
  ** Note if you are on windows use python without the 3 suffix
   ```sh
$ pip install -r requirements.txt
$ python3 manage.py makemigrations
$ python3 manage.py migrate
$ python3 manage.py createsuperuser


$ python manage.py shell

```
In the shell prompt : 
``` python3
from database_set_up import main as db_main
db_main()
exit()
```

-Finally run
```sh
$   python3 manage.py runserver
```
Visit the site on your browser at [localhost:8000/](http://localhost:8000/)
