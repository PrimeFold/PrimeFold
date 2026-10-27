# Hey, I'm Aditya 👋

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=2500&pause=800&color=2563EB&center=true&vCenter=true&width=600&lines=Cloud+Native+%26+Go+Systems+Engineer;Building+high-throughput+distributed+software;L4+Proxies+%7C+Databases+%7C+Kubernetes;Active+CNCF+Contributor" alt="Typing SVG" />
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

I'm a systems and backend developer focused on building **high-throughput, cloud-native infrastructure in Go** and full-stack platforms with **TypeScript & Next.js**. I care about what happens at the network socket layer, memory allocations on the heap, and designing software that doesn't buckle under heavy concurrency.

Active contributor to the **CNCF ecosystem (OpenCost)**, working on Kubernetes cost-allocation engines, Prometheus metrics, and distributed tracing.

---

## 🌐 Open Source Contributions (CNCF)

| Project | Organization | PR / Impact | Tech |
|---|---|---|---|
| [**OpenCost**](https://github.com/opencost/opencost) | CNCF | [#4144](https://github.com/opencost/opencost/pull/4144) · Added lifecycle unit tests for `ConfigMapWatchers.Stop()`, achieving 100% method coverage (+14.3% pkg jump) | Go, Concurrency |
| [**OpenCost**](https://github.com/opencost/opencost) | CNCF | [#4146](https://github.com/opencost/opencost/pull/4146) · Dead code elimination in `ParseAggregationProperties` & Prometheus sanitization tests | Go, PromQL, CI |
| [**OpenCost UI**](https://github.com/opencost/opencost-ui) | CNCF | [#105](https://github.com/opencost/opencost-ui/pull/105) · Resolved 57 strict TypeScript compile errors across legacy reporting routes | React, TypeScript |

---

## ⚡ Featured Systems Projects

### 🔹 [GoBalance](https://github.com/PrimeFold/gobalance) · Zero-Allocation L4 TCP Reverse Proxy
A high-throughput Layer 4 TCP load balancer written in Go with least-connections routing, dynamic health-check daemon, and Prometheus metrics.
- **Performance:** Benchmarked at **26 ns/op** with **0 heap allocations/op** using `sync.Pool` buffer recycling.
- **Reliability:** Built with atomic counters, `net/http/pprof` runtime profiling, and graceful socket draining on SIGTERM.
- **Stack:** Go · TCP Sockets · sync.Pool · Prometheus · pprof · Benchmarks

### 🔹 [ByteCache](https://github.com/PrimeFold/bytecache) · High-Performance In-Memory KV Database
An in-memory key-value database running over raw TCP sockets with active TTL expiration and Cobra CLI.
- **Throughput:** **50M+ reads/sec (20.4 ns/op)** and **31M+ writes/sec (31.8 ns/op)** across 18 cores with zero heap allocations.
- **Concurrency:** Thread-safe read/write locking via `sync.RWMutex`, active background eviction daemon preventing memory leaks.
- **Stack:** Go · Raw TCP Protocol · sync.RWMutex · Cobra CLI · Benchmarks

### 🔹 [PulseGuard](https://github.com/PrimeFold/pulseguard) · Autonomous SRE Incident Response Platform
A multi-tenant production console that ingests raw production logs, aggregates errors using SHA-256 signatures and sliding-window rate-limiting, and utilizes an AI agent with RAG (pgvector) to draft hotfixes.
- **Stack:** Next.js · TypeScript · Redis · PostgreSQL + pgvector · Prisma · Docker

---

## 🚀 More Projects

| Project | What it does | Stack |
|---|---|---|
| [**Spoonful**](https://github.com/PrimeFold/Spoonful) | Community-driven food discovery for college students: affordable local spots that don't appear on commercial food apps | TypeScript, Next.js |
| [**Invoicify**](https://github.com/PrimeFold/Invoicify) | Developer-first time tracking and auto-invoicing dashboard with server-side vector PDF generation | Next.js, Prisma, TypeScript |
| [**SpendPilot**](https://github.com/PrimeFold/SpendPilot) | Real-time AI token and compute spend auditor for organizations | TypeScript, React |

---

## 🛠️ Tech Stack

**Systems, Cloud Native & Backend**

<img src="https://skillicons.dev/icons?i=go,docker,kubernetes,postgres,redis,nodejs,bun" alt="Backend and Systems stack" />

**Frontend & Languages**

<img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,tailwind,html,css" alt="Frontend stack" />

**Tools & Diagnostics**

<img src="https://skillicons.dev/icons?i=git,github,vscode,linux,bash" alt="Tools" />

---

## 🚧 Currently Working On

- Deepening **Go low-level networking**, gRPC streaming pipelines, and microservice architectures
- Contributing upstream to CNCF repositories (OpenCost, CoreDNS, Jaeger)
- Preparing for **LFX Mentorship & GSoC 2027** in Cloud Native & Systems

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
