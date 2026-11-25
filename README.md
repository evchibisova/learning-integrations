# Learning Integrations

Минимальное приложение на FastAPI без базы данных.

Все команды выполняются из директории проекта.

Команды одинаковые для Windows, macOS и Linux. Docker должен быть установлен и запущен. На Windows используйте Docker Desktop в режиме Linux-контейнеров; команды можно выполнять в PowerShell.

## Запуск через Docker

Собрать образ:

```bash
docker build -t learning-integrations .
```

Запустить контейнер:

```bash
docker run --rm -p 8000:8000 learning-integrations
```

## Проверка

- Приложение: http://localhost:8000
- Swagger: http://localhost:8000/docs

Маршрут `GET /` возвращает `{"message": "Hello, world!"}`.

Для остановки приложения нажмите `Ctrl+C` в терминале, где оно запущено.
