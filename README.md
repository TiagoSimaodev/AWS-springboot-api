# 🚀 AWS Spring Boot API

## 📖 Sobre o projeto

Esta é uma API REST desenvolvida com **Java + Spring Boot**, com o objetivo de gerenciar produtos através de operações CRUD (Create, Read, Delete).

A aplicação foi projetada seguindo boas práticas de desenvolvimento backend e está hospedada na AWS, utilizando serviços como Elastic Beanstalk e RDS.

---

## ☁️ Arquitetura da aplicação

A aplicação segue uma arquitetura baseada em cloud:

* Front-end: hospedado no AWS S3
* API Gateway: responsável por receber as requisições
* Back-end: Spring Boot rodando no Elastic Beanstalk
* Banco de dados: MySQL no AWS RDS

![Arquitetura](./docs/arquitetura.png)

---

## ⚙️ Tecnologias utilizadas

### Back-end

* Java 17
* Spring Boot
* Spring Data JPA
* Hibernate
* Maven

### Banco de dados

* MySQL (AWS RDS)

### Cloud / Infraestrutura

* AWS S3
* AWS API Gateway
* AWS Elastic Beanstalk
* AWS RDS

---

## 🔥 Funcionalidades

* ✅ Cadastro de produtos
* ✅ Listagem de produtos
* ✅ Exclusão de produtos
* ✅ Integração com banco de dados

---

## 📡 Endpoints principais

### 📦 Produtos

```http
GET /produtos
POST /produtos
PUT /produtos/{id}
DELETE /produtos/{id}
```

---

## ▶️ Como executar o projeto

### Pré-requisitos

* Java 17
* Maven
* MySQL

---

### Passos

```bash
# Clonar o repositório
git clone https://github.com/TiagoSimaodev/AWS-springboot-api.git

# Entrar na pasta
cd AWS-springboot-api

# Rodar o projeto
mvn spring-boot:run
```

---

## 🔐 Variáveis de ambiente

Para rodar o projeto, configure as seguintes variáveis:

```env
DB_URL=
DB_USERNAME=
DB_PASSWORD=
```

---

## 🌐 Deploy

A aplicação está preparada para deploy na AWS utilizando:

* Elastic Beanstalk para o backend
* RDS para o banco de dados
* S3 para o frontend

---

## 📌 Melhorias futuras

* 🔐 Implementar autenticação com JWT
* 📦 Dockerizar aplicação
* 🚀 CI/CD com GitHub Actions
* 📊 Monitoramento com CloudWatch

---

## 👨‍💻 Autor

**Tiago Simão**

🔗 LinkedIn: https://www.linkedin.com/in/tiagosimaodev/
🔗 GitHub: https://github.com/TiagoSimaodev

---

## ⭐ Considerações

Este projeto foi desenvolvido com foco em aprendizado e prática de desenvolvimento backend com Spring Boot e integração com serviços da AWS, demonstrando uma arquitetura moderna e escalável.

---
