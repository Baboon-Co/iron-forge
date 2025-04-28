# Iron Forge
Основной репозиторий с документацией проекта и инструкцией по запуску

# Ссылки
## Содержание
[Запуск](https://github.com/Baboon-Co/iron-forge/tree/main?tab=readme-ov-file#запуск)

[После запуска](https://github.com/Baboon-Co/iron-forge?tab=readme-ov-file#после-запуска)

## Связанные репозитории
[Frontend](https://github.com/Baboon-Co/iron-forge-frontend)

[Контракты](https://github.com/Baboon-Co/iron-forge-contracts)

[API-Gateway](https://github.com/Baboon-Co/iron-forge-api-gateway)

[Auth-сервис](https://github.com/Baboon-Co/iron-forge-auth-service)

# Запуск
## Docker Compose:
```yaml
services:
    api-gateway:
        container_name: api-gateway
        image: ghcr.io/baboon-co/iron-forge/api-gateway:latest
        environment:
            ASPNETCORE_ENVIRONMENT: Development
            ASPNETCORE_HTTP_PORTS: 5000
        ports:
            - "5000:5000"
```

# После запуска
## API-Gateway
### Основной адрес
http://localhost:5000/api

### Документация OpenAPI
http://localhost:5000/api-docs
