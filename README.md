<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Amer%20Elrouby&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Full-stack%20Engineer%20%C2%B7%20Java%20%2F%20Spring%20Boot%20%C2%B7%20Angular%20%C2%B7%20React&descAlignY=58&descSize=18" width="100%" alt="Amer Elrouby" />

<div align="center">

<a href="https://github.com/amer-rouby">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3500&pause=900&color=36BCF7&center=true&vCenter=true&width=720&lines=Modular+monoliths+with+enforced+module+boundaries;Hexagonal+%2F+Clean+architecture+%C2%B7+DDD+building+blocks;Spring+Boot+APIs+%2B+Angular+%26+Next.js+front+ends;Multi-tenant+SaaS+%C2%B7+POS+%C2%B7+E-commerce+%C2%B7+Marketplaces" alt="Typing SVG" />
</a>

</div>

### 👋 About me

I'm a full-stack engineer who designs and ships **business systems end to end** — retail & POS platforms, multi-tenant SaaS, e-commerce and service marketplaces — with **Spring Boot** on the backend and **Angular** or **React / Next.js** on the front end.

What I care about most: **clear module boundaries, a domain model that matches the business, and code that stays easy to change.**

### 🧱 How I build

- **Modular monolith first** — feature modules with enforced boundaries (Spring Modulith, module-boundary tests, Maven multi-module), ready to split into services without a rewrite.
- **Hexagonal / Clean architecture** — `domain` → `application` → `infrastructure`, with external APIs (AI, payments, messaging) behind ports.
- **DDD building blocks** — aggregate roots, state machines for lifecycles, domain events between modules, dedicated read models.
- **Correct under concurrency** — idempotency keys, conditional stock reservation, optimistic locking.
- **Schema as code & real tests** — Flyway migrations, Testcontainers on PostgreSQL, CI on every push.
- **Frontend architecture** — Angular `core / shared / features` with lazy routes and signals; Next.js with feature folders, BFF auth (httpOnly cookie) and config-driven admin screens.

### ⭐ Featured projects

| Project | Architecture & highlights | Stack |
|---|---|---|
| **[Research Office Platform](https://github.com/amer-rouby/research-office-backend)**<br/>[backend](https://github.com/amer-rouby/research-office-backend) · [web](https://github.com/amer-rouby/research-office-web) | Modular monolith (identity, catalog, orders, experts, payments, messaging, AI) with module-boundary tests, Flyway, Testcontainers, versioned releases | Spring Boot 4.1 · Java 21 · Angular 22 · Tailwind 4 |
| **[Bayaa — WhatsApp Sales Bot](https://github.com/amer-rouby/whatsapp-sales-bot)** | Hexagonal (domain / application / infrastructure) + Spring Modulith, AI provider behind a port, webhook signature verification, CI | Spring Boot 4 · Next.js · PostgreSQL · Docker |
| **[VIRONAI Store](https://github.com/amer-rouby/vironai-store)** | Package-by-feature monolith, `Product` aggregate, order state machine, oversell-proof stock reservation, idempotent checkout, BFF auth | Spring Boot 4.1 · Next.js 16 · TanStack Query · Flyway |
| **[Rawaj Retail Platform](https://github.com/amer-rouby/rawaj-backend)**<br/>[backend](https://github.com/amer-rouby/rawaj-backend) · [web](https://github.com/amer-rouby/rawaj-frontend) | 14-module Maven modular monolith, multi-tenant, domain events, one core shipped as several business variants, offline-first POS | Spring Boot · Angular 22 · PostgreSQL |
| **[SmartPharma](https://github.com/amer-rouby/smartpharma-backend)**<br/>[backend](https://github.com/amer-rouby/smartpharma-backend) · [web](https://github.com/amer-rouby/smartpharma-frontend) · [mobile](https://github.com/amer-rouby/smartpharma-mobile) | Multi-tenant pharmacy management — the platform Rawaj grew from | Spring Boot · Angular · Capacitor |

### 🛠 Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,spring,hibernate,maven,postgres,angular,react,nextjs,ts,tailwind,docker,githubactions,git&perline=13" alt="Tech stack" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Modulith-6DB33F?style=flat-square&logo=spring&logoColor=white" />
  <img src="https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white" />
  <img src="https://img.shields.io/badge/JUnit_5-25A162?style=flat-square&logo=junit5&logoColor=white" />
  <img src="https://img.shields.io/badge/Testcontainers-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/RxJS-B7178C?style=flat-square&logo=reactivex&logoColor=white" />
  <img src="https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white" />
</p>

### 🐍 Contribution activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/amer-rouby/amer-rouby/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/amer-rouby/amer-rouby/output/github-contribution-grid-snake.svg" />
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/amer-rouby/amer-rouby/output/github-contribution-grid-snake.svg" />
</picture>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=110&section=footer" width="100%" alt="" />
