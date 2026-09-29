# FitFlow Redesign

Technology selection and architecture for the FitFlow fitness app redesign (IT3060 - Human Computer Interaction, Lab 05).

## Recommended stack
| Layer | Technology |
|---|---|
| Client (iOS / Android / Web) | React Native + Expo + TypeScript (native modules for HealthKit / Health Connect) |
| Core API | Python / FastAPI (modular monolith) |
| AI/ML service | FastAPI + scikit-learn / PyTorch |
| Database | PostgreSQL on Supabase (pgvector, row-level security) |
| Auth | Supabase Auth |
| Real-time | Supabase Realtime |
| Cache / jobs | Redis + Celery / RQ |
| Storage | Supabase Storage + CDN |

## Repository layout
- `frontend/` - React Native (Expo) app
- `backend/` - FastAPI core API
- `ai-service/` - recommendation / nutrition AI service
- `docs/` - tech stack summary, comparison matrix, architecture diagram, ADRs

## Documents
- [Tech stack summary](docs/tech-stack-summary.md)
- [Comparison matrix](docs/comparison-matrix.md)
- [Architecture diagram](docs/architecture.png)
- [ADR-001](docs/adr/ADR-001-stack.md)

## Author
IT23864306 - Jayawardana V K A
