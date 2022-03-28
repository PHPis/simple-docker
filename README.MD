## Докер состоит из:
- PHP - 8 (+ composer)
- NGINX - 1.16.0-alpine
- Postgres
- Adminer

## Команда запуска
```bash
docker-compose up -d
```

## Прочие команды 

Просмотр логов:
```bash
docker logs Имя_контейнера
```
Зайти из-под контейнера:
```bash
docker-compose exec engine bash
```

## Make-файл

Make-файл - это краткий вызов одной или нескольких команд, прописанных в Makefile. 