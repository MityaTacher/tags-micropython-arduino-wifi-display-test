# Отчёт по отладке приложения ФИО
1. sqlalchemy.url = driver://user:pass@localhost/dbname alembic.ini
2. Шаг 1. Анализ и запуск.
   + **Что сделал?** Согласно Readme запустил `docker compose -up --build`, получил ошибку `pydantic_core._pydantic_core.ValidationError`
   + **Проблема** В Pydantic-setting передается что-то лишнее
   + **Файл и строка** `app/core/config:14`
   + **Как исправил** передал корректное название переменной окружения 