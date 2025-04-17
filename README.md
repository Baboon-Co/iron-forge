# Iron Forge
Основной репозиторий с документацией проекта и инструкцией по запуску

# Запуск
## Docker Compose:
```yaml
services:
    api-gateway:
        container-name: api-gateway
        image: ghcr.io/baboon-co/iron-forge-api-gateway:latest
        ports:
            - "5000:5000"
            - "5001:5001"
        
    auth-service:
        container-name: auth-service
        image: ghcr.io/baboon-co/iron-forge-auth:latest
```
