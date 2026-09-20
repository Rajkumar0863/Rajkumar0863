# Rajkumar Vijayan

**Graduate Software Engineer | C++ · Java · Systems · Game Development**  
MSc Software Development (International Systems), University of Limerick — graduating May 2027

[Email](mailto:vijayanrajkumar478@gmail.com) · [LinkedIn](https://www.linkedin.com/in/rajkumar-vijayan-0135a8338/) · Based in Limerick, Ireland

I build software where correctness, performance and clear rules matter. My recent work includes a multithreaded C++ scheduler, a price-time-priority matching engine and an Unreal Engine combat prototype in development. I am interested in graduate engineering roles involving C++, gameplay systems, real-time software and performance-focused development.

---

## Engineering highlights

### [InferX](https://github.com/Rajkumar0863/inferx) — C++20 inference scheduler

**Status:** Complete · **Focus:** concurrency, scheduling and performance measurement

InferX simulates an AI inference-serving path and makes scheduling behaviour measurable rather than opaque.

- Implemented FIFO and priority scheduling with stable ordering for equal-priority requests.
- Added configurable dynamic batching using batch-size and timeout triggers.
- Built a concurrent worker pool and thread-safe queue with `std::thread`, mutexes, condition variables and atomics.
- Instrumented mean, p50, p95 and p99 latency, throughput and batch occupancy.
- Verified scheduling, batching and metrics behaviour with eight passing GoogleTest/CTest cases.

`C++20` · `Concurrency` · `Algorithms` · `CMake` · `GoogleTest` · `Performance Metrics`

### [TradeMatchExchange](https://github.com/Rajkumar0863/TradeMatchExchange) — Java matching engine

**Status:** Complete · **Focus:** data structures, deterministic matching and object-oriented design

TradeMatchExchange models how an electronic exchange prioritises and executes orders.

- Implemented max-heap buy books and min-heap sell books using `PriorityQueue` and custom comparators.
- Applied price-time priority, partial-fill processing and deterministic execution logic.
- Separated order management, matching, trade history, risk validation and market statistics.
- Added CSV trade export and measures including volume, price range, average price and VWAP.

`Java` · `PriorityQueue` · `Heaps` · `Data Structures` · `OOP` · `JUnit 5` · `Maven`

### Arcane Arena — Unreal Engine turn-based combat prototype

**Status:** In progress · **Focus:** C++ gameplay architecture and Unreal Engine workflows

Arcane Arena is a focused prototype for learning production-style gameplay programming.

- Developing Fighter, Mage and Rogue classes with distinct abilities and reusable combat behaviour.
- Designing health, enemy-encounter and turn-sequencing systems as modular gameplay components.
- Using C++ for core rules and Blueprints for presentation and user-interface feedback.
- Structuring the combat loop so new abilities and enemy behaviours can be added without rewriting its core.

`Unreal Engine 5` · `C++` · `Blueprints` · `OOP` · `Gameplay Systems`

---

## Core stack

| Area | Technologies |
|---|---|
| Programming | C++20, Java, Python, C#, SQL, JavaScript |
| Computer science | Data structures, algorithms, OOP, design patterns, concurrency |
| Quality and performance | Debugging, optimisation, latency measurement, automated testing |
| Testing and build | GoogleTest, CTest, CMake, JUnit, Mockito, MockMvc, Maven |
| Backend and data | Spring Boot, REST APIs, JPA, PostgreSQL, Pandas, NumPy |
| Engineering tools | Git, GitHub Actions, Linux, Docker, Google Cloud Run, AWS |

## How I work

- Break systems into components with clear responsibilities and interfaces.
- Test behaviour at boundaries, including ordering, timeouts, invalid input and state transitions.
- Measure performance with useful metrics rather than relying on assumptions.
- Document design decisions, build steps and limitations so another engineer can reproduce the work.

---

## Other selected projects

- **[GradTrack](https://github.com/Rajkumar0863/gradtrack)** — Spring Boot and PostgreSQL application with validation, automated tests and GitHub Actions CI.
- **[ConsultLab](https://github.com/Rajkumar0863/consultlab)** — process-mining study using 1.2 million events from the BPI Challenge 2017 dataset.
- **[CRM Sales Pipeline Analysis](https://github.com/Rajkumar0863/crm-sales-pipeline-analysis)** — SQL, Python and Tableau analysis across 8,800 sales opportunities.
- **[Retail Customer Growth](https://github.com/Rajkumar0863/retail-customer-growth)** — Python and Power BI analysis of more than 700,000 retail transactions.

---

## Experience

### Amazon Development Centre — ML Data Associate
*Chennai, India · February 2022 – January 2023*

- Curated and validated more than 100,000 records for machine-learning training pipelines while meeting daily accuracy and throughput targets.
- Investigated recurring error patterns and proposed workflow improvements adopted by the team, contributing to a reported 30% productivity improvement.

### VRBB & Associates — Business Consulting Intern
*Sivakasi, India · May – July 2024*

- Gathered client requirements and documented processes, operating procedures and reporting needs.
- Converted open-ended discussions into clear requirements, decisions and follow-up actions.

---

## Education

- **MSc Software Development (International Systems)** — University of Limerick, 2025–2027
- **PGDM Business Analytics** — Thiagarajar School of Management, 2023–2025
- **BCA Data Science** — B.S. Abdur Rahman Crescent Institute of Science and Technology, 2017–2020

## Additional

- AWS Academy Cloud Foundations
- McKinsey Forward Program
- Entrepreneurship Cell Core Committee — managed 15–20 sponsor relationships for a national student festival with 1,000+ attendees

---

**Open to 2027 graduate software-engineering and game-engineering opportunities in Ireland.**
