# Hi there, I'm Sang Le! 👋
  ### Software Engineering

  I am a software engineer with **over 6 years of hands-on experience** crafting responsive, high-performance web applications.
  I enjoy tackling creative challenges, writing clean/maintainable code, and optimizing user experiences.

  🎯 Currently a **Software Engineer** growing toward **Application Security Engineering** — deepening my systems and security foundations (memory safety, exploitation primitives, network protocols).

  ---

  ### 🛠️  Tech Stack

  **Languages**
  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
  ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
  ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
  ![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)

  **Frontend**
  ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
  ![Redux](https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white)
  ![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
  ![React Query](https://img.shields.io/badge/React_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white)
  ![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)

  **Backend & Frameworks**
  ![NodeJS](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
  ![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
  ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)

  **Databases & ORM**
  ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
  ![MySQL](https://img.shields.io/badge/MySQL-000000?style=for-the-badge&logo=mysql&logoColor=white)
  ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
  ![Redis](https://img.shields.io/badge/Redis-DD0031?style=for-the-badge&logo=redis&logoColor=white)
  ![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)
  ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)

  **Messaging & DevOps**
  ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
  ![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)
  ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
  ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
  ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

  ---

  ### 🔭 Experience & Projects

  **Featured Personal Projects:**

  * 🛡️ **CS:APP Visualizer** — [Live](https://jonathn1001.github.io/csapp-visualizer/) · An **Application Security–focused** interactive learning engine for Computer Systems (CS:APP).
    * Pure-TypeScript simulation engine (unit-tested against the book's worked examples) with a React replay UI; every concept renders as a step-by-step state trace.
    * AppSec modules: stack smashing & buffer overflow → control-flow hijack, stack canaries (`-fstack-protector`), NX + ASLR, signed/integer overflow → heap overflow, address translation, and race conditions.
    * *Stack:* TypeScript · React · Vite · Vitest · TailwindCSS

  * 🌐 **NetViz** — [Live](https://jonathn1001.github.io/netviz/) · An interactive sandbox for Computer Networking (Kurose & Ross, top-down).
    * Each protocol is a deterministic, discrete-event state machine replayed packet-by-packet — a wrong engine sends the packet the wrong way and a test fails.
    * Covers Ch. 1–6 with a Trace Mode composing the layers (TCP `cwnd`/loss recovery, Dijkstra routing, DNS, sockets).
    * *Stack:* TypeScript · React · Vite · Vitest · Zustand · Framer Motion · TailwindCSS

  * 🗄️ **DDIA Visualized** — [Live](https://jonathn1001.github.io/ddia-visualized/) · An interactive lab for *Designing Data-Intensive Applications* — all 12 chapters as simulations you can break.
    * Pure-TypeScript discrete-event engine (seeded RNG, virtual clock, snapshot/replay) fully separated from a React UI; every protocol is a hand-written pure reducer, property-tested with fast-check (e.g. Raft never elects two leaders in one term).
    * 19 labs across all 12 chapters — LSM/B-tree storage, replication, consistent-hashing partitioning, isolation anomalies, an unreliable-network + fencing playground, a 5-node Raft + linearizability checker, MapReduce-vs-dataflow, Kafka/RabbitMQ/Redis brokers, an unbundled-database CDC pipeline — each with 2–3 engine-verified chaos challenges (produce a stale read, cause a split-brain, lose an acked write).
    * *Stack:* TypeScript · React · Vite · Vitest · fast-check · Zustand · Framer Motion · TailwindCSS

  * 🛒 **E-Commerce Backend API** — A robust and scalable e-commerce backend covering the full purchase lifecycle.
    * User auth (JWT), product catalog, shopping cart, discount engine, order management, inventory tracking, nested comments, and real-time notifications.
    * File uploads to **Cloudinary** and **AWS S3**; async processing via **RabbitMQ** and **Kafka**.
    * *Stack:* Node.js · Express · MongoDB · Redis · RabbitMQ · Kafka

  * 🎟️  **NestJS Ticketing Backend API** — A ticketing system backend with structured logging and multi-database support.
    * Modules: users, tickets, orders, stock management.
    * *Stack:* NestJS · TypeORM · MySQL · PostgreSQL · Winston

  * 🔍 **Product Search Service** — A product microservice with full-text search and event-driven sync.
    * Prisma ORM for MySQL persistence; Elasticsearch for search indexing; RabbitMQ for async data synchronization.
    * *Stack:* NestJS · Prisma · MySQL · Elasticsearch · RabbitMQ

  * 🤖 **Telegram Intel Bot** — A passive channel monitor with on-demand AI-powered intelligence analysis.
    * Dual Telegram identity: Telethon (MTProto) for channel reading, aiogram for bot commands.
    * Commands: `/summary`, `/trends`, `/entities`, `/threat` — powered by **Google Gemini 1.5 Pro**.
    * *Stack:* Python · Telethon · aiogram · Gemini API · Docker

  * 🛍️  **TryBuy.com** — A full-stack e-commerce application with a modern React frontend and Node.js backend.
    * *Stack:* React · React Hook Form · Framer Motion · Node.js

  ---

  ### 🌱 Current Learning Focus
  * **🎯 Career Goal — Application Security Engineer:** transitioning from backend engineering into AppSec.
  * **Application Security:** OWASP Top 10, memory safety & binary exploitation fundamentals (CS:APP), secure-by-design review.
  * **Advanced Backend Architecture:** System design, NestJS patterns, and microservices.
  * **Education:** Pursuing a degree in Information Technology at PTIT (Posts and Telecommunications Institute of Technology).

  ---

  ### 📫 Connect with Me
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/robert-le-a93268210)
  [![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sangle1001.dev@gmail.com)
