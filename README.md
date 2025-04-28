# Iron Forge
Основной репозиторий с документацией проекта и инструкцией по запуску

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
