# Daanial Mirza — Master Engineering Learning Roadmap

This learning curriculum is tailored directly to the architecture, algorithms, frameworks, and engineering concepts used across Daanial's active software engineering portfolio.

---

## Level 1 — Core Computer Science & Language Fundamentals
- **Data Structures**:
  - Directed Acyclic Graphs (DAGs), Adjacency Lists, Topological Sorting (Kahn's Algorithm, DFS).
  - Priority Queues & Heaps (`heapq`), Hash Maps, Sets, Circular Buffers.
- **Algorithmic Complexity**:
  - Big-O Time & Space Analysis, Graph Traversal ($O(V+E)$), Branch-and-Bound, Pareto Frontier Pruning.
- **Languages & Typing**:
  - **Python 3.12**: Type hints, Pydantic v2 validation, generators, async/await with `anyio`/`asyncio`.
  - **TypeScript 5.x**: Strict mode, generic constraints, discriminated unions, template literal types.
  - **Kotlin**: Coroutines, StateFlow, Android Architecture Components.

---

## Level 2 — Application Engineering & Architecture
- **Full-Stack Frameworks**:
  - **FastAPI**: Dependency injection (`Depends`), Pydantic settings, custom middlewares, APIRouters.
  - **Next.js 14/15**: App Router, Server Actions, React Server Components (RSC), SSR/SSG boundaries.
- **Relational Databases & ORMs**:
  - **SQLAlchemy 2.0 & Prisma ORM**: Foreign key constraints, cascade rules, index optimization, migrations.
  - **Ledger Invariants**: Double-entry bookkeeping balance equations, ACID transaction isolation.
- **Testing & Quality Assurance**:
  - `pytest` (fixtures, parameterized testing, coverage), `vitest` (fast unit tests), `playwright` (cross-browser E2E testing).

---

## Level 3 — Systems, Concurrency & Resilient Architecture
- **Offline-First & Data Synchronization**:
  - Conflict-Free Replicated Data Types (CRDTs), Version Vectors, IndexedDB local mutation queues.
  - Multi-attribute Last-Write-Wins (LWW) with domain-specific merge semantics (clinical/financial data).
- **Concurrency & Locking**:
  - Database Row-Level Locking (`SELECT FOR UPDATE`), optimistic locking with version columns, distributed mutexes.
- **Real-Time Communication**:
  - WebSockets, Socket.io, Firebase Realtime listeners, event-driven message architectures.
- **Geospatial & Physics Systems**:
  - PostGIS spatial indexing (GIST R-trees), surface thermodynamic energy balance equations, geospatial GeoJSON processing.

---

## Level 4 — Production AI & Agentic Engineering
- **Deterministic vs. Probabilistic Boundaries**:
  - Isolating deterministic calculation engines (scoring, pricing, safety rules) from LLM reasoning layers.
- **Multi-Agent Systems**:
  - **LangGraph**: StateGraph, cyclical agent routing, conditional edges, recursion depth limits.
  - **10-Agent Cyclical Pipeline**: Query planner, parallel searcher, extractor, fact-checker, writer, citation validator, reviewer.
- **Advanced Retrieval-Augmented Generation (RAG)**:
  - Hybrid Search: Reciprocal Rank Fusion (RRF) combining dense vector embeddings with sparse BM25.
  - Neural Cross-Encoder Reranking (`ms-marco-MiniLM`), semantic chunking with overlap buffers.
  - Multi-tenant vector isolation and IR benchmark metrics (MRR@10, NDCG@5).
- **On-Device Agent Runtimes**:
  - Android Accessibility perception layers, UI hierarchy tree traversal, deterministic 8-point constraint safety engines.

---

## Level 5 — System Design & Interview Mastery
- **30-Second / 2-Minute / 5-Minute Technical Pitches** across all 5 Flagship systems.
- **Failure Mode Defense**: LLM outage fallbacks, network partition handling in offline healthcare apps, battery degradation in microgrid optimization, race condition defense in venue booking.
- **Scaling Strategies**: In-memory graph snapshotting, Redis caching layers, asynchronous task offloading via Celery/Redis queues.
