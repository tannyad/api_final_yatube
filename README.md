# Проект «API для Yatube»
### Описание
Продемонстрирована реализация API для проекта социальной сети Yatube.
### Описание
Python 3.7
Django 2.2.19
### Установка
- Установите зависимости из файла requirements.txt
```
pip install -r requirements.txt
``` 
- Создать и активировать виртуальное окружение:
```
python -m venv env
source env/bin/activate
```
- Установить все необходимые пакеты:
```
pip install -r requirements.txt
```
- Выполнить миграции:
```
python manage.py migrate
```
- Запустить проект:
```
python manage.py runserver
```
### Примеры
- GET .../api/v1/posts/:
```
{
  "count": 123,
  "next": "http://api.example.org/accounts/?offset=400&limit=100",
  "previous": "http://api.example.org/accounts/?offset=200&limit=100",
  "results": [
    {
      "id": 0,
      "author": "string",
      "text": "string",
      "pub_date": "2021-10-14T20:41:29.648Z",
      "image": "string",
      "group": 0
    }
  ]
}
```
