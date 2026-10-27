<h1 align="center">Hi 👋, I'm Sanjay</h1>
<h3 align="center">Software Engineer with 2.5+ years building scalable, distributed systems in production, spanning microservices, event-driven pipelines, and AI-powered features</h3>

<p align="left">
  <img src="https://komarev.com/ghpvc/?username=sanjaym-2002&label=Profile%20views&color=0e75b6&style=flat" alt="sanjaym-2002" />
</p>

- 💼 Currently **SDE-2 at Swivl**, designing backend microservices, payment systems, third-party integrations, and event-driven architectures
- 📫 Reach me at **sanjaym2202@gmail.com**

<br />

<h2 align="left">💼 Experience</h2>

**Swivl** · Bangalore

*SDE-2 (Backend)* · Dec 2025 – Present
- Developed and scaled **REST APIs** in **NestJS** and **Go** for a **field-service management platform** serving **10,000+ businesses**, spanning work orders, CRM, scheduling, media, and billing
- Designed a **provider-agnostic payment layer** integrating **Stripe** and **Paysafe** for connected accounts, checkout sessions, transfers, and **credit-based billing**, migrating live tenants behind **gated API versioning** with **zero downtime**
- Developed a **GPS tracking service** ingesting locations via **AWS IoT Core** and **SQS**, with a **geofence state machine**, **Kalman-filter** smoothing, trails stored in **S3**, and live updates streamed via **Kinesis**, **Redis pub/sub**, and **WebSockets**

*SDE-1 (Backend)* · Sept 2024 – Nov 2025
- Built an **event-driven communication microservice** turning domain events into notification intents, scheduled via **AWS EventBridge** and dispatched across **email**, **SMS**, and **push**, delivering **300K+ notifications** monthly
- Engineered a **media pipeline** using **FFmpeg, Sharp, SQS, Lambda**, and **S3** for asynchronous **image compression**, **thumbnail variants**, and **HLS transcoding** (**240p–1080p**), reducing payload size by **85%**
- Built a **FastAPI-based AI Estimate agent** using **LangGraph** and **gRPC-based tool calls** to generate estimates through guided conversations, reducing token usage from **1M+ to 10K** per workflow and estimate creation time by **70%**
- Architected a dedicated **AI Receptionist microservice** using **Twilio** and **Retell AI**, covering number provisioning, call forwarding, transfer routing, and post-call processing, capturing **80% of inbound leads**
- Built a **bidirectional QuickBooks integration** that synced accounting data both ways and eliminated manual data entry

**CryptoPool** · Remote

*Full Stack Developer Intern* · July 2024 – Sept 2024
- Implemented **REST APIs** for **admin operations** and **merchant account management**, supporting **500+ merchants** and reducing manual intervention through streamlined workflows
- Built a **Merchant Dashboard** in **Next.js** giving clients an intuitive interface to manage their transactions and track payment activity
- Created an **Admin Dashboard** in **React.js** for internal use, enabling efficient tracking and management of merchant details and transaction records
- Integrated **multiple payment providers** with **retry-safe, idempotent webhook handlers**, and built a **notification service** delivering **real-time transaction updates** via **email** and **in-app (Pusher)** channels

**Alts Wealth** · Bangalore

*Software Developer Intern* · July 2023 – Dec 2023
- Built **React Native** and **React** frontends for a **Digital Will platform** and a **Portfolio Review app**, covering asset, beneficiary, and financial-planning workflows
- Developed **backend services** and **REST APIs** using **Python**, **Flask**, **MongoDB**, and **S3**, handling user data and document management workflows across applications

<br />

<h2 align="left">🚀 Featured Projects</h2>

| Project | What it is | Stack |
|---|---|---|
| **[LiteCode](https://github.com/SanjayM-2002/litecode)** | LeetCode-style coding judge. Submissions are graded asynchronously by an **in-house Go judge** that runs untrusted code inside `isolate` (namespaces + cgroup v2), with batched test-case execution. Also has premium AI hints/roasts and Razorpay subscriptions driven by idempotent webhooks | NestJS · GraphQL · Go · RabbitMQ · PostgreSQL · Prisma · Redis · React 19 · Turborepo |
| **[Meet Random](https://github.com/SanjayM-2002/meet-random)** | Omegle-style random video chat. A Socket.IO server pairs strangers from a matchmaking queue into rooms and relays WebRTC offer/answer signaling between them | TypeScript · Socket.IO · WebRTC · React · Node.js |
| **[Invoice & Payment Service](https://github.com/SanjayM-2002/invoice-payment-service)** | Billing backend covering invoices, payments through a mock PSP, an invoice state machine, signed webhooks with retries/backoff, and hashed API keys | Rust · Axum · SQLx · PostgreSQL · Docker |

<br />

<h2 align="left">🧪 Built From Scratch (Experiments & Deep Dives)</h2>

Side projects where I rebuild core systems myself to understand how they work.

| Project | What I built | Concepts |
|---|---|---|
| **[prismo](https://github.com/SanjayM-2002/prismo)** | A **Prisma-inspired ORM for Go**. It parses a `.prisma`-style schema, diffs it against MySQL (`db push` with data-loss protection) and generates a type-safe Go client | Parsers · schema diffing · code generation |
| **[chess-engine](https://github.com/SanjayM-2002/chess-engine)** | A thread-safe chess engine with full rules (castling, en passant, pins), validated with perft. Adds an alpha-beta AI, a multiplayer lobby, live spectators and a TCP server. Standard library only | Move generation · alpha-beta search · concurrency (`-race` tested) |
| **[probabloom](https://github.com/SanjayM-2002/probabloom)** | **Bloom filters** from first principles for "is this username taken?" checks. Implements different strategies (standard, counting, partitioned, cache-line blocked, scalable) with multiple hashing algorithms (FNV-1a, xxHash64, MurmurHash3), and supports both in-memory and Redis (RedisBloom) storage | Probabilistic data structures · hashing · cache locality |
| **[chat-filter](https://github.com/SanjayM-2002/chat-filter)** | Real-time **profanity filter for chat streams** built on a **trie**. Catches leetspeak (`$h1t`) and separator tricks (`s.h.i.t`), and serves streams over a WebSocket hub | Tries · text normalization · WebSockets |
| **[gredis](https://github.com/SanjayM-2002/gredis)** | A **Redis-compatible in-memory key-value store** written from first principles (work in progress). Has a **RESP** protocol parser with pipelining, a single-threaded event loop on **epoll** (Linux) / **kqueue** (macOS), core commands (`GET`, `SET`, `DEL`, `INCR`, `EXPIRE`, `TTL`), `MULTI`/`EXEC` transactions, sampled active expiry, approximated-LRU and random eviction, and **AOF** persistence | Event loops · I/O multiplexing · RESP · eviction · persistence |
| **[reverse-proxy-scratch](https://github.com/SanjayM-2002/reverse-proxy-scratch)** | Reverse proxies built from scratch: an **L4 TCP load balancer** (round robin, weighted RR, least connections) and a **database router** that routes each command, either splitting reads and writes across a primary and replicas or sharding keys with modulo or consistent hashing | Networking · load balancing · sharding · consistent hashing |
| **[trydb](https://github.com/SanjayM-2002/trydb)** | A tiny **trie-based key-value database** stored in a single custom binary file. Writes are **copy-on-write** (unchanged subtrees are shared) and commit with an atomic root-pointer swap over two CRC-checked meta slots, so it survives crashes without a write-ahead log. Supports put, get, delete and prefix scan | Storage engines · copy-on-write · crash safety · binary file formats |

<br />

<h2 align="left">🎓 Education</h2>

- **B.E. (Hons.)**, **BITS Pilani** · Nov 2020 – May 2024

<br />

<h2 align="left">🏆 Achievements</h2>

- **Best Performer of the Quarter** at **Swivl** (Q2 2026) for building the payment and billing infrastructure
- **Knight** at LeetCode (contest rating 2018, top 2.3%), with Global Ranks **95**, **550** and **706** in Biweekly Contests
- **Specialist** at Codeforces (rating 1437)

<br />

<h2 align="left">🤝 Connect with me</h2>
<p align="left">
  <a href="https://www.linkedin.com/in/sanjay-m-74a123240/" target="_blank" rel="noreferrer">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="40" />
  </a>

  <a href="mailto:sanjaym2202@gmail.com">
    <img align="center" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/google/google-original.svg" alt="Email" height="30" width="40" />
  </a>
</p>

<br />

<h2 align="left">🛠️ Skills</h2>

| Category | Tools |
|---|---|
| **Languages** | <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="C++" title="C++" width="40" height="40" /> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java" title="Java" width="40" height="40" /> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" title="JavaScript" width="40" height="40" /> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="TypeScript" title="TypeScript" width="40" height="40" /> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original-wordmark.svg" alt="Go" title="Go" width="40" height="40" /> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" title="Python" width="40" height="40" /> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5" title="HTML5" width="40" height="40" /> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3" title="CSS3" width="40" height="40" /> |
| **Backend** | <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="Node.js" title="Node.js" width="40" height="40" /> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nestjs/nestjs-original.svg" alt="NestJS" title="NestJS" width="40" height="40" /> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="Express" title="Express" width="40" height="40" /> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/prisma/prisma-original.svg" alt="Prisma" title="Prisma" width="40" height="40" /> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/spring/spring-original.svg" alt="Spring Boot" title="Spring Boot" width="40" height="40" /> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flask/flask-original.svg" alt="Flask" title="Flask" width="40" height="40" /> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" alt="FastAPI" title="FastAPI" width="40" height="40" /> |
| **Frontend** | <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="React" title="React" width="40" height="40" /> <img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" alt="Next.js" title="Next.js" width="40" height="40" /> <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="Tailwind" title="Tailwind" width="40" height="40" /> <img src="https://img.shields.io/badge/React%20Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React Native" /> |
| **Databases** | <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL" title="MySQL" width="40" height="40" /> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="MongoDB" title="MongoDB" width="40" height="40" /> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="PostgreSQL" title="PostgreSQL" width="40" height="40" /> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original-wordmark.svg" alt="Redis" title="Redis" width="40" height="40" /> |
| **APIs & Messaging** | <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/graphql/graphql-plain.svg" alt="GraphQL" title="GraphQL" width="40" height="40" /> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/grpc/grpc-original.svg" alt="gRPC" title="gRPC" width="40" height="40" /> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/apachekafka/apachekafka-original.svg" alt="Kafka" title="Kafka" width="40" height="40" /> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rabbitmq/rabbitmq-original.svg" alt="RabbitMQ" title="RabbitMQ" width="40" height="40" /> <img src="https://img.shields.io/badge/BullMQ-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="BullMQ" /> |
| **Cloud & DevOps** | <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="AWS" title="AWS" width="40" height="40" /> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="Docker" title="Docker" width="40" height="40" /> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/kubernetes/kubernetes-original.svg" alt="Kubernetes" title="Kubernetes" width="40" height="40" /> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" alt="Nginx" title="Nginx" width="40" height="40" /> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jenkins/jenkins-original.svg" alt="Jenkins" title="Jenkins" width="40" height="40" /> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/github/github-original.svg" alt="GitHub" title="GitHub" width="40" height="40" /> |
| **Monitoring & Testing** | <img src="https://www.vectorlogo.zone/logos/jestjsio/jestjsio-icon.svg" alt="Jest" title="Jest" width="40" height="40" /> <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="Postman" title="Postman" width="40" height="40" /> <img src="https://img.shields.io/badge/Datadog-632CA6?style=for-the-badge&logo=datadog&logoColor=white" alt="Datadog" /> <img src="https://img.shields.io/badge/PostHog-000000?style=for-the-badge&logo=posthog&logoColor=white" alt="PostHog" /> |
| **AI / LLM** | <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain" /> <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangGraph" /> <img src="https://img.shields.io/badge/Anthropic-191919?style=for-the-badge&logo=anthropic&logoColor=white" alt="Anthropic" /> |

<br />

<h2 align="left">📊 Stats</h2>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sanjaym-2002&layout=compact&langs_count=10&theme=dracula" alt="Top languages" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com/?user=sanjaym-2002&theme=dracula" alt="GitHub streak" />
</p>
