# Hey, I'm Aditya 👋

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=2500&pause=800&color=2563EB&center=true&vCenter=true&width=600&lines=Building+modern+web+software;Next.js+%7C+TypeScript+%7C+PostgreSQL;Full-stack+developer%2C+backend-leaning;I+build+and+ship+real+web+apps" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://primefold-portfolio.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-Visit-2563EB?style=flat&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://github.com/PrimeFold?tab=repositories">
    <img src="https://img.shields.io/badge/Projects-Browse-2563EB?style=flat&logo=github" alt="Projects" />
  </a>
</p>

---

## 🧑‍💻 About Me

I'm a full-stack developer from Ranchi who turns ideas into working products. I like understanding **why** systems are built the way they are, not just how to wire them together, and I lean toward backend work: data modeling, APIs, and the parts users never see but always feel.

I ship projects end to end, from database schema to deployed UI. My flagship, PulseGuard, is an AI-assisted incident response platform with vector search, caching, and role-based multi-tenancy.

---

## ⚡ Flagship Project: PulseGuard

**Autonomous SRE & multi-tenant incident response platform** · [Live demo](https://pulseguard-app-navy.vercel.app) · [Source](https://github.com/PrimeFold/pulseguard)

PulseGuard is a self-hosted console that takes raw production logs, groups related errors into incidents, looks up the relevant runbook, and lets an AI agent diagnose the outage and draft a code fix. Nothing reaches your repo until a human approves it.

**How it works**

1. **Ingest:** services POST logs to an API-key-protected, rate-limited endpoint.
2. **Cluster:** stack traces are scrubbed of UUIDs, IPs, timestamps and numbers, then hashed (SHA-256) into a signature. A sliding window in Redis opens an incident only after 3 identical errors in 3 minutes, which cuts alert noise.
3. **Diagnose:** in the incident "War Room", an AI agent queries telemetry, searches runbooks with pgvector semantic search (RAG), and reads files from the connected GitHub repo.
4. **Fix:** the agent proposes a hotfix as a diff card. An `OWNER` or `ADMIN` approves it, and only then does PulseGuard open a pull request.

**Engineering highlights**

- **Multi-tenant RBAC:** organizations are isolated server-side, with role checks (`OWNER`, `ADMIN`, `MEMBER`, `VIEWER`) on every sensitive action.
- **Bring-your-own-model:** each org plugs in its own AI provider key (Google, Anthropic, OpenAI, Groq, OpenRouter), encrypted at rest.
- **Human-in-the-loop by design:** the agent is read-only, and repo writes are gated behind admin approval.
- **RAG pipeline:** PDF and Markdown runbooks are chunked, embedded, and searched by cosine similarity in Postgres.
- **Production hygiene:** Redis caching, 7-day log auto-pruning, a Vitest suite covering encryption and RBAC, and a Docker Compose local stack. It is deployed on Vercel, and the repo has 70+ commits.

**Stack:** Next.js 16 · React 19 · TypeScript · Bun · Prisma · PostgreSQL + pgvector · Redis · Vercel AI SDK · Better Auth · Octokit · Docker

---

## 🚀 More Projects

| Project | What it does | Stack |
|---|---|---|
| [**Spoonful**](https://github.com/PrimeFold/Spoonful) | Community-driven food discovery for college students: affordable dhabas, tiffin services and local gems that never show up on Zomato | TypeScript |
| [**Invoicify**](https://github.com/PrimeFold/Invoicify) | Developer-first time tracking and auto-invoicing dashboard, with server-side vector PDF generation | Next.js (App Router), Prisma, TypeScript |
| [**SpendPilot**](https://github.com/PrimeFold/SpendPilot) | Audit your AI spend in 60 seconds | TypeScript |
| [**Passly**](https://github.com/PrimeFold/Passly) | Event registration and ticketing platform built for Indian organizers | TypeScript |

---

## 🛠️ Tech Stack

**Languages & Frontend**

<img src="https://skillicons.dev/icons?i=ts,js,html,css,react,nextjs,tailwind" alt="Frontend stack" />

**Backend & Database**

<img src="https://skillicons.dev/icons?i=nodejs,bun,postgres,prisma,redis,docker" alt="Backend stack" />

**Tools**

<img src="https://skillicons.dev/icons?i=git,github,vscode" alt="Tools" />

**Currently exploring:** system design, deeper backend architecture, AI agents

---

## 🚧 Currently Working On

- Going deeper on **Next.js** and backend architecture
- Databases, caching and system design
- Reading code written by better engineers, then applying what I learn to my own projects

---

## 🤝 Let's Connect

<p align="left">
  <a href="https://primefold-portfolio.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-2563EB?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://www.linkedin.com/in/aditya-raj-primefold">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://x.com/aditya_xb26476">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" />
  </a>
  <a href="https://instagram.com/solarisrex.zen">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
  </a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=2563EB&height=100&section=footer" alt="" />
</p>
