# Echofy 🎵

**Alunos:**

> Cauê Iwamoto Meira, R.A: 22.221.039-5

> Hanna de Oliveira Melo, R.A: 22.223.002-1
------------------------------------------------------
## Introdução
O Echofy é um sistema de recomendação musical desenvolvido com o objetivo de demonstrar a integração entre diferentes modelos de bancos de dados em uma única aplicação.

O sistema simula uma plataforma de streaming musical onde usuários podem:

- cadastrar músicas;
- criar playlists;
- comentar músicas;
- curtir músicas;
- receber recomendações inteligentes.

Para este projeto utilizamos múltiplos bancos de dados, onde cada tecnologia foi escolhida de acordo com o tipo de dado e comportamento esperado no sistema.

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
Utilizado para armazenar:
- usuários;
- músicas;
- playlists;
- relacionamentos muitos-para-muitos entre os usuários.

### MongoDB
Utilizado para armazenar:
- comentários das músicas.

### Neo4j
Utilizado para:
- sistema de curtidas;
- relações entre usuários e músicas;
- recomendações inteligentes.

