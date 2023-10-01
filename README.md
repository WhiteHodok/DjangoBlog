# DjangoBlog

# Демонстрация работы 

![pycharm64_u6EcTp4p31](https://github.com/WhiteHodok/DjangoBlog/assets/39564937/00e665ec-0232-432e-8a55-e1b6967439ea)

## tree 

![image](https://github.com/WhiteHodok/DjangoBlog/assets/39564937/8fc20c20-ecf7-4cba-ba59-ce3ee6220a77)

## Dependencies

- Важно ! Откатить свою версию Django, либо же удалить до той, которая в requirements.txt (crispy forms конфликтует из-за этого) и установить зависимости через тот же requirements

- Django==3.12 , crispy-forms-django , bootstrap4


# Как устроен проект и как его редактировать 


## Обзор 


- Скриншот Home : 


![image](https://github.com/WhiteHodok/DjangoBlog/assets/39564937/12d64466-540d-4845-a331-727a83c7d506)


- Многопользовательский блог на Django + bootstrap4 , обладающий всем CRUD функционалом 

- Список всех аппок 

![image](https://github.com/WhiteHodok/DjangoBlog/assets/39564937/2be62b5c-da04-4517-bd95-af1bf2b0c40e)


## Edit 

- Проект имеет стандартную маршрутизацию в файлах, как и в любых Django проектах
  
- Основные шаблоны HTML находятся в *blog/templates/blog*

- Основная таблица (и единственная) таблица стилей (CSS) находится по следующему адресу *blog/static/blog*

![image](https://github.com/WhiteHodok/DjangoBlog/assets/39564937/200139dd-2c96-432d-a87d-65b6c9581dd5)

- Используется стандартная Jinja в виде шаблонизатора 

- БД является стандартная джанговская sqlite3 

- Проведены все migrations для Django 

- Обработка шаблонов производится через стандартные для каждого пользователя в Django *views.py*

- В свою очередь *urls.py* содержит ссылки на эти шаблоны 


# Installation and run 

- git clone this repo 

- .env файл в корневую директорию для хеш-ключа такого вида (его можно взять у меня)


``` SECRET_KEY="" ```


- В консоли прописать последовательно : 


1. ``` pip install requirements.txt```

2. ```python manage.py runserver```


# Осталось переделать 

- Перенести все данные из sqlite3 в supabase(PostgreSQL) 

- Перенести все img в supabase Storage 
 
  
