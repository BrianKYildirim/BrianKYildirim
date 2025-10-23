# Hi, I’m Brian Yildirim

**Computer Science (Information Specialization @ UC Irvine (’27)** · **Backend & Distributed Systems** · **Pragmatic builder of fast, reliable services**

I like turning messy real-world problems into clean, testable systems. My happy place is the intersection of **high-performance backends**, **microservices**, and **developer-friendly tooling**.

- **Current focus:** production-ready microservices, distributed rate limiting, observability with OpenTelemetry, and resilient AWS deployments.
- **Interests:** token-bucket algorithms, concurrency & sharding, networking protocols, and system design that scales.
- **Goal:** ship useful OSS, write clear docs, and keep latency low.
- **Open to:** Summer 2026 Software Engineering Intern roles.

---

## Selected Projects

> Full write-ups live on my portfolio → **[brianyildirim.vercel.app](https://brianyildirim.vercel.app/)**

| Project | What it does | Tech | Links |
|---|---|---|---|
| **Rate Limiter Library (C++20)** | A tiny, fast library implementing a **sharded token-bucket** with clean **C++ and C interfaces** and first-class **CMake** packaging. Designed for **low-overhead**, predictable throughput under contention. | C++20, atomics, CMake, unit tests, benchmarks | Portfolio: [/projects/rate-limiter](https://brianyildirim.vercel.app/projects/rate-limiter) |
| **Multi-Threaded TCP Key-Value Server** | Persistent KV store with a **custom text protocol**, request parsing, and multi-client concurrency. Built for learning sockets, framing, and back-pressure. | Python, sockets, threading, persistence | Portfolio: [/projects/tcp-server](https://brianyildirim.vercel.app/projects/tcp-server) |
| **Image Quality Gate** | **Microservice** that auto-rejects blurry/low-quality images (e.g., before upload pipelines) using sharpness/blur detection metrics. | Python, NumPy, image processing, REST | Portfolio: [/projects/image-quality-gate](https://brianyildirim.vercel.app/projects/image-quality-gate) |
| **Personal Portfolio** | My site with projects, notes, and résumé. Lightweight, fast, and deploys cleanly. | Next.js, TypeScript, Tailwind, Vercel | [Homepage](https://brianyildirim.vercel.app/), [Résumé (PDF)](https://brianyildirim.vercel.app/resume.pdf) |

---

## Stack & Tools

**Languages:** `C++20` · `Python` · `TypeScript` · `JavaScript`

**Frontend:** `React` · `Next.js` · `TailwindCSS`  

**Data:** `PostgreSQL` · `Redis (ElastiCache)`

**DevOps:** `Docker` · `Kubernetes` · `GitHub Actions`  

**Security & Auth:** `Auth0` (JWKS caching, short-lived ATs, RT rotation)  

**Observability:** `OpenTelemetry` (traces/metrics/logs), p95/p99-first mindset  

**Testing & Perf:** unit + property-based tests · benchmarks · load testing

---

## Engineering Philosophy

- **Simplicity > cleverness.** Fewer moving parts win—especially under pressure.
- **Measure, then optimize.** Benchmarks and traces drive changes; p95 budgets keep us honest.
- **APIs as contracts.** Clear interfaces, crisp failure modes, and strong docs.
- **Automate the boring stuff.** CI/CD, style checks, and reproducible builds by default.
- **Write things down.** READMEs and examples are part of the product.

---

## What to Explore

- **Rate Limiter internals:** sharding strategy, fairness trade-offs, and atomic paths.  
- **TCP server protocol:** request framing, concurrency model, and persistence format.  
- **Image quality heuristics:** sharpness metrics, thresholds, and false-positive handling.

---

## Contact

- **Website:** [brianyildirim.vercel.app](https://brianyildirim.vercel.app/contact)  
- **Résumé:** [brianyildirim.vercel.app/resume.pdf](https://brianyildirim.vercel.app/resume.pdf)
