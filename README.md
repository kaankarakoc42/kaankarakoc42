# Kaan Karakoç

**Backend Developer (Go) · Distributed Systems · Microservices**

I build systems that don’t fall apart under pressure.

Currently working on **TaskForge** — a distributed task orchestration platform built with event-driven architecture.

---

## 🚀 What I Actually Do

- Design and build **event-driven systems** using Kafka
- Develop **Go microservices** with real production concerns
- Handle **distributed state, retries, and failure scenarios**
- Build full observability stacks (**Prometheus + Grafana + Jaeger**)
- Deploy systems on **Kubernetes (k3s / minikube)**

---

## 🧠 Tech Stack

### Backend
- Go (main)
- Python (Django, Flask)
- Node.js (Express)

### Frontend
- React
- React Native

### Infrastructure
- Docker / Docker Compose
- Kubernetes (k3s, minikube)
- Nginx / Traefik
- Cloudflare

### Messaging & Data
- Apache Kafka
- PostgreSQL

### Observability
- Prometheus
- Grafana
- Jaeger (OpenTelemetry)

---

## ⚙️ Featured Project

### 🔥 TaskForge

> Distributed task orchestration system

**Key Features:**
- Async task processing with Kafka
- Retry & scheduling system
- WebSocket real-time updates
- Outbox pattern implementation
- Full observability (metrics + tracing)

```diff
API → Kafka → Worker → DB → WebSocket
