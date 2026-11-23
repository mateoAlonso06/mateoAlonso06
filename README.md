# Mateo Alonso

Backend Software Engineer specialized in **Java 21**, **Spring Boot**, and **AI Engineering**.

![Java](https://img.shields.io/badge/Java_21-007396?style=flat-square&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring AI](https://img.shields.io/badge/Spring_AI-6DB33F?style=flat-square&logo=spring&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

Focused on designing scalable modular architectures, building resilient domain models, and integrating LLMs into enterprise backend workflows.

---

### ⚙️ Selected Projects

#### 🤖 [expense-bot](https://github.com/mateoAlonso06/expense-bot)
Financial expense-tracking bot processing natural language, receipt photos, and voice notes via Telegram webhooks.
* **Architecture:** Modular monolith under strict Hexagonal Architecture enforced at test-time via **ArchUnit**.
* **AI Integration:** **Spring AI 2.0** (OpenAI & JDBC memory) with an *eval dataset* pipeline for structured entity extraction accuracy and conversational corrections.
* **Security & Observability:** **Keycloak** (OAuth2 Resource Server / PKCE), **Testcontainers** (real PostgreSQL), and a full observability stack (**Prometheus, Grafana, Loki, Tempo**).

#### 🏫 Library Management System (CRESTA)
Domain-driven REST API replacing a 15-year legacy institutional system in a production environment.
* Designed the core domain logic for loans, reservations, and sanctions under a modular MVC architecture.
* Built an ETL pipeline migrating **+20,000 historical records** to MySQL without data loss.
* Implemented JWT/RBAC security, background job automation (Cron Jobs), and Nginx rate-limiting.

---

### 🧰 Technical Stack

| Category | Technologies & Tools |
| :--- | :--- |
| **Core & Frameworks** | Java 21, Spring Boot 4, Spring AI 2.0, Spring Security, Spring Data JPA |
| **Architecture & Testing** | Hexagonal Architecture, Modular Monolith, DDD, SOLID, ArchUnit, Testcontainers, JUnit, Mockito |
| **Data & Persistence** | PostgreSQL, MySQL, Redis, Flyway, JdbcClient |
| **DevOps & Infrastructure** | Keycloak (OAuth2), Docker, GitHub Actions, Nginx, Prometheus, Grafana, Loki, Tempo, Linux |

---

### 📌 Architectural Principles

* **Domain Isolation:** Business rules remain pure Java, strictly detached from frameworks and infrastructure details.
* **Automated Guardrails:** Architecture boundaries enforced via ArchUnit tests; integration flows validated against real database engines using Testcontainers.
* **Deterministic AI Integration:** Leveraging LLMs through structured JSON outputs, context boundaries, and quantitative evaluation pipelines.

---

### 📈 GitHub Stats

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=mateoAlonso06&show_icons=true&theme=dark&hide_border=true&include_all_commits=true&cache_seconds=1800" height="150" alt="Mateo Alonso GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mateoAlonso06&layout=compact&theme=dark&hide_border=true&langs_count=6&cache_seconds=1800" height="150" alt="Top Languages" />
</p>

---

### 📬 Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/mateoalonso20)
[![Gmail](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:alonsomateo2002@gmail.com)
