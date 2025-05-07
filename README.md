# Iron Forge
Основной репозиторий с документацией проекта и инструкцией по запуску

# Ссылки
## Содержание
[Запуск](#запуск)

[После запуска](#после-запуска)

## Связанные репозитории
[Frontend](https://github.com/Baboon-Co/iron-forge-frontend)

[Контракты](https://github.com/Baboon-Co/iron-forge-contracts)

[API-Gateway](https://github.com/Baboon-Co/iron-forge-api-gateway)

[Auth-сервис](https://github.com/Baboon-Co/iron-forge-auth-service)

[Profile-сервис](https://github.com/Baboon-Co/iron-forge-profile-service)

[Matchmaking-сервис](https://github.com/Baboon-Co/iron-forge-matchmaking-service)

[Game-сервис](https://github.com/Baboon-Co/iron-forge-game-service)

# Запуск
## Docker Compose:
1. Скачать репозиторий или [docker-compose.yml](./docker-compose.yml)
2. Из папки запустить команду:
```bash
docker compose pull && docker compose up -d
```
Либо эту, если хочется смотреть на логи контейнеров прямо в консоли:
```bash
docker compose pull && docker compose up
```

# После запуска
## API-Gateway
### Основной адрес
http://localhost:5000/api

### Документация OpenAPI
http://localhost:5000/api-docs
