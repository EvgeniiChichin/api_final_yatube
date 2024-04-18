### Описание проекта

Проект API для социальной сети Yatube.
Автор: Евгений Чичин

Для работы с API используeтся:  
Django Rest Framework  
Python 3.10  
Django 3.2.16  
SQlite3
  
В проекте используютя модели:  
Post -  посты  
Group - группы  
Comment - комментарии для постов  
Follow -  управление подписками  

Документация по проекту после запуска сервера доступна по адресу:  
http://127.0.0.1:8000/redoc/  


### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:EvgeniiChichin/api_final_yatube.git
```

```
cd kittygram
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```
