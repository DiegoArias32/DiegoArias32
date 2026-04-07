<div align="center">

<!-- Header -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,20&height=300&section=header&text=Diego%20Arias&fontSize=80&fontColor=fff&animation=twinkling&fontAlignY=35&desc=Full-Stack%20Developer%20%7C%20.NET%20%7C%20Laravel%20%7C%20React%20%7C%20Cloud&descAlignY=55&descSize=20"/>

<!-- Typing Animation -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=3000&pause=1000&color=667EEA&center=true&vCenter=true&repeat=true&width=600&height=70&lines=Building+enterprise+systems+in+production;Clean+Architecture+%2B+CQRS+%2B+multi-DB;CI%2FCD+with+Jenkins+%2B+Docker+%2B+AWS;AI+platforms+with+RAG+%2B+multi-LLM" alt="Typing SVG"/>

<!-- Badges -->
<p>
  <a href="https://www.linkedin.com/in/diego-arias-654426250/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:ariasdiego570@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/DiegoArias32">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/Anthropic-Claude%20Code%20Certified-D97706?style=for-the-badge&logo=anthropic&logoColor=white"/>
  </a>
</p>

<img src="https://komarev.com/ghpvc/?username=DiegoArias32&color=blueviolet&style=for-the-badge&label=PROFILE+VIEWS"/>

</div>

<br/>

---

<div align="left">

## 👋 Diego De Jesús Arias González

<img align="right" src="https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif" width="380">

Full-Stack Developer building **enterprise-grade web systems** end-to-end — from database schema to CI/CD pipeline. Currently the **sole developer** behind a 5-module platform running in production at **ElectroHuila S.A. E.S.P.**, a Colombian power utility.

My stack spans C# / .NET, Laravel, React / Next.js, TypeScript, and multi-database architectures. I've shipped systems connecting Oracle + SQL Server + PostgreSQL + MySQL in a single application, with real-time SignalR, Jenkins CI/CD, and full E2E test coverage.

On the AI side, I built a full ChatGPT-like platform from scratch — hybrid RAG with pgvector, 4 LLM providers, Stripe billing, and LLM observability.

### 📌 Quick Facts

- 📍 **Location:** Neiva, Colombia 🇨🇴
- 💼 **Currently:** Application Developer @ ElectroHuila S.A. E.S.P.
- 🌐 **Open to:** Remote roles & relocation worldwide
- 🎓 **Education:** ADSO — SENA · 2024–2025
- 🏆 **Certified:** Claude Code in Action — Anthropic (2026)

</div>

<br clear="right"/>

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%">

---

## 🚀 Featured Projects

<br/>

### 🏭 PQR-Agenda — Enterprise Multi-Module System
> **Production** · ElectroHuila S.A. E.S.P. · Built solo from architecture to deployment

<table>
<tr>
<td align="center"><b>Module</b></td>
<td align="center"><b>What it does</b></td>
</tr>
<tr>
<td>📅 PQR Scheduling</td>
<td>Appointment system with interactive calendar, QR verification, Excel export, admin panel, Gmail + WhatsApp notifications</td>
</tr>
<tr>
<td>🏢 Corporate Intranet</td>
<td>Unified portal for 30+ internal apps, categorized by department, SSO</td>
</tr>
<tr>
<td>📄 Actas</td>
<td>Automatic PDF/document generation, PWA</td>
</tr>
<tr>
<td>📊 KPI Dashboard</td>
<td>Real-time indicators (SAIDI, SAIFI, revenue) with Recharts</td>
</tr>
<tr>
<td>🗺️ ServiCampo</td>
<td>Field operations management with KML mapping</td>
</tr>
</table>

**Architecture:** Clean Architecture + CQRS · ASP.NET Core 10 (C# 13) + Laravel 12 (PHP 8.2)
**Data:** Oracle 19c · SQL Server · PostgreSQL · MySQL — all in one app via Entity Framework
**DevOps:** Jenkins declarative pipeline · Docker Compose · Dev / QA / Production
**Testing:** Vitest · Cypress E2E · Playwright · Pest PHP

<p>
<img src="https://skillicons.dev/icons?i=cs,dotnet,php,laravel,react,nextjs,ts,tailwind,docker,postgres,mysql&theme=dark"/>
</p>

---

### 🤖 Electro IA — AI Chat Platform
> **Personal project** · Full-stack ChatGPT-like platform with RAG, multimodal input, and subscription billing

**AI layer:**
- Hybrid RAG: vector similarity (pgvector HNSW 72%) + lexical (25%) + recency boost (3%) over PDFs, text, GitHub repos
- 4 LLM providers via Vercel AI SDK: Claude (Anthropic) · GPT (OpenAI) · Gemini (Google) · Ollama local
- Intent detection across 11 categories — math short-circuit, auto web search (Tavily), context window trimming
- OCR with Tesseract.js · multimodal messages · streaming responses

**Platform layer:**
- Auth: Clerk with webhook sync · Stripe (Free/Pro) · token metering + 30-day reset
- Rate limiting: Upstash Redis · Observability: Langfuse + Sentry
- Turbo monorepo: Next.js 15 + Hono edge API + Drizzle ORM + Neon PostgreSQL

<p>
<img src="https://skillicons.dev/icons?i=nextjs,react,ts,tailwind,postgres&theme=dark"/>
</p>

`pgvector` `Hono` `Drizzle ORM` `Vercel AI SDK` `Stripe` `Clerk` `Langfuse` `Sentry` `Upstash` `Turbo`

---

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%">

## 🛠️ Tech Stack

<div align="center">

### Core

<table>
<tr>
<td align="center" width="100">
<img src="https://techstack-generator.vercel.app/csharp-icon.svg" width="55" height="55"/>
<br><b>C#</b>
</td>
<td align="center" width="100">
<img src="https://skillicons.dev/icons?i=dotnet&theme=dark" width="55" height="55"/>
<br><b>.NET</b>
</td>
<td align="center" width="100">
<img src="https://skillicons.dev/icons?i=php&theme=dark" width="55" height="55"/>
<br><b>PHP</b>
</td>
<td align="center" width="100">
<img src="https://skillicons.dev/icons?i=laravel&theme=dark" width="55" height="55"/>
<br><b>Laravel</b>
</td>
<td align="center" width="100">
<img src="https://techstack-generator.vercel.app/react-icon.svg" width="55" height="55"/>
<br><b>React</b>
</td>
<td align="center" width="100">
<img src="https://skillicons.dev/icons?i=nextjs&theme=dark" width="55" height="55"/>
<br><b>Next.js</b>
</td>
<td align="center" width="100">
<img src="https://techstack-generator.vercel.app/ts-icon.svg" width="55" height="55"/>
<br><b>TypeScript</b>
</td>
<td align="center" width="100">
<img src="https://techstack-generator.vercel.app/aws-icon.svg" width="55" height="55"/>
<br><b>AWS</b>
</td>
<td align="center" width="100">
<img src="https://techstack-generator.vercel.app/docker-icon.svg" width="55" height="55"/>
<br><b>Docker</b>
</td>
</tr>
</table>

<details>
<summary><b>📦 Full stack</b></summary>

<br/>

### Backend & Cloud
<img src="https://skillicons.dev/icons?i=cs,dotnet,php,laravel,python,aws,docker,nginx,linux&theme=dark&perline=9"/>

### Frontend
<img src="https://skillicons.dev/icons?i=react,nextjs,ts,js,tailwind,html,css&theme=dark&perline=9"/>

### Databases
<p>
<img src="https://skillicons.dev/icons?i=postgres,mysql&theme=dark"/>
<img src="https://img.icons8.com/color/56/000000/microsoft-sql-server.png" width="48" height="48"/>
<img src="https://img.icons8.com/color/56/000000/oracle-logo.png" width="48" height="48"/>
</p>

### DevOps & Tools
<img src="https://skillicons.dev/icons?i=git,github,docker,jenkins,vscode,visualstudio,postman&theme=dark&perline=9"/>

### Testing
<img src="https://skillicons.dev/icons?i=vitest,cypress,playwright&theme=dark"/>

</details>

</div>

---

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%">

## 📊 GitHub Analytics

<div align="center">

<p>
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=DiegoArias32&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=667eea&icon_color=667eea&text_color=ffffff&count_private=true&include_all_commits=true&border_radius=10"/>
  <img width="48%" src="https://streak-stats.demolab.com?user=DiegoArias32&theme=radical&hide_border=true&background=0D1117&ring=667eea&fire=ff6b6b&currStreakLabel=667eea&border_radius=10"/>
</p>

<img width="48%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DiegoArias32&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=667eea&text_color=ffffff&langs_count=8&border_radius=10"/>

</div>

---

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%">

## 🏆 Achievements

<div align="center">
<img src="https://github-profile-trophy.vercel.app/api/?username=DiegoArias32&theme=radical&no-frame=true&no-bg=true&margin-w=8&column=7&title=Commits,Repositories,Stars,Followers,PullRequest,Issues,MultiLanguage" width="100%"/>
</div>

---

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%">

<div align="center">

**Open to remote roles and relocation worldwide**

<a href="https://www.linkedin.com/in/diego-arias-654426250/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="mailto:ariasdiego570@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<a href="https://github.com/DiegoArias32">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=3000&pause=1000&color=667EEA&center=true&vCenter=true&width=500&lines=Building+things+that+run+in+production;Let's+build+something+great+together" alt="Typing SVG"/>

</div>

<br/>

<!-- Snake Animation -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/DiegoArias32/DiegoArias32/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/DiegoArias32/DiegoArias32/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/DiegoArias32/DiegoArias32/output/github-contribution-grid-snake-dark.svg">
</picture>

<br/>

<!-- Footer -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,20&height=150&section=footer"/>

<div align="center">
<img src="https://img.shields.io/badge/Hecho%20con-❤️%20%26%20Código-667eea?style=for-the-badge&logo=markdown&logoColor=white"/>
<img src="https://img.shields.io/badge/Status-Open%20to%20Work-00C853?style=for-the-badge&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/Anthropic-Claude%20Code%20Certified-D97706?style=for-the-badge&logo=anthropic&logoColor=white"/>
</div>
