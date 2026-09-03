# Hi, I'm Divyaraj

CS undergrad at VIT Vellore ('27), into backend and infra.

## What I've built

**[EventPulse](https://github.com/divyaraj24/EventPulse)** — a webhook
delivery pipeline deliberately subjected to controlled chaos, to measure
exactly when retry stops helping and starts sustaining the outage it was
meant to fix. Implements RetryGuard (Tavori et al., 2025) as a real adaptive
retry policy: under a 90s throttled-recovery fault, adaptive fires 89% fewer
retries than naive backoff (366 vs. 3231) and resolves 100% of events vs.
53% still unresolved under naive. Numbers and raw CSVs for this run are
committed in the repo.

**LLM API Gateway** — weighted routing across multiple LLM providers with
per-provider circuit breakers (Closed/Open/Half-Open) and atomic
Redis-Lua rate limiting. Pushing this to GitHub soon.

**OrgLens** — scores GitHub repos for bus factor and ownership drift: who'd
hurt a project most by leaving, and whether anyone's positioned to take
over. Currently rebuilding it in Spring Boot.

## Stack

Python (FastAPI), Java (Spring Boot), Redis, PostgreSQL, Docker

## Right now

Working through DSA (NeetCode + Codeforces contests), rebuilding OrgLens,
open to backend/distributed-systems roles off-campus.

## Elsewhere

[Portfolio](https://divyaraj24.in) · [LinkedIn](https://www.linkedin.com/in/divyaraj24/) · divyarajdeepak2356@gmail.com
