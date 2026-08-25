# 👋 Olá, eu sou André Ferreira

### Backend Developer | Java · Spring Boot · Python | APIs · Integrações · Event-Driven Systems

Desenvolvedor backend com experiência profissional em **APIs, integrações entre sistemas, regras de negócio, troubleshooting e bancos relacionais**.

Atuo com **Python, PostgreSQL, REST APIs, OAuth2 e webhooks** e venho aprofundando engenharia backend através de projetos com **Java/Spring Boot, Apache Kafka, Redis, Docker, Kubernetes, AWS e sistemas distribuídos**.

Meu foco está em **backend, integrações, mensageria, processamento assíncrono, persistência de dados e arquitetura de aplicações**.

🎓 Graduando em **Análise e Desenvolvimento de Sistemas**

🎯 Aberto a oportunidades em **Backend / Software Engineering**, principalmente com **Java ou Python**, APIs, integrações e cloud.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-André_Ferreira-0077B5?style=flat-square\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/andre-ferreira30)
[![GitHub](https://img.shields.io/badge/GitHub-AndreLopes30-181717?style=flat-square\&logo=github\&logoColor=white)](https://github.com/AndreLopes30)

---

## 🛠️ Tech Stack

### Backend

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square\&logo=openjdk\&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square\&logo=springboot\&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square\&logo=fastapi\&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square\&logo=typescript\&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square\&logo=nestjs\&logoColor=white)

### Data & Messaging

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square\&logo=postgresql\&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square\&logo=redis\&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square\&logo=apachekafka\&logoColor=white)
![Amazon SQS](https://img.shields.io/badge/Amazon_SQS-FF4F8B?style=flat-square\&logo=amazonsqs\&logoColor=white)

### Cloud, DevOps & Observability

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square\&logo=docker\&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square\&logo=kubernetes\&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square\&logo=amazonwebservices\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square\&logo=githubactions\&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square\&logo=opentelemetry\&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square\&logo=prometheus\&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square\&logo=grafana\&logoColor=white)

### Também utilizo

`SQLAlchemy` · `JPA/Hibernate` · `Flyway` · `Alembic` · `JUnit` · `Mockito` · `Pytest` · `Testcontainers` · `n8n` · `C#/.NET`

Frontend como conhecimento complementar: `React` · `Angular` · `Vue.js` · `JavaScript`

---

# 🚀 Projetos em destaque

## 🥇 [OrderFlow Platform](https://github.com/AndreLopes30/orderflow-platform)

**Java 21 · Spring Boot · Kafka · PostgreSQL · Redis · Docker · Kubernetes**

Plataforma backend orientada a eventos composta por microsserviços de pedidos e notificações, criada para explorar desafios reais de **consistência, mensageria, redelivery, concorrência e observabilidade**.

### Destaques

* arquitetura de **microsserviços**;
* eventos assíncronos com **Apache Kafka**;
* **Transactional Outbox** para consistência entre PostgreSQL e Kafka;
* entrega `at-least-once` com consumidor **idempotente**;
* retry com backoff e **Dead Letter Topic**;
* cache-aside com **Redis**;
* integração real com PostgreSQL, Kafka e Redis usando **Testcontainers**;
* observabilidade com **OpenTelemetry, Prometheus, Grafana e Tempo**;
* containers com Docker e manifests para **Kubernetes**;
* pipeline de CI com **GitHub Actions** e validação end-to-end via Docker Compose.

`Event-Driven Architecture` · `Kafka` · `Transactional Outbox` · `Idempotency` · `Retry/DLT` · `Redis` · `Observability`

---

## 🥈 [Distributed Wagering Processor](https://github.com/AndreLopes30/junglegaming-backend-challenge)

**TypeScript · NestJS · PostgreSQL · AWS SQS · Docker**

Backend para processamento assíncrono de apostas e movimentações financeiras, com foco em **concorrência, consistência e resiliência**.

### Destaques

* API e workers com **NestJS**;
* processamento assíncrono com **AWS SQS**;
* ambiente local utilizando **LocalStack**;
* idempotência persistente;
* padrões **Inbox / Outbox**;
* ledger append-only;
* controle de concorrência por carteira;
* retry e Dead Letter Queue;
* cenários de teste concorrentes e multiprocessamento;
* Docker Compose para execução da infraestrutura.

`NestJS` · `SQS` · `Concurrency` · `Idempotency` · `Inbox/Outbox` · `DLQ`

---

## 🥉 [LeadFlow AI](https://github.com/AndreLopes30/leadflow-ai)

**Python · FastAPI · n8n · PostgreSQL · Docker**

Pipeline de automação para coleta, classificação e roteamento de leads, integrando workflows e backend através de APIs e webhooks.

```text
Webhook
   ↓
n8n
   ↓
Validação / Normalização
   ↓
FastAPI
   ↓
Scoring e regras de negócio
   ↓
PostgreSQL
   ↓
Roteamento
```

### Destaques

* integração entre **n8n e FastAPI**;
* webhooks;
* contratos e validação com Pydantic;
* scoring e regras de roteamento;
* persistência com PostgreSQL e SQLAlchemy;
* testes automatizados;
* execução com Docker Compose.

`FastAPI` · `n8n` · `Webhooks` · `API Integration` · `Automation`

---

## ⚡ [Nexus API](https://github.com/AndreLopes30/nexus-api)

**Python · FastAPI · PostgreSQL · SQLAlchemy · Docker**

API REST desenvolvida com foco em fundamentos sólidos de backend, autenticação, persistência e qualidade de código.

### Destaques

* FastAPI;
* PostgreSQL e SQLAlchemy;
* migrations com Alembic;
* autenticação JWT;
* autorização baseada no usuário autenticado;
* Docker;
* testes automatizados com Pytest;
* análise estática com Ruff;
* documentação OpenAPI;
* CI com GitHub Actions.

`FastAPI` · `PostgreSQL` · `JWT` · `Docker` · `CI`

---

# 📦 Outros projetos

| Projeto                                                                            | Stack / foco                                                                |
| ---------------------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| [Escola API](https://github.com/AndreLopes30/escola-java-api)                      | Java 21, Spring Boot, Spring Security, JWT, PostgreSQL, JPA, Testcontainers |
| [TicketFlow API](https://github.com/AndreLopes30/ticketflow-api)                   | ASP.NET Core, EF Core, PostgreSQL, async, Testcontainers                    |
| [Penny Budget Tracker](https://github.com/AndreLopes30/penny-budget-tracker)       | FastAPI, React, TypeScript, PostgreSQL, AWS                                 |
| [Korp — Desafio Técnico](https://github.com/AndreLopes30/Korp_Teste_AndreFerreira) | ASP.NET Core, Angular, EF Core, integração entre serviços                   |
| [Catálogo de Carros](https://github.com/AndreLopes30/catalogo-de-carros)           | Python, Flask, SQLite, Docker                                               |

---

## 💼 Experiência profissional aplicada

Além dos projetos públicos, minha experiência profissional envolve:

* desenvolvimento e sustentação backend com **Python**;
* análise e evolução de **APIs REST e integrações**;
* endpoints e contratos de integração;
* autenticação e **OAuth2**;
* **webhooks**;
* PostgreSQL e SQL;
* regras de negócio;
* troubleshooting e investigação de incidentes;
* correção de bugs e melhorias contínuas;
* documentação e refinamento técnico;
* suporte e sustentação de sistemas em produção;
* análise de performance de consultas com `EXPLAIN ANALYZE`.

---

## 📫 Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-André_Ferreira-0077B5?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/andre-ferreira30)

📧 **[ferreiraandre833@gmail.com](mailto:ferreiraandre833@gmail.com)**

📍 **São Paulo, Brasil**
