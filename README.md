<div align="center">

<img width="100%" alt="Diego Arias — Full-Stack Developer" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,20&height=220&section=header&text=Diego%20Arias&fontSize=64&fontColor=fff&animation=twinkling&fontAlignY=38&desc=Full-Stack%20Developer%20·%20.NET%20·%20Laravel%20·%20Next.js&descAlignY=58&descSize=18"/>

<a href="https://www.linkedin.com/in/diego-arias-654426250/">
  <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="mailto:ariasdiego570@gmail.com">
  <img alt="Email" src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<img alt="Location" src="https://img.shields.io/badge/Neiva,%20Colombia-1a1a2e?style=for-the-badge&logo=googlemaps&logoColor=white"/>
<img alt="Open to work" src="https://img.shields.io/badge/Open%20to-Remote%20%26%20Relocation-00C853?style=for-the-badge&logo=github&logoColor=white"/>

</div>

---

## Hi, I'm Diego 👋

I'm 20, based in Neiva, Colombia, and I'm the **sole developer** behind a five-module platform running in production at **ElectroHuila S.A. E.S.P.**, a regional power utility. Database schema, backend, frontend, CI/CD pipeline, tests — all of it.

What that has taught me, in short:

- **Enterprise .NET at scale** — Clean Architecture + CQRS on ASP.NET Core, with Oracle, SQL Server, PostgreSQL and MySQL wired into a single application through EF Core.
- **Shipping, not just building** — Jenkins pipelines, Docker Compose, three environments, and E2E coverage with Cypress and Playwright, because "works on my machine" doesn't help the people using it.
- **Applied AI** — I built a full ChatGPT-style platform on my own time: hybrid RAG over pgvector, four LLM providers, Stripe billing, Langfuse observability.

I like problems where the hard part is the system design, not the syntax.

<table>
<tr><td><b>Role</b></td><td>Application Developer @ ElectroHuila S.A. E.S.P.</td></tr>
<tr><td><b>Education</b></td><td>ADSO — SENA (2024–2025)</td></tr>
<tr><td><b>Certification</b></td><td>Claude Code in Action — Anthropic (2026)</td></tr>
<tr><td><b>Languages</b></td><td>Spanish (native) · English (technical)</td></tr>
<tr><td><b>Looking for</b></td><td>Backend / full-stack roles — remote or relocation</td></tr>
</table>

---

## 🚀 What I've built

### 🏭 PQR-Agenda — enterprise multi-module platform

> **In production** at ElectroHuila S.A. E.S.P. · Built solo, from architecture to deployment
> *Private repository — happy to walk through the architecture or share a code sample on request.*

Five modules serving internal staff and utility customers:

| Module | What it does |
| --- | --- |
| 📅 **PQR Scheduling** | Appointment booking with interactive calendar, QR check-in, Excel export, admin panel, and Gmail + WhatsApp notifications |
| 🏢 **Corporate Intranet** | Single portal for 30+ internal apps, organized by department, with SSO |
| 📄 **Actas** | Automatic PDF and document generation, installable as a PWA |
| 📊 **KPI Dashboard** | Live reliability and revenue indicators (SAIDI, SAIFI) rendered with Recharts |
| 🗺️ **ServiCampo** | Field-operations management with KML mapping |

**Architecture** — Clean Architecture + CQRS · ASP.NET Core 10 (C# 13) + Laravel 12 (PHP 8.2) · real-time updates over SignalR
**Data** — Oracle 19c · SQL Server · PostgreSQL · MySQL, unified through Entity Framework
**DevOps** — Jenkins declarative pipeline · Docker Compose · Dev / QA / Production
**Testing** — Vitest · Cypress · Playwright · Pest PHP

<img alt="Stack" src="https://skillicons.dev/icons?i=cs,dotnet,php,laravel,react,nextjs,ts,tailwind,docker,jenkins&theme=dark"/>

---

### 🤖 Electro IA — AI chat platform

> **Personal project** · A ChatGPT-style product built end to end: RAG, multimodal input, subscriptions

**AI layer**
- Hybrid retrieval — pgvector HNSW similarity (72%) + lexical matching (25%) + recency boost (3%), over PDFs, plain text and GitHub repos
- Four providers behind the Vercel AI SDK: Claude, GPT, Gemini, and local Ollama
- Intent routing across 11 categories, with a math short-circuit, automatic web search via Tavily, and context-window trimming
- OCR through Tesseract.js, multimodal messages, streamed responses

**Platform layer**
- Clerk auth with webhook sync · Stripe Free/Pro tiers · token metering with a 30-day reset
- Upstash Redis rate limiting · Langfuse + Sentry for observability
- Turborepo: Next.js 15 · Hono edge API · Drizzle ORM · Neon PostgreSQL

<img alt="Stack" src="https://skillicons.dev/icons?i=nextjs,react,ts,tailwind,postgres,vercel&theme=dark"/>

`pgvector` · `Hono` · `Drizzle` · `Vercel AI SDK` · `Stripe` · `Clerk` · `Langfuse` · `Sentry` · `Upstash` · `Turborepo`

---

<!--
### 🔧 Project name
> One line on what it is and who it's for

Two or three sentences: the problem, the interesting technical decision, the outcome.

**Stack:** ...
[Live demo](#) · [Code](#)

---
-->

## 🛠️ Stack

**Backend** — C# / .NET · PHP / Laravel · Python · REST APIs · SignalR
**Frontend** — React · Next.js · TypeScript · Tailwind CSS
**Data** — Oracle · SQL Server · PostgreSQL · MySQL · pgvector · Entity Framework · Drizzle
**Infra** — Docker · Jenkins · AWS · Nginx · Linux
**Testing** — Vitest · Cypress · Playwright · Pest

<img alt="Backend and cloud" src="https://skillicons.dev/icons?i=cs,dotnet,php,laravel,python,aws,docker,nginx,linux,jenkins&theme=dark&perline=10"/>
<img alt="Frontend and tooling" src="https://skillicons.dev/icons?i=react,nextjs,ts,js,tailwind,postgres,mysql,git,github,vscode&theme=dark&perline=10"/>

---

## 📊 GitHub

<div align="center">

<img height="150" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=DiegoArias32&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=667eea&icon_color=667eea&text_color=ffffff&count_private=true&include_all_commits=true&border_radius=10"/>
<img height="150" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DiegoArias32&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=667eea&text_color=ffffff&langs_count=6&hide=html,css&border_radius=10"/>

</div>

> Most of my production work lives in private and company repositories, so the graph below doesn't tell the whole story. Ask me about the architecture instead — I'd rather talk through a design decision than a commit count.

---

<div align="center">

### Let's talk

I'm open to backend and full-stack roles, remote or with relocation.

<a href="https://www.linkedin.com/in/diego-arias-654426250/">
  <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="mailto:ariasdiego570@gmail.com">
  <img alt="Email" src="https://img.shields.io/badge/ariasdiego570@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,20&height=120&section=footer"/>

</div>
