<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0f172a,100:0ea5e9&text=DANIELOZA&fontColor=ffffff&fontSize=52&fontAlignY=40&desc=Daniel%20%27DANIELOZA%27%20Danek%20%7C%20Python%20Backend%20Engineer&descAlignY=62" alt="DANIELOZA header" />
</div>

<p align="center">
  I build production-style backend products: multi-tenant APIs, secure auth flows, operations monitoring, and automation bots.
</p>

<p align="center">
  <a href="https://github.com/danieloza/DANIELOZAHUB4"><img src="https://img.shields.io/badge/Flagship-Danex%20Business%20API-0369a1?style=for-the-badge" alt="Danex Business API" /></a>
  <a href="https://github.com/danieloza/DANIELOZAHUB3"><img src="https://img.shields.io/badge/Core-SalonOS-0f766e?style=for-the-badge" alt="SalonOS" /></a>
  <a href="https://github.com/danieloza/DANIELOZAHUB2"><img src="https://img.shields.io/badge/Automation-Faktury%20Bot-9a3412?style=for-the-badge" alt="Faktury Bot" /></a>
  <a href="https://github.com/danieloza/rag-api-starter"><img src="https://img.shields.io/badge/GenAI-RAG%20API%20Starter-14532d?style=for-the-badge" alt="RAG API Starter" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11+-111827?style=flat-square&logo=python&logoColor=ffd43b" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-Production-111827?style=flat-square&logo=fastapi&logoColor=00c7b7" alt="FastAPI" />
  <img src="https://img.shields.io/badge/PostgreSQL%20%7C%20SQLite-Data%20Layer-111827?style=flat-square&logo=postgresql&logoColor=336791" alt="Data" />
  <img src="https://img.shields.io/badge/Docker%20Compose-DevOps-111827?style=flat-square&logo=docker&logoColor=2496ed" alt="Docker" />
  <img src="https://img.shields.io/badge/CI%2FTests-GitHub%20Actions-111827?style=flat-square&logo=githubactions&logoColor=2088ff" alt="CI" />
</p>

## 15-Second Snapshot
- Python backend engineer focused on real product architecture, not toy demos.
- I ship gateway + core + bot ecosystems with tests, contracts, and operational scripts.
- My strongest stack: FastAPI, SQLAlchemy, Telegram bots, Docker, CI, and secure API design.

## Flagship Projects
| Project | What It Proves |
| --- | --- |
| [Danex Business API](https://github.com/danieloza/DANIELOZAHUB4) | Gateway/admin/public layer over SalonOS with JWT + cookie session + CSRF, CRM/invoices, ops metrics/alerts/jobs health, Alembic, Docker compose, CI/tests. |
| [SalonOS](https://github.com/danieloza/DANIELOZAHUB3) | Core multi-tenant booking and visit platform (FastAPI + Telegram bot), reservation status flow, conversion integrity, reports/exports, OpenAPI contract + quality gates. |
| [Danex Faktury Bot](https://github.com/danieloza/DANIELOZAHUB2) | Invoice automation bot with OCR pipeline, hash-based deduplication, review statuses, role-based access, retry/retention flows, and test suite. |
| [Salon Utarg Bot](https://github.com/danieloza/DANIELOZAHUB5) | TeamOps and reporting bot integrated with SalonOS workflows (leave, shift swaps, time clock, Google Sheets reporting). |
| [RAG API Starter](https://github.com/danieloza/rag-api-starter) | FastAPI mini-project for GenAI interviews with `/ingest`, `/ask`, `/health`, local FAISS indexing, and demo-ready setup in 2 minutes. |

## Demo In 2 Minutes
```powershell
git clone https://github.com/danieloza/DANIELOZAHUB4.git
cd DANIELOZAHUB4
powershell -ExecutionPolicy Bypass -File .\scripts\start_demo_stack.ps1 -SeedDanex -SeedDemoData
```

Open after startup:
- `http://127.0.0.1:8001/health`
- `http://127.0.0.1:8001/docs`
- `http://127.0.0.1:8000/docs`

## System Architecture
```mermaid
flowchart LR
    U[Client Apps and Admin UI] --> G[Danex Business API - Gateway and Admin]
    G --> C[SalonOS Core - Booking and Visits]
    G --> F[Danex Faktury Bot - OCR and Invoice Flow]
    C --> T[Salon Utarg Bot - TeamOps and Reports]
    C --> O[Ops Monitoring - Metrics Alerts Jobs Health]
```

## Engineering Signals
- Auth patterns: JWT + secure cookie session + CSRF protection.
- Multi-tenant architecture and tenant-aware routing.
- Contract-first delivery with OpenAPI and CI quality gates.
- Production workflows: migrations, backup/restore drills, smoke and E2E scripts.
- Observability endpoints and operational runbooks.

## GitHub Stats
<p align="center">
  <img height="160" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=danieloza&theme=github" alt="GitHub stats" />
  <img height="160" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=danieloza&theme=github" alt="Top languages" />
</p>

## Target Roles
- Python Backend Engineer
- FastAPI/API Platform Engineer
- GenAI Automation and RAG Integrations
