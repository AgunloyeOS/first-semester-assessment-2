# Python & FastAPI Engineering Journey

## Course Identity

This is a standalone Python and backend engineering curriculum that runs in parallel with the AltSchool AI-Powered Full-Stack Engineering program.

AltSchool remains the primary curriculum for JavaScript, TypeScript, React, Node.js, Express.js, NestJS, and its prescribed technologies.

This track independently develops Python and FastAPI expertise from programming fundamentals through production backend engineering.

The two tracks may reinforce shared software engineering concepts, but neither depends on the other for progression.

---

## Purpose

The goal is to build a complementary Python/backend specialization alongside the broader AltSchool full-stack curriculum.

This journey will:

- rebuild Python knowledge systematically from the foundations;
- restore coding fluency through frequent hands-on programming;
- fill subtle gaps in Python syntax, semantics, and behaviour;
- develop strong problem-solving habits;
- progress from scripts to professionally structured applications;
- build production-grade APIs with FastAPI;
- deepen PostgreSQL, SQLAlchemy, and database engineering skills;
- develop competence in testing, security, asynchronous systems, caching, queues, Docker, CI/CD, and system design;
- connect shared software engineering concepts across Python and JavaScript ecosystems;
- apply advanced concepts to realistic products, including GetHome where appropriate.

The objective is not merely framework familiarity.

The end goal is the ability to understand software and backend engineering concepts independently of a particular language and implement them effectively using Python and the wider backend ecosystem.

---

# Learning Philosophy

## Start From the Foundations

The curriculum begins with beginner Python even though I have previous Python and backend experience.

This is intentional.

The purpose is not to assume that previous knowledge has disappeared, but to:

- reconstruct the language systematically;
- identify forgotten details;
- fill small conceptual gaps;
- rebuild syntax recall;
- restore coding muscle memory;
- develop greater confidence writing programs from a blank file.

Previously mastered material may therefore progress quickly.

---

## Learn by Writing Code

The course should avoid passive tutorial consumption.

The default learning cycle is:

Concept → Demonstration → Recall → Exercise → Independent Challenge → Review → Refactor → Project

Where possible, I should attempt exercises before seeing complete solutions.

AI should function primarily as:

- teacher;
- explainer;
- reviewer;
- debugger;
- pair programmer;
- architecture partner.

It should not replace my own first attempt at solving appropriate programming problems.

---

## Project-Heavy Progression

Small concepts should lead to small programs.

Groups of concepts should lead to mini-projects.

Major sections should lead to larger projects.

Projects should become progressively less guided as competence increases.

Old coursework does not need to be reproduced exactly.

Instead, new projects should exercise equivalent or deeper skills.

---

## Git and GitHub Habit

Meaningful work should be version controlled.

Typical workflow:

Working files → Stage → Commit → Push

Projects and meaningful exercises should be committed with descriptive messages.

The objective is to develop Git usage as a normal engineering habit rather than something performed only for assignments.

---

# Module 1 — Python Foundations

## 1.1 Python and Program Execution

Topics:

- what Python is;
- interpreter vs compiler;
- source code;
- scripts;
- interactive Python;
- `.py` files;
- how Python executes a program;
- statements and expressions;
- syntax errors vs runtime errors;
- reading tracebacks;
- indentation and whitespace;
- basic Python style.

Subtle concepts:

- why indentation is syntax in Python;
- significant vs insignificant whitespace;
- line continuation;
- semicolons and why they are rarely needed;
- Python's execution from top to bottom.

---

## 1.2 Output, Comments, Strings, and Basic Syntax

Topics:

- `print()`;
- comments with `#`;
- string literals;
- single quotes;
- double quotes;
- triple single quotes;
- triple double quotes;
- multiline strings;
- docstrings;
- escape sequences;
- raw strings;
- string concatenation;
- basic string methods;
- f-strings.

Important distinctions:

- `'...'` vs `"..."`;
- `'''...'''` vs `"""..."""`;
- triple-quoted strings vs comments;
- comments vs docstrings;
- `\n`;
- `\t`;
- `\\`;
- escaped quotes;
- `r"..."`;
- empty strings;
- whitespace inside strings.

---

## 1.3 Variables, Objects, and Data Types

Topics:

- variables;
- assignment;
- naming rules;
- naming conventions;
- dynamic typing;
- integers;
- floats;
- strings;
- booleans;
- `None`;
- checking types with `type()`;
- type conversion.

Deeper concepts:

- variables as names bound to objects;
- reassignment;
- object identity;
- `id()`;
- mutable vs immutable objects;
- why Python variables are not boxes in the strict sense;
- multiple assignment;
- chained assignment;
- swapping values;
- constants by convention.

---

## 1.4 Numbers and Operators

Topics:

- arithmetic operators;
- precedence;
- parentheses;
- integer division;
- modulo;
- exponentiation;
- augmented assignment;
- numeric conversion;
- rounding.

Subtle concepts:

- `/` vs `//`;
- `%`;
- floating-point precision;
- negative floor division;
- operator precedence;
- readable expressions vs clever expressions.

---

## 1.5 Input and Basic Programs

Topics:

- `input()`;
- converting input;
- storing user input;
- combining input and output;
- basic validation;
- simple interactive programs.

Mini-projects may include:

- calculators;
- converters;
- bill splitters;
- simple financial calculations;
- text-based utilities.

---

## 1.6 Booleans and Conditional Logic

Topics:

- comparison operators;
- `if`;
- `elif`;
- `else`;
- nested conditions;
- logical operators;
- membership operators;
- identity operators.

Subtle concepts:

- truthy and falsy values;
- `==` vs `is`;
- `!=` vs `is not`;
- short-circuit evaluation;
- chained comparisons;
- `None` comparisons;
- conditional expressions.

---

## 1.7 Collections

### Lists

- creation;
- indexing;
- negative indexing;
- slicing;
- mutation;
- common methods;
- nested lists.

### Tuples

- creation;
- immutability;
- tuple packing;
- unpacking;
- single-item tuples.

### Sets

- uniqueness;
- membership;
- set operations;
- common methods.

### Dictionaries

- keys and values;
- access;
- mutation;
- dictionary methods;
- iteration;
- nested structures.

Subtle concepts:

- mutable vs immutable collections;
- references and aliasing;
- copying;
- shallow copies;
- hashability;
- dictionary key requirements;
- ordered dictionaries in modern Python;
- slicing syntax;
- `[::-1]`;
- unpacking collections.

---

## 1.8 Loops and Iteration

Topics:

- `for`;
- `while`;
- `range()`;
- iteration over collections;
- nested loops;
- `break`;
- `continue`;
- `pass`;
- loop `else`;
- `enumerate()`;
- `zip()`.

Deeper concepts:

- iterable vs iterator;
- avoiding unnecessary index-based loops;
- infinite loops;
- sentinel-controlled loops.

---

## 1.9 Functions

Topics:

- defining functions;
- calling functions;
- parameters;
- arguments;
- return values;
- default parameters;
- keyword arguments;
- positional arguments;
- scope;
- local and global names.

Subtle concepts:

- `return` vs `print`;
- functions as objects;
- `None` as an implicit return value;
- positional-only and keyword-only concepts;
- `*args`;
- `**kwargs`;
- argument unpacking with `*`;
- dictionary unpacking with `**`;
- mutable default argument trap;
- LEGB scope;
- `global`;
- `nonlocal`.

---

## 1.10 Errors and Exceptions

Topics:

- syntax errors;
- runtime errors;
- logical errors;
- exceptions;
- `try`;
- `except`;
- `else`;
- `finally`;
- `raise`;
- common built-in exceptions.

Skills:

- reading tracebacks;
- identifying the actual failing line;
- catching specific exceptions;
- avoiding overly broad exception handling.

---

## 1.11 Files and Modules

Topics:

- opening files;
- reading;
- writing;
- appending;
- file paths;
- `with`;
- context managers;
- modules;
- imports;
- standard library;
- creating reusable modules.

Subtle concepts:

- relative vs absolute paths;
- `__name__`;
- `__main__`;
- `if __name__ == "__main__":`;
- import execution;
- module namespaces.

---

## Module 1 Outcome

By the end of Module 1 I should be able to write small Python programs from a blank file without depending heavily on references.

The module should finish with several mini-projects and at least one larger foundations project.

---

# Module 2 — Intermediate Python

Topics include:

- list, dictionary, and set comprehensions;
- nested comprehensions;
- unpacking;
- advanced function usage;
- lambda expressions;
- higher-order functions;
- `map()`;
- `filter()`;
- iterables;
- iterators;
- generators;
- `yield`;
- decorators;
- closures;
- context managers;
- JSON;
- CSV;
- dates and times;
- regular expressions;
- useful standard-library modules;
- packages;
- virtual environments;
- dependency installation;
- modern Python project tooling.

Subtle concepts include:

- lazy evaluation;
- iterator exhaustion;
- generator expressions;
- closures and captured state;
- decorator syntax;
- copying vs referencing;
- shallow vs deep copy;
- Pythonic iteration patterns.

---
# Module 3 — Data Structures, Algorithms, and Problem Solving

This module develops algorithmic thinking, problem-solving ability, and the computer-science foundations needed for stronger software engineering and technical interviews.

The objective is not to memorize solutions or grind coding challenges.

The objective is to understand how data is organized, how algorithms operate on it, how to reason about efficiency, and how to communicate solutions clearly.

## Algorithmic Thinking

Topics:

- what an algorithm is;
- breaking problems into steps;
- inputs and outputs;
- constraints;
- edge cases;
- brute-force solutions;
- improving a working solution;
- correctness;
- readability vs optimization;
- reasoning before coding.

## Complexity and Big-O

Topics:

- time complexity;
- space complexity;
- Big-O notation;
- constant time — `O(1)`;
- linear time — `O(n)`;
- logarithmic time — `O(log n)`;
- linearithmic time — `O(n log n)`;
- quadratic time — `O(n²)`;
- exponential growth;
- best, average, and worst-case thinking;
- recognizing nested-loop complexity;
- practical performance vs theoretical complexity.

Python-specific examples should be used to understand the costs of common operations.

## Core Data Structures

Topics:

- arrays and Python lists;
- tuples;
- hash tables and Python dictionaries;
- sets;
- stacks;
- queues;
- `collections.deque`;
- linked lists;
- choosing an appropriate data structure.

Deeper concepts:

- lookup;
- insertion;
- deletion;
- traversal;
- memory trade-offs;
- hash functions;
- collisions;
- why dictionary and set lookups are typically fast;
- list vs deque performance;
- Python abstractions vs underlying data-structure concepts.

## Searching

Topics:

- linear search;
- binary search;
- search requirements;
- sorted vs unsorted data;
- complexity comparison;
- implementing searches from scratch;
- when built-in Python functionality is preferable in production.

## Sorting

Topics:

- what sorting algorithms solve;
- comparison-based sorting;
- stability;
- in-place vs copied sorting;
- Bubble Sort;
- Selection Sort;
- Insertion Sort;
- Merge Sort;
- Quick Sort concepts;
- Python `sorted()`;
- `.sort()`;
- sorting with `key`;
- sorting complexity;
- why production code normally uses optimized built-in sorting rather than hand-written algorithms.

The objective of implementing classic algorithms is understanding, not replacing Python's built-in tools.

## Recursion

Topics:

- recursive thinking;
- base cases;
- recursive cases;
- call stack;
- stack overflow / recursion limits;
- recursion vs iteration;
- appropriate and inappropriate uses of recursion.

## Trees

Topics:

- hierarchical data;
- nodes;
- roots;
- parents;
- children;
- leaves;
- binary trees;
- binary search trees;
- traversal;
- depth-first traversal;
- breadth-first traversal;
- practical examples of tree structures.

## Graph Fundamentals

Topics:

- vertices/nodes;
- edges;
- directed vs undirected graphs;
- weighted vs unweighted graphs;
- adjacency lists;
- adjacency matrices;
- Breadth-First Search;
- Depth-First Search;
- visited sets;
- practical graph use cases.

Graph study at this stage should focus on engineering fundamentals rather than advanced competitive-programming algorithms.

## Common Problem-Solving Patterns

Patterns include:

- frequency counting;
- hash-map lookup;
- two pointers;
- sliding window;
- prefix-style accumulation;
- sorting before processing;
- divide and conquer;
- recursion;
- traversal;
- BFS;
- DFS.

The emphasis should be recognizing when a pattern simplifies a problem rather than memorizing templates.

## Python Performance Awareness

Topics:

- complexity of common list operations;
- dictionary lookup;
- set membership;
- tuple characteristics;
- `deque`;
- string operations;
- copying collections;
- sorting;
- generators and memory;
- unnecessary loops;
- choosing appropriate built-in data structures.

## Problem-Solving Practice

Exercises should gradually include:

- short coding problems;
- debugging broken algorithms;
- improving inefficient solutions;
- identifying edge cases;
- comparing multiple solutions;
- explaining complexity;
- writing solutions without AI assistance;
- explaining code aloud;
- live-coding style exercises.

Difficulty should increase progressively rather than jumping immediately into advanced interview puzzles.

## Interview Application

Throughout the module, practice should include:

- understanding a problem before coding;
- asking or identifying constraints;
- describing a proposed solution;
- implementing it cleanly;
- testing examples and edge cases;
- analyzing time and space complexity;
- discussing alternative solutions;
- responding to follow-up modifications.

The purpose is to make technical interview problem-solving a natural extension of engineering knowledge rather than a separate memorization exercise.

## Module 3 Outcome

By the end of this module I should be able to:

- select appropriate common data structures;
- reason about algorithm efficiency;
- understand and implement foundational algorithms;
- solve progressively challenging programming problems;
- explain the reasoning behind a solution;
- recognize common problem-solving patterns;
- discuss time and space complexity;
- perform foundational technical-interview coding tasks with confidence.

---

# Module 4 — Object-Oriented and Modern Python

Topics:

- classes;
- objects;
- attributes;
- methods;
- constructors;
- `self`;
- instance attributes;
- class attributes;
- instance methods;
- class methods;
- static methods;
- inheritance;
- composition;
- encapsulation;
- abstraction;
- polymorphism;
- properties;
- dataclasses;
- enums;
- type hints;
- generics;
- protocols where appropriate.

Python data model concepts:

- dunder methods;
- `__init__`;
- `__repr__`;
- `__str__`;
- `__len__`;
- `__eq__`;
- operator behaviour;
- object representation.

Design emphasis:

- composition vs inheritance;
- separation of responsibilities;
- avoiding unnecessary classes;
- modelling real application domains.

The module concludes with an OOP-focused project.

---

# Module 5 — Professional Python Development

Topics:

- professional project structure;
- virtual environments;
- dependency management;
- `pip`;
- `pyproject.toml`;
- environment variables;
- configuration;
- `.gitignore`;
- debugging;
- logging;
- assertions;
- testing;
- pytest;
- fixtures;
- parametrization;
- mocking fundamentals;
- formatting;
- linting;
- type checking;
- documentation;
- Git workflows;
- refactoring;
- clean-code principles.

The objective is to transition from writing scripts to maintaining software projects.

---

# Module 6 — Web and API Foundations

Topics:

- internet and web fundamentals;
- client/server architecture;
- HTTP;
- HTTPS;
- URLs;
- DNS overview;
- requests and responses;
- HTTP methods;
- headers;
- bodies;
- status codes;
- JSON;
- REST;
- resources;
- endpoints;
- path parameters;
- query parameters;
- cookies;
- sessions;
- tokens;
- API versioning;
- idempotency;
- pagination;
- filtering;
- API documentation;
- basic networking concepts.

Python practice:

- consuming APIs;
- making HTTP requests;
- processing JSON;
- handling external API failures.

The objective is to understand web APIs independently of FastAPI.

---

# Module 7 — FastAPI Application Development

Topics:

- FastAPI fundamentals;
- application creation;
- development server;
- path operations;
- routing;
- path parameters;
- query parameters;
- request bodies;
- Pydantic models;
- validation;
- response models;
- status codes;
- exceptions;
- dependency injection;
- `Depends`;
- `APIRouter`;
- middleware;
- application configuration;
- file uploads;
- pagination;
- filtering;
- OpenAPI;
- Swagger UI;
- API documentation.

Architecture progression:

Simple application → Routers → Services → Repositories → Application layers

Projects become increasingly independent and production-oriented.

---

# Module 8 — PostgreSQL and Persistence

Topics:

- relational database concepts;
- SQL refresh;
- PostgreSQL;
- schemas;
- tables;
- primary keys;
- foreign keys;
- constraints;
- relationships;
- normalization;
- indexes;
- joins;
- transactions;
- database modelling;
- SQLAlchemy 2.x;
- ORM concepts;
- sessions;
- models;
- relationships;
- querying;
- repositories;
- Alembic;
- migrations;
- database testing.

Important engineering concepts:

- ORM vs SQL;
- N+1 queries;
- transaction boundaries;
- connection management;
- database constraints vs application validation;
- performance implications of indexes.

---

# Module 9 — Authentication, Security, and Testing

Topics:

- authentication;
- authorization;
- password hashing;
- salts;
- JWT;
- access tokens;
- refresh-token concepts;
- OAuth2 concepts;
- roles;
- permissions;
- FastAPI security dependencies;
- CORS;
- input validation;
- secrets management;
- rate limiting;
- common API vulnerabilities;
- OWASP concepts.

Testing:

- unit testing;
- integration testing;
- API testing;
- database testing;
- pytest;
- HTTP clients;
- fixtures;
- mocks;
- test isolation.

The module concludes with a production-style authenticated API.

---

# Module 10 — Advanced Backend Engineering

Topics:

- synchronous vs asynchronous programming;
- concurrency;
- `async`;
- `await`;
- coroutines;
- event loops;
- blocking vs non-blocking I/O;
- background tasks;
- Redis;
- caching;
- cache invalidation;
- queues;
- workers;
- scheduled jobs;
- retries;
- idempotency;
- WebSockets;
- Server-Sent Events;
- external integrations;
- webhooks;
- notifications;
- logging;
- monitoring;
- observability;
- performance;
- Docker;
- CI/CD.

The objective is to understand how production backend systems perform work beyond ordinary request-response APIs.

---

# Module 11 — Architecture, Scale, AI, and Production

Topics:

- application architecture;
- service layers;
- repository patterns;
- modular monoliths;
- microservices;
- when not to use microservices;
- system design;
- requirements analysis;
- capacity estimation;
- scalability;
- reliability;
- availability;
- fault tolerance;
- horizontal vs vertical scaling;
- load balancing;
- database scaling concepts;
- caching architecture;
- queues and asynchronous architecture;
- deployment;
- production configuration;
- security review;
- observability;
- AI service integration;
- LLM APIs;
- streaming AI responses;
- background AI tasks;
- responsible AI-assisted development.

GetHome may increasingly become an application environment for advanced architectural exercises and capstone work.

---

# Relationship With AltSchool

The two learning tracks remain distinct.

## AltSchool AI-Powered Full-Stack Journey

Primary ecosystem:

HTML → CSS → JavaScript → TypeScript → React → Node.js → Express.js → MongoDB → SQL/ORMs → NestJS → Full-Stack Engineering

Follow the AltSchool curriculum as prescribed.

## Python & FastAPI Engineering Journey

Primary ecosystem:

Python → FastAPI → PostgreSQL → SQLAlchemy → Redis → Production Backend Engineering

Follow this curriculum independently.

When both tracks encounter concepts such as:

- programming fundamentals;
- OOP;
- asynchronous programming;
- HTTP;
- REST;
- authentication;
- databases;
- testing;
- caching;
- queues;
- WebSockets;
- security;
- system design;
- AI integration;

compare implementations to strengthen language-independent understanding.

The Python course does not need to wait for AltSchool to introduce a concept.

AltSchool lessons do not need to be converted into Python lessons.

---

# Session Structure

A typical learning session may contain:

1. recap of previous knowledge;
2. concept explanation;
3. subtle syntax or semantic details;
4. short demonstrations;
5. prediction or recall questions;
6. guided exercises;
7. independent coding challenge;
8. code review;
9. refactoring;
10. mini-project work where appropriate;
11. Git commit when meaningful.

Not every session needs every stage.

---

# Exercise Rules

When a problem is within my current ability:

- attempt it before receiving the complete solution;
- use errors and tracebacks as learning tools;
- ask for hints before full solutions where practical;
- explain my reasoning when useful;
- review working code for improvements after solving it.

AI-generated code should not replace deliberate practice.

---

# Project Progression

Projects should progress approximately through:

Tiny scripts  
↓  
CLI programs  
↓  
Multi-file Python applications  
↓  
Object-oriented applications  
↓  
Programs consuming external APIs  
↓  
FastAPI services  
↓  
Database-backed APIs  
↓  
Authenticated/tested APIs  
↓  
Asynchronous and distributed backend features  
↓  
Production-style systems  
↓  
GetHome/capstone architecture

Projects should be new where possible rather than simply reproducing previous coursework.

---

# Workload and Pace

This course runs alongside AltSchool.

The default principle is consistency rather than rigid daily quotas.

Beginner concepts may progress rapidly because they are primarily refreshers.

More time should be spent where:

- recall is weak;
- implementation ability is weak;
- concepts are genuinely new;
- backend engineering depth is valuable;
- projects expose gaps.

The course is not required to last exactly 100 days.

The 100-Days-of-Code influence is the habit of frequent coding and project building, not an arbitrary deadline.

---

# Knowledge-Gap Policy

Do not assume that a concept is too small to revisit.

Include subtle Python concepts when relevant, especially those that are frequently used but easily misunderstood.

Examples include:

- quote styles;
- triple-quoted strings;
- comments vs docstrings;
- escape sequences;
- raw strings;
- indentation;
- `None`;
- truthiness;
- `==` vs `is`;
- mutability;
- object references;
- copying;
- slicing;
- unpacking;
- `*` and `**`;
- scope;
- implicit returns;
- mutable default arguments;
- iterables vs iterators;
- generators;
- dunder names;
- `__name__`;
- `__main__`;
- imports and namespaces;
- context managers;
- decorators;
- typing behaviour;
- synchronous vs asynchronous execution.

The objective is to remove accumulated gaps rather than merely reach advanced topics quickly.

---

# End Goal

By the end of the journey I should be comfortable with:

Programming:
Python

Backend:
FastAPI + REST APIs + asynchronous Python

Data:
PostgreSQL + SQL + SQLAlchemy + Alembic + Redis

Testing:
pytest + unit/integration/API testing

Infrastructure:
Git + GitHub + Docker + CI/CD

Engineering:
Architecture + Security + Performance + Observability + System Design

AI:
AI-assisted development + AI API integration

Combined with the AltSchool curriculum, the broader skill set should include:

Frontend:
HTML + CSS + JavaScript + TypeScript + React

Backend:
Python + FastAPI + Node.js + Express.js + NestJS

Databases:
PostgreSQL + MongoDB + Redis

The ultimate objective is not simply knowing frameworks.

It is being able to design, build, test, understand, debug, secure, and evolve useful software systems across both the Python and JavaScript/TypeScript ecosystems.