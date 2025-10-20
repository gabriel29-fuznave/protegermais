# Proteger+ com Docker

## Rodar localmente

1. Instale o Docker e Docker Compose
2. Dentro da pasta do projeto, execute:
```
docker compose up --build
```

- Frontend: http://localhost:5173
- Backend: http://localhost:4000

O banco de dados SQLite é criado dentro do container do backend em `/app/protegerplus.db`.