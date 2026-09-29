# Tech Stack Summary

| Layer | Selected | Reason |
|---|---|---|
| Client | React Native + Expo + TypeScript | One codebase for iOS/Android/web, large talent pool, fast releases |
| Core API | FastAPI | Fast development, typed validation, same language as ML code |
| AI service | FastAPI + scikit-learn / PyTorch | Independent retraining and deployment |
| Database | PostgreSQL (Supabase) + pgvector | ACID integrity, joins, row-level security |
| Auth | Supabase Auth | Integrates with row-level security, low cost |
| Real-time | Supabase Realtime | Feed and notifications from database changes |
| Cache / jobs | Redis | Caching, rate limiting, queues |
| Media | Supabase Storage + CDN | Photos and videos |
