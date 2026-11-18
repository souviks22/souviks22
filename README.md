# Hi, I'm Souvik 👋

I'm a software engineer focused on **backend infrastructure, distributed systems, and reliable software**.

I enjoy building systems from first principles and understanding the trade-offs behind consistency, concurrency, fault tolerance, and performance. My work spans backend services, distributed coordination, storage engines, and AI infrastructure.

Currently working on AI platforms while building and maintaining systems-oriented projects in Go and Python.

## Selected Projects

### [Continuum](https://github.com/souviks22/continuum) · Distributed Key-Value Store

An embeddable Go key-value store built around Raft consensus and an in-memory MVCC state machine.

- Raft-based replication with durable logs, snapshots, and restart recovery
- MVCC, transactions, and linearizable reads
- Resumable watches, leases, and membership changes
- Embedded clients and separate-process TCP clients
- Optional TLS/mTLS for remote communication
- Stable v1 API with an intentionally scoped support contract

**Built with:** Go, Raft, Protocol Buffers, TCP, TLS/mTLS

### [Sluice](https://github.com/souviks22/sluice) · Distributed Rate Limiting

A FastAPI-first asynchronous rate-limiting library with Redis-backed atomic admission and explicit degradation behavior.

- Token Bucket, Sliding Window Log, and Sliding Window Counter
- Atomic weighted admission using Redis Lua scripts and Redis server time
- FastAPI route dependencies and optional pure-ASGI middleware
- Redis failure handling with circuit breaking and bounded local fallback
- Trusted-proxy-aware identity resolution and HMAC-based identifier pseudonymization
- Low-cardinality observability interfaces
- Unit, concurrency, Redis integration, and fault-injection tests

**Built with:** Python, FastAPI, asyncio, Redis, Lua, Pytest, Docker

## Technical Interests

- Distributed systems, consensus, and replication
- Database internals, storage engines, and transaction processing
- Concurrency, synchronization, and fault tolerance
- Backend architecture, networking, and performance engineering
- AI infrastructure, retrieval systems, and observability

## Technologies

**Languages:** Go, Python, C++, Java, SQL

**Backend & Infrastructure:** FastAPI, Spring Boot, REST APIs, Kafka, Redis, Docker, Linux, Git

**Systems & Data:** Raft, MVCC, TCP, Protocol Buffers, PostgreSQL, MySQL

**AI Infrastructure:** RAG, FAISS, semantic retrieval

## Problem Solving

Competitive programming has helped me develop strong algorithmic problem-solving skills. I enjoy tackling challenging problems and reasoning about correctness, complexity, and edge cases.

[Codeforces](https://codeforces.com/profile/souvikofculture) · [LeetCode](https://leetcode.com/u/souviksarkar2k3/)

## Connect

[LinkedIn](https://www.linkedin.com/in/souviks22/) · [GitHub](https://github.com/souviks22)

Always interested in discussing backend engineering, distributed systems, and interesting technical problems.
