# ScreenMatch v3 - API REST com Spring Boot e integração Frontend

Projeto desenvolvido em Java utilizando Spring Boot para construção de uma API REST responsável por fornecer dados de séries e episódios para uma aplicação web.

A aplicação também realiza consumo de uma API externa para obtenção de informações de filmes e séries, permitindo integração entre backend, banco de dados e frontend.

---

## 🚀 Tecnologias utilizadas

### Backend
- Java
- Spring Boot
- Spring Web
- Spring Data JPA
- Hibernate
- PostgreSQL
- Maven

### Frontend
- HTML
- CSS
- JavaScript
- Consumo de API REST

### Integrações
- OMDb API (API externa de filmes e séries)
- Configuração CORS para comunicação entre aplicações

---

## 📚 Conceitos aplicados

Durante o desenvolvimento deste projeto foram aplicados conceitos importantes do desenvolvimento backend:

- Criação de APIs REST com Spring Boot
- Arquitetura em camadas (Controller, Service e Repository)
- Integração entre backend e frontend
- Consumo de API externa
- Persistência de dados com Spring Data JPA
- Consultas utilizando JPQL
- Uso de DTOs para transferência de dados
- Configuração de CORS
- Organização de pacotes em aplicações Java

---

## ⚙️ Configuração do ambiente

Para executar o projeto é necessário possuir:

- Java 17 ou superior
- Maven
- PostgreSQL
- Navegador web

---

## 🔑 Configuração da chave da API

Este projeto utiliza a API externa **OMDb API**.

Crie uma variável de ambiente chamada:

OMDB_API_KEY

Na classe `Principal` substitua:

"SUACHAVEAPI"

Para obter uma chave de API acesse:

https://omdbapi.com/

---

## 🔑 Configuração do Application properties

Este projeto utiliza variáveis de ambiente para aumentar a segurança.

Crie variáveis de ambiente chamada:

${DB_HOST}
${DB_NAME}
${DB_USER}
${DB_PASSWORD}

No arquivo "application.properties" vão estar essas variáveis:

---

## ▶️ Como executar o projeto

1 Clone o repositório

git clone LINK_DO_REPOSITORIO

2 Acesse a pasta do backend

cd backend

3 Execute a aplicação Spring Boot

4 Abra o frontend no navegador para consumir os dados da API.
-> Melhor utilizar a extensão "live reload"

---

## 📌 Objetivo do projeto

Este projeto foi desenvolvido com o objetivo de consolidar conhecimentos em desenvolvimento backend utilizando Java e Spring Boot, explorando criação de APIs REST, integração e praticar com frontend e consumo de APIs externas.

---

## 👨‍💻 Autor

Projeto desenvolvido por **BrunoMhit* como parte dos estudos em desenvolvimento backend com Java.

