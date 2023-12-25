## Описание

Тестовое задание Долгих А.А. для Performance Group.

## Установка

1. Установить и запустить локально PostgreSQL.
Официальный сайт для скачивания: `https://www.postgresql.org/download/`

2. Выполнить миграцию.
- Запустите SQL Shell (psql) и авторизуйтесь под учетной записью, заданной при установке.
- Выполните команду: "\i 'путь_до\\akb\\Create_DB_DDL.sql'" (обратите внимание все \\ двойные или можно использовать обратные /), пример: "\i 'C:\\Users\\username\\Desktop\\akb\\Create_DB_DDL.sql'".

3. Настроить переменные окружения.
Файл: `./.env`.

4. Установить зависимости.
```bash
$ npm i
```

## Запуск приложения

```bash
$ npm start
```

## Ручная проверка

Осуществляется через Postman.
Коллекция запросов в ./Коллекция_запросов_Postman.json
