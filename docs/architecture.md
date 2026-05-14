# Ascend Architecture

## Overview

Ascend is designed as a modern SaaS platform composed of:

- React frontend
- Go API
- Go workers
- PostgreSQL database
- Redis queue system
- MinIO object storage

## High-level architecture

```txt
Frontend (React + Vite)
        ↓
Go API
        ↓
PostgreSQL + pgvector
        ↓
Redis + Asynq
        ↓
Go Workers
```

## Main domains

- Authentication
- Candidate profiles
- Resume management
- Job aggregation
- Matching engine
- Document generation
- Application tracking
- Notifications
