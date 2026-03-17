
# 🚀 Analytics Platform (Fullstack Project)

## 📌 Overview
Fullstack data analytics platform with API, dashboard and ETL pipeline.

## ⚙️ Features
- Upload dataset (JSON)
- Real-time stats calculation (average, sum, count)
- REST API (Fastify)
- ETL pipeline (Python)
- Simple dashboard interface

## 🧱 Tech Stack
- Node.js (Fastify)
- HTML / JS frontend
- Python (ETL)
- Docker-ready (optional)

## 🚀 Running locally

### Backend
```bash
cd apps/api
npm init -y
npm install fastify
node src/server.js
```

### Frontend
Open:
```
apps/web/index.html
```

### ETL
```bash
cd scripts
python etl.py
```

## 🌐 Deployment
- Frontend: Vercel
- Backend: Railway

## 📊 Example Input
```json
[{"value":10},{"value":20},{"value":30}]
```

## 💼 Author
Built for portfolio to demonstrate fullstack + data skills.
