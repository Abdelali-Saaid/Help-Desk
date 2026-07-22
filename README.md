# Help-Desk

Real-time IT ticketing and moderation

| Before | After |
|---|---|
| A phone that rang | A queue everyone can see |
| Urgency = the loudest voice | Owner, age and escalation state on every ticket |
| "Where is my ticket?" | Status pushed live to every open dashboard |

TypeScript end to end, a layered API over PostgreSQL, Redis pub/sub fanning
status changes out over WebSockets.

The bugs never threw. The rate limiter returned 429s while Redis held zero
keys it had been counting in memory, per instance, the whole time. Login
returned the full row, password hash included, while the types swore it was
safe. Both surfaced only by booting the real build against real
infrastructure so the app now refuses to start without real secrets and a
live Redis. Types check shapes, not reality.

**TypeScript · React · Drizzle ORM · Redis**

Abdelali Saaid · [Portfolio](https://abdelalisaaid.com) ·
[LinkedIn](https://www.linkedin.com/in/abdelali-saaid)
