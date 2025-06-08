# E-Commerce Microservices Platform 🛒

A full-stack microservices-based e-commerce application using:

- **Backend:** Java, Spring Boot (Auth, Catalog, Orders, Payments)
- **Database:** MySQL
- **Frontend:** React.js
- **DevOps:** Docker, Docker Compose

---

## 🔧 Features

- 🔐 JWT Authentication with Role-Based Access Control
- 🗂 RESTful APIs for product, order, and payment management
- 🗃 MySQL with indexing for optimized queries
- 📦 Dockerized microservices with `docker-compose`
- 🎨 React UI to browse products and interact with backend

---

## 🧱 Microservices Overview

| Service        | Port  | Description                       |
|----------------|-------|-----------------------------------|
| Auth Service   | 8081  | Login, Register, JWT Auth         |
| Catalog Service| 8082  | Product listing & management      |
| Order Service  | 8083  | Order placement & user orders     |
| Payment Service| 8084  | Dummy payment processing          |
| React Frontend | 3000  | UI interface                      |
| MySQL DB       | 3306  | Data persistence                  |

---

## 🚀 Getting Started

### 1. Prerequisites
- Docker & Docker Compose
- Java 17+
- Node.js (for frontend)

### 2. Run via Docker Compose
```bash
docker-compose up --build
