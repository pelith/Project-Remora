# EthGlobal HackMoney 2026

This repo has two submodules. How to run them:

## How to run

### Project-Remora-Backend

```bash
cd Project-Remora-Backend
docker compose up -d postgres
ENV=local go run ./cmd/migration
ENV=local go run ./cmd/api
```

API base URL: **http://127.0.0.1:8080**

### Project-Remora-Frontend

```bash
cd Project-Remora-Frontend
pnpm install
pnpm dev
```
