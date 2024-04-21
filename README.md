# docker-NginxNode
Desafio Full Cycle Docker - Nginx com Node.js

# Como executar o projeto
Primeiro você deve criar uma network para que os containers possam se comunicar entre si:
docker network create app-node-network

Agora basta executar o comando docker-compose para subir os containers:
docker-compose up -d

Agora basta acessar a aplicação em seu browser:
http://localhost:8080
