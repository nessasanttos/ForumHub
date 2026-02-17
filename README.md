# ForumHub API

Projeto desenvolvido como requisito obrigatório da especialização, implementando uma API REST para gerenciamento de tópicos de fórum utilizando **Spring Boot**.

---

## 🚀 Tecnologias utilizadas

* Java
* Spring Boot
* Spring Web
* Spring Data JPA
* Spring Security
* PostgreSQL
* Lombok
* Validation
* Maven

---

## 📌 Funcionalidades

* Cadastro de tópicos
* Listagem de todos os tópicos
* Detalhamento de tópico por ID
* Atualização de tópico
* Exclusão de tópico
* Autenticação com Spring Security
* Persistência em banco de dados relacional

---

## ▶️ Como executar o projeto

1. Clonar o repositório:

   ```bash
   git clone https://github.com/nessasanttos/ForumHub.git
   ```

2. Entrar na pasta do projeto:

   ```bash
   cd ForumHub
   ```

3. Configurar o banco PostgreSQL no arquivo:

   ```
   src/main/resources/application.properties
   ```

4. Executar a aplicação:

   ```bash
   mvn spring-boot:run
   ```

---

## 🔐 Acesso

Após iniciar a aplicação:

```
http://localhost:8080/topicos
```

Será necessário autenticação configurada pelo Spring Security.

---

## 📚 Objetivo

Este projeto tem fins **educacionais**, atendendo aos requisitos obrigatórios da especialização para prática de:

* API REST
* Persistência com JPA
* Segurança com Spring Security
* Versionamento com Git/GitHub

---

## ✍️ Autora

**Ângela Vanessa**
