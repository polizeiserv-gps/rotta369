# Vehicle Tracking Platform - Enterprise SaaS

## 🚀 Run Locally

1. Copy environment

cp .env.example .env

2. Install dependencies

npm install

3. Run database migration

npm run migrate

4. Start containers

cd infra
docker compose up --build

API: http://localhost:3000  
Realtime: http://localhost:4000  
Postgres: 5432  
Redis: 6379  

---

## 🏗 Architecture

- Node.js + TypeScript
- Express API
- Prisma ORM
- PostgreSQL
- Redis Pub/Sub
- Socket.IO
- Docker
- Production-ready logging & validation
