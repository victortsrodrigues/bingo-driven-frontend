# Bingo Driven - Frontend

## Link deploy:
https://bingo-driven-frontend-kappa.vercel.app/

## Link repositório:
https://github.com/victortsrodrigues/bingo-driven-frontend

## Execução com Docker:

### 1. Construa a imagem do container frontend:
Execute no terminal: docker build -t myfrontend .

### 5. Execute o container backend:
Execute no terminal:
  docker run -d \
  --name NOMECONTAINER \
  -p 80:80 \
  --network=NOMENETWORK \
  myfrontend

## Execução com Docker Compose:

### 1. Execute o comando docker-compose up -d para iniciar o container:
Execute no terminal: docker compose up -d