# Echofy 🎵

**Alunos:**

> Cauê Iwamoto Meira, R.A: 22.221.039-5

> Hanna de Oliveira Melo, R.A: 22.223.002-1
------------------------------------------------------

# Introdução

O Echofy é um sistema de recomendação musical desenvolvido com o objetivo de demonstrar a integração entre diferentes modelos de bancos de dados em uma única aplicação.

O sistema simula uma plataforma de streaming musical onde usuários podem:

- cadastrar músicas;
- criar playlists;
- comentar músicas;
- curtir músicas;
- receber recomendações inteligentes.


---

# Tecnologias Utilizadas

## Frontend
- React.js
- JavaScript
- React Router DOM

## Backend
- Node.js
- Express.js

## Bancos de Dados

### PostgreSQL
Responsável por armazenar:
- usuários;
- músicas;
- playlists;
- relacionamentos muitos-para-muitos (playlist_musicas).

### MongoDB
Responsável por armazenar:
- comentários das músicas.

### Neo4j
Responsável por:
- sistema de curtidas;
- relações entre usuários e músicas;
- recomendações inteligentes.

---

# Requisitos para Rodar o Projeto

Antes de executar o sistema, é necessário instalar localmente:

## Node.js
Download:
https://nodejs.org/

Versão recomendada:
- LTS

---

## PostgreSQL
Download:
https://www.postgresql.org/download/

Durante a instalação:
- definir usuário = postgres;
- definir senha = 123;
- manter porta padrão 5433.

---

## MongoDB Community Server
Download:
https://www.mongodb.com/try/download/community

Versão recomendada:
- 7.0.x

---

## Neo4j Desktop
Download:
https://neo4j.com/download/

---
