# 🛒 SmartBasket
**SmartBasket** is an intelligent grocery price optimizer and meal-planning engine.  
It combines real-time price scraping, product normalization, cost-efficient basket optimization, and AI-powered meal generation — helping users save money every time they shop.

[![Last Commit](https://img.shields.io/github/last-commit/samuelpmvm/smartbasket)](https://github.com/samuelpmvm/smartbasket)

[Build Status](https://github.com/samuelpmvm/smartbasket/actions)

[![License](https://img.shields.io/github/license/samuelpmvm/smartbasket)](LICENSE)
---

## ✨ Features

### 🔧 Phase 1 — Core Infrastructure
- Spring Boot backend (modular architecture)
- Selenium scrapers for retailers
- Product & price normalization engine
- Fast REST Price API
- Docker & Kubernetes-ready deployment

### 🚀 Phase 2 — MVP
- Basket optimization algorithm (cheapest total cost)
- Mobile frontend integration (shopping planner)
- Basic AI meal generator
- Caching & performance boosts

### 📈 Phase 3 — Expansion
- Support for multiple retailers
- 50–100 curated recipes
- Monitoring for scrapers
- Beta testing & refinement

### 💰 Phase 4 — Monetization & Launch
- AdMob / affiliate links
- Premium AI-powered features
- Public release (iOS / Android)

---

## 🧱 Tech Stack

### Backend
- **Java 21+**
- **Spring Boot**
- **Spring Data JPA**
- **PostgreSQL**
- **Selenium WebDriver**
- **Docker / Kubernetes**

### DevOps
- Docker Compose
- Helm Charts
- GitHub Actions (planned)

### AI (planned)
- Meal generation
- Basket recommendations
- Ingredient substitutions
- Cost-efficiency scoring

---

## 📂 Project Structure (planned)

```
backend/
  price-api/
  scraper-service/
  normalizer/
  common/
frontend/
devops/
docs/
```

---

## ▶️ Getting Started

### Prerequisites
- Java 21+
- Maven 3.8+
- Docker / Docker Compose

### Clone the repo
```bash
git clone https://github.com/samuelpmvm/smartbasket.git
cd smartbasket
```

### Build
```bash
mvn clean install
```

### Run (local)
```bash
docker-compose up -d postgres
mvn spring-boot:run
```

### Run PostgreSQL via Docker
```bash
docker-compose up -d
```

---

## 🧪 Testing
```bash
mvn test
```

---

## 📌 Roadmap

- [ ] Price API prototype
- [ ] First retailer scraper
- [ ] Normalization engine
- [ ] Basket optimizer MVP
- [ ] Meal planner AI integration
- [ ] Mobile app integration
- [ ] Monitoring & alerting
- [ ] App Store release

---

## 🤝 Contributing
Contributions, issues, and feature requests are welcome.  
Feel free to open a discussion or submit a PR.

---

## 📜 License
MIT License — free to use and modify.

---

## 📬 Contact
Project maintained by **SmartBasket Team**.

---
