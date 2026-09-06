<div align="center">

<img width="100%" alt="Diego Arias — Full-Stack Developer" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,20&height=220&section=header&text=Diego%20Arias&fontSize=64&fontColor=fff&animation=twinkling&fontAlignY=38&desc=Full-Stack%20Developer%20·%20.NET%20·%20Laravel%20·%20Next.js%20·%20Flutter&descAlignY=58&descSize=18"/>

<a href="https://www.linkedin.com/in/diego-arias-654426250/">
  <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="mailto:ariasdiego570@gmail.com">
  <img alt="Email" src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<img alt="Location" src="https://img.shields.io/badge/Neiva,%20Colombia-1a1a2e?style=for-the-badge&logo=googlemaps&logoColor=white"/>
<img alt="Available" src="https://img.shields.io/badge/Available-Remote%20%26%20Relocation-00C853?style=for-the-badge&logo=github&logoColor=white"/>

</div>

---

## Hi, I'm Diego 👋

I'm 20, based in Neiva, Colombia. Between January and July 2026 I built and maintained **six enterprise applications running in production** at **ElectroHuila S.A. E.S.P.**, a regional power utility — web and mobile, from database schema to CI/CD pipeline.

Three things that period taught me:

- **Legacy data is where the real work is.** I integrated new applications with Oracle 19c and external corporate systems (ERP, SIEC, payroll), and built a management dashboard that consolidates KPIs from five separate databases into one view.
- **Shipping is part of the job.** I ran Jenkins CI/CD pipelines and then led the migration to Coolify, giving QA and production automated deploys on `git push`.
- **Field constraints beat clean abstractions.** ServiCampo had to work offline in rural areas, so it syncs to Oracle when a signal comes back — not when the architecture diagram says it should.

On my own time I built a full ChatGPT-style platform: hybrid RAG over pgvector, four LLM providers, Stripe billing, LLM observability.

I like problems where the hard part is the system design, not the syntax.

<table>
<tr><td><b>Most recent</b></td><td>Software Developer @ ElectroHuila S.A. E.S.P. (Jan – Jul 2026)</td></tr>
<tr><td><b>Education</b></td><td>Tecnólogo en Análisis y Desarrollo de Software — SENA (2024 – 2026)</td></tr>
<tr><td><b>Certification</b></td><td>Claude Code in Action — Anthropic (2026)</td></tr>
<tr><td><b>Languages</b></td><td>Spanish (native) · English (intermediate)</td></tr>
<tr><td><b>Looking for</b></td><td>Backend / full-stack roles — remote or relocation</td></tr>
</table>

---

## 🚀 What I've built

### 🏭 ElectroHuila — six applications in production

> **Live systems** at a regional power utility · Built end to end, from schema to deploy
> *Private company repositories — happy to walk through the architecture or share a code sample on request.*

| Application | What it does |
| --- | --- |
| 📅 **PQR Scheduling** | Customer appointment booking with real-time notifications over WhatsApp, email and SignalR, plus QR-code check-in |
| 🗺️ **ServiCampo** | Offline-first Flutter app for managing electrical easements in the field — satellite maps, photo capture, automatic Oracle sync |
| 📊 **Indicadores Gerenciales** | Executive dashboard consolidating KPIs from five databases (commercial, technical, HR, quality, finance) |
| 📄 **Actas** | Automates contractual and pre-contractual paperwork, cutting document turnaround time |
| 🏢 **Corporate Intranet** | Portal launching 27+ internal applications, with news and integrated management system |

**Stack** — Laravel · .NET · Next.js · Flutter
**Data** — Oracle 19c, including queries against external systems (ERP, SIEC, payroll) · SQL Server · PostgreSQL · MySQL
**Security** — JWT authentication with role-based access control
**DevOps** — Jenkins pipelines, then led the migration to Coolify with `git push` deploys to QA and production

<img alt="Stack" src="https://skillicons.dev/icons?i=cs,dotnet,php,laravel,react,nextjs,flutter,ts,docker,jenkins&theme=dark"/>

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

**Backend** — C# / .NET · PHP / Laravel · Node.js · Java / Spring Boot · Python · REST APIs · SignalR
**Frontend** — React · Next.js · TypeScript · Tailwind CSS
**Mobile** — Flutter
**Data** — Oracle · SQL Server · PostgreSQL · MySQL · pgvector · Entity Framework · Drizzle
**Infra** — Docker · Jenkins · Coolify · Nginx · Linux · Git

<img alt="Backend" src="https://skillicons.dev/icons?i=cs,dotnet,php,laravel,java,spring,nodejs,python,flutter,dart&theme=dark&perline=10"/>
<img alt="Frontend and infra" src="https://skillicons.dev/icons?i=react,nextjs,ts,js,tailwind,postgres,mysql,docker,git,linux&theme=dark&perline=10"/>

---

## 📊 GitHub

<div align="center">

<img height="150" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=DiegoArias32&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=667eea&icon_color=667eea&text_color=ffffff&count_private=true&include_all_commits=true&border_radius=10"/>
<img height="150" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DiegoArias32&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=667eea&text_color=ffffff&langs_count=6&hide=html,css&border_radius=10"/>

</div>

> Most of my production work lives in private and company repositories, so these numbers don't tell the whole story. Ask me about the architecture instead — I'd rather talk through a design decision than a commit count.

---

<div align="center">

### Let's talk

I'm available for backend and full-stack roles, remote or with relocation.

<a href="https://www.linkedin.com/in/diego-arias-654426250/">
  <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="mailto:ariasdiego570@gmail.com">
  <img alt="Email" src="https://img.shields.io/badge/ariasdiego570@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,20&height=120&section=footer"/>

</div>
