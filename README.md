# Ascend

Career intelligence platform for modern job search.

Ascend is an AI-powered SaaS platform designed to help candidates discover relevant job opportunities, analyze offers, adapt application documents, and manage the full application pipeline from one modern dashboard.

## Vision

Build a premium, privacy-conscious career platform focused first on the French job market.

## Core features

- Candidate profile extraction from resumes
- Intelligent job discovery
- AI-assisted job scoring and matching
- Tailored resume and cover letter generation
- Application tracking and reminders
- Modern SaaS dashboard

## Tech stack

### Frontend

- React
- Vite
- TypeScript
- Panda CSS
- React Router
- TanStack Query
- Zustand

### Backend

- Go
- PostgreSQL
- pgvector
- Redis
- Asynq
- MinIO / S3-compatible storage

### Infrastructure

- Docker Compose for local development
- PostgreSQL for relational and vector data
- Redis for queues and caching
- MinIO for file storage

## Repository structure

```txt
apps/
  web/      React Vite frontend
  api/      Go HTTP API
  worker/   Go background workers
infra/      Local infrastructure and deployment files
docs/       Product and technical documentation
```

## Status

Early-stage project initialization.
