<div align="center">

# Diego Arias

**Full-Stack Developer** — enterprise systems, clean architecture, cloud deployments

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/diego-arias-654426250/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ariasdiego570@gmail.com)
[![Claude Code](https://img.shields.io/badge/Certified-Claude%20Code%20in%20Action-D97706?style=flat-square&logo=anthropic&logoColor=white)](https://www.anthropic.com)

*Neiva, Colombia · Open to remote & relocation worldwide*

</div>

---

I build production web systems end-to-end — from database schema to CI/CD pipeline. Currently the sole developer behind a 5-module enterprise platform running in production at a Colombian power utility, serving real users daily.

My stack spans **C# / .NET**, **Laravel**, **React / Next.js**, **TypeScript**, and **multi-database architectures**. I've shipped systems with Oracle + SQL Server + PostgreSQL + MySQL all connected in a single application, real-time SignalR updates, Jenkins CI/CD pipelines, and full E2E test coverage with Cypress and Playwright.

On the AI side, I built a full ChatGPT-like platform from scratch — hybrid RAG with pgvector, 4 LLM providers, Stripe billing, OCR, and LLM observability with Langfuse.

---

## What I've built

### 🏭 PQR-Agenda · Enterprise Platform · *Production @ ElectroHuila*

A multi-module internal system for Colombia's Huila region power utility. Built solo from architecture to deployment.

| Module | What it does |
|--------|-------------|
| **PQR Scheduling** | Appointment system with interactive calendar, QR verification, Excel export, admin panel |
| **Corporate Intranet** | Unified portal for 30+ internal apps, categorized by department, SSO |
| **Actas** | Automatic PDF/document generation, PWA |
| **KPI Dashboard** | Real-time indicators (SAIDI, SAIFI, revenue), Recharts |
| **ServiCampo** | Field operations with KML mapping |

**Architecture:** Clean Architecture + CQRS · ASP.NET Core 10 (C# 13) + Laravel 12 (PHP 8.2)
**Data:** Oracle 19c primary · SQL Server · PostgreSQL · MySQL — all in one app via Entity Framework
**Real-time:** SignalR · Gmail API · WhatsApp API
**DevOps:** Jenkins declarative pipeline · Docker Compose · Dev / QA / Production environments
**Testing:** Vitest · Cypress E2E · Playwright · Pest PHP
**Security:** JWT · role-based permissions per module · CORS · Zod validation · Polly retry policies

`C#` `ASP.NET Core 10` `Laravel 12` `Next.js 15` `React 19` `TypeScript` `Tailwind CSS` `Oracle` `SQL Server` `PostgreSQL` `MySQL` `Docker` `Jenkins` `SignalR` `Entity Framework` `Zod`

---

### 🤖 Electro IA · AI Chat Platform · *Personal project*

Full-stack ChatGPT-like platform with RAG, multimodal input, and subscription billing. Built as a Turbo monorepo.

**AI layer:**
- Hybrid RAG: vector similarity (pgvector HNSW 72%) + lexical (25%) + recency boost (3%) over PDFs, text, GitHub repos
- 4 LLM providers via Vercel AI SDK: Claude · GPT · Gemini · Ollama (Gemma 3 12B local)
- Intent detection across 11 categories — math short-circuit, auto web search (Tavily), joke/story memory
- OCR pipeline with Tesseract.js · multimodal messages · context window trimming

**Platform layer:**
- Auth: Clerk with webhook sync to PostgreSQL
- Billing: Stripe (Free/Pro plans) · webhooks · token metering · 30-day reset
- Rate limiting: Upstash Redis with sliding window
- Observability: Langfuse (LLM traces) · Sentry (errors)

**Stack:** Next.js 15 · React 19 · TypeScript · Hono edge API · Drizzle ORM · Neon PostgreSQL · Tailwind CSS · shadcn/ui · Turbo monorepo

`Next.js 15` `Hono` `Drizzle ORM` `pgvector` `Vercel AI SDK` `Anthropic` `OpenAI` `Gemini` `Ollama` `Stripe` `Clerk` `Langfuse` `Sentry` `Upstash` `Turbo`

---

## Stack

```
Backend      C# · ASP.NET Core · PHP · Laravel · Python · Entity Framework
             REST APIs · Microservices · SignalR · JWT · Polly

Frontend     React · Next.js · TypeScript · Tailwind CSS · Zustand · SWR
             Framer Motion · shadcn/ui · Recharts

Databases    Oracle · SQL Server · PostgreSQL · MySQL · pgvector
             Multi-database in single application

DevOps       Docker · Jenkins · AWS · CI/CD · Git
             Vitest · Cypress · Playwright · Pest PHP

AI           Vercel AI SDK · Claude · GPT · Gemini · Ollama
             RAG · pgvector · Langfuse · Sentry · Stripe · Clerk
```

---

## Experience

**Application Developer — ElectroHuila S.A. E.S.P.** · Jan 2026 – present
Sole developer on PQR-Agenda: designed architecture, implemented all 5 modules, configured CI/CD, deployed to production. Stack: ASP.NET Core 10 + Laravel 12 + Next.js 15 + Oracle + Jenkins + Docker.

---

## Education & Certifications

- **ADSO** — Software Analysis and Development · SENA · 2024–2025
- **Claude Code in Action** — Anthropic · Jan 2026 · `ID: tqfwgvj249nc`

---

<div align="center">

<img width="47%" src="https://github-readme-stats.vercel.app/api?username=DiegoArias32&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true&title_color=60a5fa&icon_color=60a5fa"/>
<img width="47%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DiegoArias32&layout=compact&theme=github_dark&hide_border=true&langs_count=8&title_color=60a5fa"/>

</div>

---

<div align="center">
<sub>Building things that run in production · ariasdiego570@gmail.com</sub>
</div>
