# Курсовая 5. Работа с базами данных


## Основные шаги проекта
Получение данных о работодателях и их вакансиях с сайта hh.ru. Для этого используется публичный API hh.ru и библиотека requests

Выбраны не менее 10 интересных компаний, от которых получены данные о вакансиях по API.

Спроектированы таблицы в БД PostgreSQL для хранения полученных данных о работодателях и их вакансиях. Для работы с БД используется библиотека psycopg2.

Реализован код, который заполняет созданные в БД PostgreSQL таблицы данными о работодателях и их вакансиях.

Создан класс DBManager для работы с данными в БД. 

Класс DBManager использует библиотеку psycopg2 для работы с БД.