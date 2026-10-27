<h1 align="center">Hi 👋, I'm Sanjay</h1>
<h3 align="center">Software Engineer with 2.5+ years building scalable, distributed systems in production, spanning microservices, event-driven pipelines, and AI-powered features</h3>

<p align="left">
  <img src="https://komarev.com/ghpvc/?username=sanjaym-2002&label=Profile%20views&color=0e75b6&style=flat" alt="sanjaym-2002" />
</p>

- 💼 Currently **SDE-2 at Swivl**, designing backend microservices, payment systems, third-party integrations, and event-driven architectures
- 🎓 B.E. (Hons.), **BITS Pilani**
- 🏆 LeetCode **Knight** (rating 2018, top 2.3%)
- 📫 Reach me at **sanjaym2202@gmail.com**

<h3 align="left">🚀 Featured Projects:</h3>

| Project | What it is | Stack |
|---|---|---|
| **[LiteCode](https://github.com/SanjayM-2002/litecode)** | LeetCode-style coding judge. Submissions are graded asynchronously by an **in-house Go judge** that runs untrusted code inside `isolate` (namespaces + cgroup v2), with batched test-case execution. Also has premium AI hints/roasts and Razorpay subscriptions driven by idempotent webhooks | NestJS · GraphQL · Go · RabbitMQ · PostgreSQL · Prisma · Redis · React 19 · Turborepo |
| **[Meet Random](https://github.com/SanjayM-2002/meet-random)** | Omegle-style random video chat. A Socket.IO server pairs strangers from a matchmaking queue into rooms and relays WebRTC offer/answer signaling between them | TypeScript · Socket.IO · WebRTC · React · Node.js |
| **[Invoice & Payment Service](https://github.com/SanjayM-2002/invoice-payment-service)** | Billing backend covering invoices, payments through a mock PSP, an invoice state machine, signed webhooks with retries/backoff, and hashed API keys | Rust · Axum · SQLx · PostgreSQL · Docker |

<h3 align="left">🧪 Built From Scratch (Experiments & Deep Dives):</h3>

Side projects where I rebuild core systems myself to understand how they work.

| Project | What I built | Concepts |
|---|---|---|
| **[prismo](https://github.com/SanjayM-2002/prismo)** | A **Prisma-inspired ORM for Go**. It parses a `.prisma`-style schema, diffs it against MySQL (`db push` with data-loss protection) and generates a type-safe Go client | Parsers · schema diffing · code generation |
| **[chess-engine](https://github.com/SanjayM-2002/chess-engine)** | A thread-safe chess engine with full rules (castling, en passant, pins), validated with perft. Adds an alpha-beta AI, a multiplayer lobby, live spectators and a TCP server. Standard library only | Move generation · alpha-beta search · concurrency (`-race` tested) |
| **[probabloom](https://github.com/SanjayM-2002/probabloom)** | **Bloom filters** from first principles for "is this username taken?" checks. Implements different strategies (standard, counting, partitioned, cache-line blocked, scalable) with multiple hashing algorithms (FNV-1a, xxHash64, MurmurHash3), and supports both in-memory and Redis (RedisBloom) storage | Probabilistic data structures · hashing · cache locality |
| **[chat-filter](https://github.com/SanjayM-2002/chat-filter)** | Real-time **profanity filter for chat streams** built on a **trie**. Catches leetspeak (`$h1t`) and separator tricks (`s.h.i.t`), and serves streams over a WebSocket hub | Tries · text normalization · WebSockets |
| **[reverse-proxy-scratch](https://github.com/SanjayM-2002/reverse-proxy-scratch)** | Reverse proxies built from scratch: an **L4 TCP load balancer** (round robin, weighted RR, least connections) and a **database router** that routes each command, either splitting reads and writes across a primary and replicas or sharding keys with modulo or consistent hashing | Networking · load balancing · sharding · consistent hashing |
| **[trydb](https://github.com/SanjayM-2002/trydb)** | A tiny **trie-based key-value database** stored in a single custom binary file. Writes are **copy-on-write** (unchanged subtrees are shared) and commit with an atomic root-pointer swap over two CRC-checked meta slots, so it survives crashes without a write-ahead log. Supports put, get, delete and prefix scan | Storage engines · copy-on-write · crash safety · binary file formats |

<h3 align="left">Connect with me:</h3>
<p align="left">
  <a href="https://www.linkedin.com/in/sanjay-m-74a123240/" target="_blank" rel="noreferrer">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="40" />
  </a>

  <a href="mailto:sanjaym2202@gmail.com">
    <img align="center" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/google/google-original.svg" alt="Email" height="30" width="40" />
  </a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="center">
  <!-- Languages -->
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="C++" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="TypeScript" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original-wordmark.svg" alt="Go" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3" width="40" height="40" />
  <br />
  <!-- Backend -->
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="Node.js" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nestjs/nestjs-original.svg" alt="NestJS" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="Express" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/prisma/prisma-original.svg" alt="Prisma" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/spring/spring-original.svg" alt="Spring Boot" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flask/flask-original.svg" alt="Flask" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" alt="FastAPI" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/graphql/graphql-plain.svg" alt="GraphQL" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/grpc/grpc-original.svg" alt="gRPC" width="40" height="40" />
  <br />
  <!-- Frontend -->
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="React" width="40" height="40" />
  <img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" alt="Next.js" width="40" height="40" />
  <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="Tailwind" width="40" height="40" />
  <br />
  <!-- Databases -->
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="MongoDB" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="PostgreSQL" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original-wordmark.svg" alt="Redis" width="40" height="40" />
  <br />
  <!-- Messaging, Cloud & DevOps -->
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/apachekafka/apachekafka-original.svg" alt="Kafka" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rabbitmq/rabbitmq-original.svg" alt="RabbitMQ" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="AWS" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="Docker" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/kubernetes/kubernetes-original.svg" alt="Kubernetes" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" alt="Nginx" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jenkins/jenkins-original.svg" alt="Jenkins" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/github/github-original.svg" alt="GitHub" width="40" height="40" />
  <br />
  <!-- Testing -->
  <img src="https://www.vectorlogo.zone/logos/jestjsio/jestjsio-icon.svg" alt="Jest" width="40" height="40" />
  <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="Postman" width="40" height="40" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React%20Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React Native" />
  <img src="https://img.shields.io/badge/BullMQ-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="BullMQ" />
  <img src="https://img.shields.io/badge/Datadog-632CA6?style=for-the-badge&logo=datadog&logoColor=white" alt="Datadog" />
  <img src="https://img.shields.io/badge/PostHog-000000?style=for-the-badge&logo=posthog&logoColor=white" alt="PostHog" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangGraph" />
  <img src="https://img.shields.io/badge/Anthropic-191919?style=for-the-badge&logo=anthropic&logoColor=white" alt="Anthropic" />
</p>

<h3 align="left">Stats:</h3>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sanjaym-2002&layout=compact&langs_count=10&theme=dracula" alt="Top languages" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com/?user=sanjaym-2002&theme=dracula" alt="GitHub streak" />
</p>
