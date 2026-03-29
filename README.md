# Rust Log Aggregator

> Log aggregation service with Rust, Tokio, and time-series storage

## ✨ Features
- User authentication with JWT
- CRUD operations for main resources
- RESTful API with proper status codes
- Database migrations and seed data
- Docker containerization

## 🧰 Tech Stack
Rust, Axum, PostgreSQL, SQLx, Docker

## 🏗️ Architecture
Backend service with Rust, frontend user interface, and database persistence

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/rust-log-aggregator
cd rust-log-aggregator

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
