<div align="center">

# Ivan Vallejos


Backend developer focused on building distributed systems that are reliable by design.

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django_5-092E20?logo=django&logoColor=white)
![Go](https://img.shields.io/badge/Go-actively_developing-00ADD8?logo=go&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-daily_driver-FCC624?logo=linux&logoColor=black)
</div>

I'm a Systems Analyst student in Argentina, working toward my first role
in the industry. My interest is in the construction of scalable services
and the architectural decisions that make them maintainable over time.

---

## What I build

I care about understanding why a system is structured the way it is 
— not just how to make it work. That means thinking about failure modes 
before they happen, separating concerns deliberately, 
and documenting the tradeoffs that shaped each decision.

My current focus is Python backend, with Go as an actively developing
secondary skill.

---

## What I'm working on

**SmartExpense** — a personal finance system combining a Telegram bot
with a web dashboard, built around an async Producer/Consumer architecture.
Running in production on Railway with real users.

- Async task queue (ARQ, similar to Celery) over Redis for job processing
- Idempotent webhook design with deliberate at-most-once delivery tradeoff
- Self-learning expense categorizer that adapts to each user's vocabulary
- 151 tests written against contracts, not implementations
- Full async Django (ASGI) + PostgreSQL + React

**Go webhook receiver** — extracting SmartExpense's webhook intake into a
standalone Go microservice. The goal is a plug-and-play component that absorbs
Telegram traffic and writes to Redis Streams, freeing the Python layer to focus
on business logic.

---

## Where I'm heading

- **Event Siphon** — a data pipeline project combining Go and Python/Polars,
  with NoSQL storage. Focused on understanding event-driven architectures
  and schema design for analytical workloads.
- **Self-hosted infrastructure** — moving SmartExpense off Railway onto a
  VPS, with a proper observability stack for logs, metrics, and failed jobs.
- **Technical writing** — documenting what I build and the decisions behind it,
  starting with SmartExpense's architecture and decision records.

---

## Stack

**Production experience**
Python 3.12 · Django 5 · Django Ninja · ARQ · PostgreSQL · Redis · React

**Actively developing**
Go (concurrency — goroutines, channels)

**Tools**
Docker · GitHub Actions · Railway · Uvicorn · pytest

---

## Links

- [SmartExpense](https://github.com/ivanvallejoss/smartexpense) — the project described above
- [LinkedIn](https://linkedin.com/in/ivanvallejoss)
