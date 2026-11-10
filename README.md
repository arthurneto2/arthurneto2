### Olá! Eu sou Arthur Neto 👋

Desenvolvedor **backend** em **Java/Spring Boot** e **C#/.NET**, graduando em Sistemas de Informação na **UFV** (conclusão prevista para julho de 2027).

Meu foco é **consistência de dados e concorrência**: transações ACID, idempotência, controle de concorrência otimista e pessimista, e testes de integração contra bancos reais com Testcontainers.

🎯 **Buscando vaga de estágio ou de desenvolvedor backend júnior** · disponível para trabalho remoto

[![LinkedIn](https://img.shields.io/badge/LinkedIn-arthurneto--dev-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/arthurneto-dev)

---

## 🚀 Projetos em destaque

**[Pediline 2.0](https://github.com/arthurneto2/pediline-showcase)** — SaaS multi-tenant de PDV, comandas e delivery para restaurantes (TCC, em dupla, [no ar](https://pediline.store/pizzaria-bella-massa))
`Java 25` `Spring Boot` `PostgreSQL` `Redis` `React` `React Native`
- Monólito modular para manter pagamento, caixa e estoque em transações ACID; lock pessimista com ordem fixa contra deadlock e pagamentos idempotentes.
- **2.906 testes automatizados**, incluindo 48 classes de integração com Testcontainers que comprovam isolamento entre tenants e comportamento sob concorrência.
- Teste de carga com k6, Prometheus e Grafana: **p95 de 70 ms no pico** e capacidade de 8x para mais de 20x a carga, sem perda nem duplicação de registros.

**[Sistema de Faturamento e Estoque](https://github.com/arthurneto2/Korp_Teste_ArthurRoberto)** — dois microsserviços com bancos independentes (desafio técnico)
`.NET 10` `ASP.NET Core` `PostgreSQL` `Angular` `Docker`
- Consistência sem transação distribuída: comando idempotente garantido pelo banco, concorrência otimista via `xmin`, retentativa seletiva com Polly e compensação explícita.
- 87 testes (xUnit, WireMock, Testcontainers com PostgreSQL real); sobe inteiro com um `docker compose up`.

**[vulnscan](https://github.com/arthurneto2/vulnscan)** — scanner de vulnerabilidades web (SQLi, XSS, autenticação em APIs REST)
`Java 21` `Selenium` `Docker` `Ollama`
- Compara empiricamente detecção heurística e um LLM local sobre um gabarito com alvos reais (DVWA, Juice Shop), medindo precisão, recall e F1.
- Arquitetura hexagonal, CI no GitHub Actions e releases automáticos.

**[Reservas de Salas](https://github.com/arthurneto2/servico-reserva)** — API REST em arquitetura hexagonal com DDD
`Java 25` `Spring Boot 4` `PostgreSQL` `ArchUnit`
- Regras de arquitetura verificadas por testes ArchUnit; fusos horários por sala e um caso de uso que grava e falha na mesma transação.

---

## 🛠️ Tecnologias

**Backend**
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![C#](https://img.shields.io/badge/-C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![.NET](https://img.shields.io/badge/-.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Hibernate](https://img.shields.io/badge/-JPA%2FHibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)

**Bancos de dados e mensageria**
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Flyway](https://img.shields.io/badge/-Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white)

**Testes e qualidade**
![JUnit](https://img.shields.io/badge/-JUnit%205-25A162?style=flat-square&logo=junit5&logoColor=white)
![Testcontainers](https://img.shields.io/badge/-Testcontainers-291A3F?style=flat-square&logo=testcontainers&logoColor=white)
![xUnit](https://img.shields.io/badge/-xUnit-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![k6](https://img.shields.io/badge/-k6-7D64FF?style=flat-square&logo=k6&logoColor=white)

**Infraestrutura e observabilidade**
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Azure](https://img.shields.io/badge/-Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

**Frontend (apoio)**
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/-React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Angular](https://img.shields.io/badge/-Angular-DD0031?style=flat-square&logo=angular&logoColor=white)

---

## 📌 Sobre mim

- 🎓 Bacharelado em Sistemas de Informação — UFV, Campus Rio Paranaíba (2024 – 2027)
- 👨‍🏫 Monitor de Estruturas de Dados na UFV desde março de 2026
- 💼 Consultor de negócios na Empresa Júnior INFOALTO (2025 – 2026)
- 🧩 Praticando algoritmos no [LeetCode](https://github.com/arthurneto2/LeetCode)
- 🌎 Inglês avançado

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/arthurneto2/arthurneto2/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/arthurneto2/arthurneto2/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/arthurneto2/arthurneto2/output/github-contribution-grid-snake.svg">
</picture>
