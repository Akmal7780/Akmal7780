# Hi there 👋 I'm Akmal Axrorov

**Software Engineer** — Java/Spring Boot & Python/Django. I build scalable, production-ready backend systems and the fullstack apps around them.

📍 Jizzakh, Uzbekistan · 💼 Open to work

---

## 🚀 About Me

I build backend systems that are meant to run in production, not just in `runserver` or `mvn spring-boot:run`.
My work spans both the **Java/Spring Boot** and **Python/Django** ecosystems — designing REST APIs, modeling relational data, securing multi-tenant systems with JWT/RBAC, moving heavy work into background workers, streaming events, and shipping everything with Docker.

Currently working as a **Software Engineer at IT-Progress**, where I built the backend of a multi-tenant SaaS HRM platform from scratch. Before that, I completed a 4-month Python/Django internship at **Kroxus Soft**, and I've independently shipped several complete fullstack systems on my own — including a multi-tenant warehouse SaaS and a core banking platform.

I've also been going deeper into **real-time systems (WebSockets)**, **event-driven architecture (Kafka)**, and **performance tuning under load** (connection pooling, load testing).

---

## 🛠 Tech Stack

**Backend**
`Java 17` · `Spring Boot 3.x` · `Python` · `Django` · `Django REST Framework` · `Django Channels` · `FastAPI`

**Frontend**
`React` · `TypeScript` · `Ant Design`

**Database & Caching**
`PostgreSQL` · `JPA / Hibernate` · `Flyway` · `Redis` · `PgBouncer`

**Async & Messaging**
`Celery` · `Kafka` · `WebSocket (STOMP/SockJS)`

**Infrastructure**
`Docker` · `Docker Compose` · `Nginx` · `MinIO (S3)`

**Auth & Docs**
`JWT (access/refresh, rotation)` · `RBAC` · `Google OAuth 2.0` · `Swagger / OpenAPI`

**Testing & Tooling**
`JUnit 5` · `MockMvc` · `ArchUnit` · `Gatling` · `Locust` · `ClamAV`

---

## 📦 Featured Projects

### 🕒 WorkTime HRM (Fullstack)

Multi-tenant HR & attendance management SaaS for companies with multiple branches — built at IT-Progress.

- Multi-tenant architecture with tenant-ownership checks on every request (closes cross-tenant IDOR leaks)
- Face-recognition attendance via a dedicated Python/FastAPI microservice (DeepFace, YOLOv8, liveness detection)
- Permission-based RBAC across 12 roles, GPS check-in/out, two-step payroll approval
- JWT auth with rotation/revocation, WebSocket notifications, one-command Docker Compose stack

**Stack:** Java 17 · Spring Boot 3 · PostgreSQL · Flyway · JWT · Docker · React · TypeScript · Python · FastAPI

[Backend](https://github.com/Akmal7780/worktime-hrm-backend) · [Frontend](https://github.com/Akmal7780/worktime-hrm-frontend)

---

### 📦 QanotSaaS — Ombor (Fullstack)

Multi-tenant warehouse & sales management SaaS for small and medium businesses.

- Multi-tenant data isolation, real-time inventory tracking, purchases & sales
- Supplier/debtor ledgers, full audit trail, Excel/PDF report exports
- Background jobs via Celery, MinIO file storage, Docker Compose deployment

**Stack:** Python · Django 5.1 · DRF · PostgreSQL · Celery · Redis · MinIO · React · Ant Design · Docker

[Backend](https://github.com/Akmal7780/ombor-tizimi) · [Frontend](https://github.com/Akmal7780/warehouse_frontend)

---

### 🏦 BankCore — Core Banking System (Fullstack)

Modular-monolith core banking platform: ledger, accounts, loans, deposits, cards, and compliance.

- Double-entry ledger, automated loan decisioning, interest-bearing deposits
- AML/compliance checks, audit logging, automated end-of-day batch processing
- Load-tested with Gatling: 100 concurrent users, 0% errors, ~102 req/s

**Stack:** Java 21 · Spring Boot 3 · PostgreSQL · ArchUnit · Gatling · React · TypeScript

---

### 💬 [Real-Time Chat Application](https://github.com/Akmal7780/chat-app) (Fullstack)

A production-style real-time messenger built on Django Channels with a React frontend — built during my internship at Kroxus Soft.

- WebSocket messaging with delivered / read receipts, Telegram-style replies & reactions
- Typing indicators, online/offline presence, group and private chats, message search
- Chunked upload for large files stored in MinIO, with async ClamAV virus scanning via Celery
- JWT + Google OAuth authentication

**Stack:** Django · Channels · DRF · PostgreSQL · Redis · Celery · MinIO · ClamAV · React (Vite) · Docker

---

### ✅ [Task Manager Backend](https://github.com/Akmal7780/task-manager-backend)

A task management API built around performance and event-driven design — built during my internship at Kroxus Soft.

- Task CRUD, assignment, status updates and activity tracking
- Real-time notifications through a Kafka producer/consumer pipeline
- PgBouncer connection pooling for high-concurrency workloads, Redis caching
- Load-tested with Locust, deployed behind Nginx with Docker Compose

**Stack:** Django · DRF · PostgreSQL · PgBouncer · Redis · Kafka · Nginx · Locust · Docker

---

### 🛒 [E-commerce Backend API](https://github.com/Akmal7780/ecommerce-backend-api)

A complete, production-ready backend for an online store — built during my internship at Kroxus Soft.

- JWT authentication + Google OAuth login, product catalog with categories, brands & search
- Cart, wishlist, orders, delivery addresses, and product reviews & ratings
- Payme / Click payment integration, Celery background tasks, Swagger API docs

**Stack:** Django · DRF · PostgreSQL · Redis · Celery · JWT · Google OAuth · Swagger · Docker

---

## 🧠 What I've Worked With

- Designing REST APIs from scratch in both Spring Boot and Django, documented with Swagger/OpenAPI
- Multi-tenant architecture and permission-based RBAC
- Relational data modeling and query optimization in PostgreSQL
- Background job processing with Celery + Redis
- Real-time communication with Django Channels, WebSockets, and STOMP/SockJS
- Event streaming and async consumers with Kafka
- Object storage and file pipelines with MinIO
- Containerization and multi-service orchestration with Docker Compose
- Load testing and performance tuning (Gatling, Locust, PgBouncer, caching)

---

## 📈 Currently Improving

- Advanced Spring Boot & Django architecture patterns
- System design fundamentals
- Microservices and event-driven architecture
- CI/CD pipelines and observability

---

## 📊 GitHub Stats

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=Akmal7780&show_icons=true&hide_border=true" height="160" alt="Akmal's GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Akmal7780&layout=compact&hide_border=true" height="160" alt="Top languages" />
</p>

---

## 📫 Contact

- **Portfolio:** https://github.com/Akmal7780/portfolio
- **LinkedIn:** https://www.linkedin.com/in/akmal-axrorov-b24198238/
- **Telegram:** [@akmalaxrorov](https://t.me/akmalaxrorov)
- **Email:** axrorovakmal4@gmail.com

---

<p align="center"><i>Open to Software Engineer roles — feel free to reach out.</i></p>
