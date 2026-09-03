# Python & FastAPI Parallel Track

## Purpose

This track runs alongside the AltSchool AI-Powered Full-Stack Engineering
curriculum.

The goal is not to study two separate full-stack programs.

Instead, it will:

- maintain and refresh my existing Python backend skills;
- map Node.js and Express concepts to Python and FastAPI;
- deepen my backend engineering knowledge;
- connect concepts across programming languages and frameworks;
- apply relevant concepts to GetHome;
- prepare me to build production-grade Python/FastAPI backends;
- combine JavaScript/TypeScript full-stack skills with Python backend engineering.

---

## Learning Strategy

AltSchool remains the primary curriculum.

The Python/FastAPI track follows three modes:

### 1. Refresh Mode

Used for Python concepts I have previously learned.

Focus:
- recall;
- modern Python syntax;
- short exercises;
- identifying knowledge gaps.

Avoid unnecessarily restarting from beginner-level material.

### 2. Mirror Mode

Used when AltSchool teaches a backend concept using Node.js, Express.js,
NestJS, or related JavaScript/TypeScript technologies.

Process:

1. Understand the language-independent engineering concept.
2. Understand the Node/Express implementation.
3. Learn the Python/FastAPI implementation.
4. Compare important architectural differences.
5. Implement a small equivalent example.

### 3. Deepen Mode

Used for important backend engineering topics that deserve deeper study.

Examples:

- asynchronous programming;
- API architecture;
- PostgreSQL;
- SQLAlchemy;
- Alembic;
- authentication and authorization;
- testing;
- background jobs;
- Redis and caching;
- queues;
- WebSockets;
- security;
- Docker;
- CI/CD;
- observability;
- system design;
- AI service integration.

---

# Semester 1 — Python Maintenance

## Python Fundamentals Refresh

Mirror relevant JavaScript programming concepts with Python.

Topics:

- variables and data types;
- strings and numbers;
- lists, tuples, sets, and dictionaries;
- conditionals;
- loops;
- functions;
- scope;
- exceptions;
- basic file handling;
- comprehensions;
- modules and imports;
- type hints.

### Goal

Restore Python fluency without repeating an entire beginner Python course.

### Practice

Complete selected programming exercises first in the language required by
AltSchool and then reproduce selected exercises in Python.

---

# Semester 2 — Python and Backend Foundations

## Modern Python

Topics:

- comprehensions;
- unpacking;
- decorators;
- iterators and generators;
- context managers;
- typing;
- dataclasses;
- Python project structure.

## Packages and Environments

Topics:

- virtual environments;
- pip;
- modern dependency management;
- pyproject.toml;
- environment variables;
- application configuration.

## Object-Oriented Python

Topics:

- classes and objects;
- encapsulation;
- inheritance;
- composition;
- polymorphism;
- abstract classes;
- protocols;
- generics;
- dependency inversion.

## Asynchronous Python

Topics:

- synchronous vs asynchronous execution;
- coroutines;
- async and await;
- event loops;
- asynchronous I/O;
- HTTP clients;
- concurrency concepts.

## FastAPI Foundations

Topics:

- FastAPI application setup;
- ASGI and Uvicorn;
- path operations;
- path parameters;
- query parameters;
- request bodies;
- response models;
- status codes;
- OpenAPI;
- Swagger documentation.

## API Design and Architecture

Topics:

- REST principles;
- resource modelling;
- API versioning;
- project structure;
- routers;
- controllers/path operations;
- services;
- repositories;
- separation of concerns;
- modular monoliths;
- introduction to microservices.

---

# Semester 3 — FastAPI Application Development

## Express.js ↔ FastAPI Mirror

Study FastAPI alongside AltSchool's Express.js API development.

Topics:

- APIRouter;
- request and response lifecycle;
- Pydantic models;
- validation;
- dependency injection with Depends();
- middleware;
- exception handling;
- pagination;
- filtering;
- authentication;
- authorization;
- JWT;
- file uploads;
- rate limiting;
- configuration management.

## Architecture Mapping

Node/Express:

Router
→ Middleware
→ Controller
→ Service
→ Database

Python/FastAPI:

APIRouter
→ Dependencies
→ Path Operation / Controller
→ Service
→ Repository
→ SQLAlchemy
→ Database

Important:

An Express controller is not equivalent to a FastAPI dependency.

FastAPI Depends() provides dependency injection and is commonly used for
database sessions, authentication, authorization and reusable application
logic.

---

# Semester 4 — Production Backend Engineering

## PostgreSQL and SQLAlchemy

Topics:

- relational database modelling;
- PostgreSQL;
- tables and relationships;
- primary and foreign keys;
- joins;
- constraints;
- indexes;
- transactions;
- normalization;
- SQLAlchemy 2.x;
- ORM relationships;
- sessions;
- query construction;
- Alembic migrations.

## Background Jobs and Queues

Topics:

- background processing;
- scheduled jobs;
- task queues;
- producers and consumers;
- retries;
- idempotency;
- Redis;
- Celery / Dramatiq / ARQ concepts.

## Caching and Integrations

Topics:

- caching strategies;
- Redis;
- cache invalidation;
- external APIs;
- webhooks;
- integration design.

## Real-Time Systems

Topics:

- WebSockets;
- Server-Sent Events;
- polling;
- realtime notifications;
- asynchronous communication.

## Testing

Topics:

- pytest;
- unit tests;
- integration tests;
- API tests;
- FastAPI TestClient/httpx;
- mocking;
- test databases;
- end-to-end concepts.

## Production FastAPI

Topics:

- Docker;
- application configuration;
- CI/CD;
- logging;
- monitoring;
- profiling;
- error tracking;
- performance optimization;
- deployment architecture.

## System Design

Topics:

- requirements gathering;
- capacity estimation;
- scalability;
- reliability;
- availability;
- API design;
- database scaling;
- caching;
- queues;
- load balancing;
- architectural trade-offs;
- design reviews.

Apply system-design exercises to GetHome.

## API and Application Security

Topics:

- OWASP API Top 10;
- authentication;
- authorization;
- OAuth2;
- JWT;
- password hashing;
- CORS;
- rate limiting;
- input validation;
- secure headers;
- secrets management;
- common API attacks.

## AI Integration

Topics:

- consuming AI APIs from Python;
- structured AI outputs;
- AI service architecture;
- background AI processing;
- document processing;
- responsible AI;
- evaluation;
- observability;
- identifying appropriate AI use cases.

Explore relevant applications within GetHome without forcing AI into
features where conventional software is sufficient.

---

# Technology Mapping

| JavaScript / Node | Python / FastAPI |
|---|---|
| Node.js | Python runtime |
| npm | pip / uv |
| package.json | pyproject.toml |
| Express.js | FastAPI |
| Express Router | APIRouter |
| Route handler | Path operation |
| Controller | Path operation / controller layer |
| Middleware | Middleware |
| req.params | Path parameters |
| req.query | Query parameters |
| req.body | Pydantic request model |
| Validation libraries | Pydantic |
| Dependency injection / reusable middleware | Depends() |
| Error middleware | HTTPException / exception handlers |
| Auth middleware | FastAPI security dependencies |
| Prisma / Sequelize | SQLAlchemy |
| Database migrations | Alembic |
| Jest / Supertest | pytest / httpx |
| process.env | Environment variables / Pydantic Settings |
| Promise / async-await | Coroutine / async-await |
| BullMQ | Celery / Dramatiq / ARQ |
| Redis | Redis |
| WebSockets | FastAPI / Starlette WebSockets |
| Swagger / OpenAPI tooling | FastAPI OpenAPI / Swagger |
| Docker | Docker |
| CI/CD | CI/CD |

---

# Lesson Workflow

After an AltSchool lesson, use the following request:

> **Python Mirror — [lesson title]**
>
> Today AltSchool covered: [topics].
>
> Code/concepts covered: [optional].
>
> Give me the Python/FastAPI equivalent, important differences, what I
> need to refresh, and one short exercise connected to GetHome.

For video lessons, provide any combination of:

- lesson title;
- lesson outline;
- notes;
- screenshots;
- code;
- transcript;
- concepts remembered from the lesson.

A full transcript is not required.

---

# Workload Rule

The parallel track must support, not compete with, the AltSchool program.

Default:

- approximately two Python sessions per week;
- approximately 45–60 minutes per session;
- increase depth when backend topics begin;
- skip Python mirroring when an AltSchool lesson is purely frontend and has
  no useful Python/backend equivalent.

---

# GetHome Integration

GetHome will serve as the primary long-term application for selected
backend concepts.

Potential areas include:

- users and roles;
- authentication;
- tenants;
- landlords;
- agents;
- property listings;
- property verification;
- search and filtering;
- tenancy;
- leases;
- payments;
- maintenance;
- notifications;
- lender integrations;
- flexible rent;
- document processing;
- fraud/risk systems;
- realtime features;
- AI-assisted features.

Not every lesson needs to modify the production GetHome codebase.

Small isolated exercises should be used when experimenting with concepts
that do not yet belong in GetHome.

---

# End Goal

By the end of the program, the target skill profile is:

Frontend:
HTML + CSS + JavaScript + TypeScript + React

Backend:
Python + FastAPI + Node.js + Express.js

Data:
PostgreSQL + SQLAlchemy + MongoDB + Redis

Engineering:
Git + Testing + Docker + CI/CD + Security + System Design + AI-Assisted Development

The objective is not merely framework familiarity.

The objective is the ability to understand backend engineering concepts
independently of a particular language and implement them effectively in
both the JavaScript/TypeScript and Python ecosystems.