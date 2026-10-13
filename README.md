# Brian Yildirim

Computer Science student at **UC Irvine** building backend systems and concurrent software — from a low-contention C++20 rate limiter to a full-stack SaaS with Stripe billing. I care about performance trade-offs, maintainable code, and software that holds up beyond the happy path.

**Currently seeking software engineering internships.**

[![Portfolio](https://img.shields.io/badge/Portfolio-brianyildirim.com-ECE9E4?logo=googlechrome&logoColor=ECE9E4&labelColor=0F1117)](https://brianyildirim.com)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-in/brianyildirim-ECE9E4?logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB3aWR0aD0nMjU2JyBoZWlnaHQ9JzI1NicgeG1sbnM9J2h0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnJyBwcmVzZXJ2ZUFzcGVjdFJhdGlvPSd4TWlkWU1pZCcgdmlld0JveD0nMCAwIDI1NiAyNTYnPjxwYXRoIGQ9J00yMTguMTIzIDIxOC4xMjdoLTM3LjkzMXYtNTkuNDAzYzAtMTQuMTY1LS4yNTMtMzIuNC0xOS43MjgtMzIuNC0xOS43NTYgMC0yMi43NzkgMTUuNDM0LTIyLjc3OSAzMS4zNjl2NjAuNDNoLTM3LjkzVjk1Ljk2N2gzNi40MTN2MTYuNjk0aC41MWEzOS45MDcgMzkuOTA3IDAgMCAxIDM1LjkyOC0xOS43MzNjMzguNDQ1IDAgNDUuNTMzIDI1LjI4OCA0NS41MzMgNTguMTg2bC0uMDE2IDY3LjAxM1pNNTYuOTU1IDc5LjI3Yy0xMi4xNTcuMDAyLTIyLjAxNC05Ljg1Mi0yMi4wMTYtMjIuMDA5LS4wMDItMTIuMTU3IDkuODUxLTIyLjAxNCAyMi4wMDgtMjIuMDE2IDEyLjE1Ny0uMDAzIDIyLjAxNCA5Ljg1MSAyMi4wMTYgMjIuMDA4QTIyLjAxMyAyMi4wMTMgMCAwIDEgNTYuOTU1IDc5LjI3bTE4Ljk2NiAxMzguODU4SDM3Ljk1Vjk1Ljk2N2gzNy45N3YxMjIuMTZaTTIzNy4wMzMuMDE4SDE4Ljg5QzguNTgtLjA5OC4xMjUgOC4xNjEtLjAwMSAxOC40NzF2MjE5LjA1M2MuMTIyIDEwLjMxNSA4LjU3NiAxOC41ODIgMTguODkgMTguNDc0aDIxOC4xNDRjMTAuMzM2LjEyOCAxOC44MjMtOC4xMzkgMTguOTY2LTE4LjQ3NFYxOC40NTRjLS4xNDctMTAuMzMtOC42MzUtMTguNTg4LTE4Ljk2Ni0xOC40NTMnIGZpbGw9JyNmZmYnLz48L3N2Zz4K&logoColor=ECE9E4&labelColor=0F1117)](https://linkedin.com/in/brianyildirim)

[![Resume](https://img.shields.io/badge/Resume-BrianYildirim.pdf-ECE9E4?logo=googledocs&logoColor=ECE9E4&labelColor=0F1117)](https://www.brianyildirim.com/static/Brian_Yildirim.pdf)

---

## Featured Projects

### StrivoAI
> **AI career platform**: A full-stack SaaS that helps job seekers sharpen resumes and navigate hiring via ATS scoring, job-description matching, LinkedIn feedback, and personalized recommendations, with payments handled through Stripe.
> 
> [Source Code](https://github.com/BrianKYildirim/strivoai) · [Live Demo](https://strivoai.net)
>
> ![TypeScript](https://img.shields.io/badge/TypeScript-0F1117?logo=typescript) ![React](https://img.shields.io/badge/React-0F1117?logo=react) ![Supabase](https://img.shields.io/badge/Supabase-0F1117?logo=supabase) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0F1117?logo=postgresql) ![Stripe](https://img.shields.io/badge/Stripe-0F1117?logo=stripe)

---

### Minecraft Enchantment Order
> **Enchantment cost optimizer**: Finds the cheapest order to combine enchantments on an anvil. Uses recursive search with memoization to minimize XP cost and prior-work penalties while respecting compatibility and anvil limits.
> 
> [Source Code](https://github.com/BrianKYildirim/minecraft-enchantment-order) · [Live Demo](https://minecraft-enchantment-order.vercel.app)
>
> ![Python](https://img.shields.io/badge/Python-0F1117?logo=python) ![Flask](https://img.shields.io/badge/Flask-0F1117?logo=flask) ![JavaScript](https://img.shields.io/badge/JavaScript-0F1117?logo=javascript)

---

### C++ Rate Limiter
> **High-performance C++20 rate limiter**: A sharded token-bucket rate limiter built to stay fast under heavy concurrent load. Fixed-point arithmetic and fine-grained locking keep contention low and latency predictable. Ships with C/C++ APIs, GoogleTest suites, Google Benchmark microbenchmarks, and reusable CMake packaging.
> 
> [Source Code](https://github.com/BrianKYildirim/ratelimit-cpp)
>
> ![C++](https://img.shields.io/badge/C++-0F1117?logo=c%2B%2B&logoColor=blue) ![CMake](https://img.shields.io/badge/CMake-0F1117?logo=cmake&logoColor=blue) ![GoogleTest](https://img.shields.io/badge/GoogleTest-0F1117?logo=google)

---

### Image Quality Gate
> **Image QA microservice**: A containerized REST API that rejects blurry or badly exposed images before they reach downstream pipelines using Laplacian variance and brightness analysis. Built for production with input validation, health checks, Prometheus metrics, and automated tests.
> 
> [Source Code](https://github.com/BrianKYildirim/image-quality-gate)
>
> ![Python](https://img.shields.io/badge/Python-0F1117?logo=python) ![FastAPI](https://img.shields.io/badge/FastAPI-0F1117?logo=fastapi) ![OpenCV](https://img.shields.io/badge/OpenCV-0F1117?logo=opencv&logoColor=blue) ![Docker](https://img.shields.io/badge/Docker-0F1117?logo=docker) ![Prometheus](https://img.shields.io/badge/Prometheus-0F1117?logo=prometheus)

---

### Concurrent Key-Value Server
> **Multithreaded TCP key-value server** — A persistent key-value store served over a custom TCP protocol. Handles many simultaneous clients with thread-safe operations and survives restarts through file-based persistence.
> 
> [Source Code](https://github.com/BrianKYildirim/key-value-storage)
>
> ![Python](https://img.shields.io/badge/Python-0F1117?logo=python)
