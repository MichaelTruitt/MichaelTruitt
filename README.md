# Michael Truitt

Director-level engineering and delivery leader in the Greater Seattle Area. 25+ years shipping cloud platforms, enterprise modernization, and AI-driven automation. Currently exploring **Director of Software Engineering, Technical Program Management, and Product Management** roles.

🌐 [michael-truitt.com](https://michael-truitt.com) · 💼 [LinkedIn](https://www.linkedin.com/in/michael-truitt/) · ✉️ mike.truitt@gmail.com

---

## A note from me

I started my career as a high school history and English teacher and accidentally pivoted into tech in 1998 when I implemented a 9-building school district computer network. Twenty-six years later, the teaching mindset still shows up in how I run engineering teams: clarity, scaffolding, repetition, and celebrating small wins.

Outside of work, I volunteer-coach youth basketball (most recently with Eastlake School District, 2025–2026) — the K-12 coaching habit that started during my Highline teaching years has stuck.

If you're a hiring team looking for a senior leader who still writes code, runs operating rhythms with rigor, and treats teaching as a leadership skill, I'd love to talk.

## What I'm building

Most of my repos are private to protect pre-launch IP. Every project below is documented in detail with **animated architecture diagrams** and **live interactive demos** at [michael-truitt.com](https://michael-truitt.com). The site has an AI chat panel (Claude-powered, lens-aware) grounded in my resume, so you can ask questions and get grounded answers.

- **Career Runway** ([career-runway.com](https://career-runway.com)). AI-powered job search, resume tailoring, ATS optimization, cover letters, interview prep, and Kanban-style application tracking. Multi-provider AI backbone with graceful degradation; async task orchestration; semantic match via pgvector.
  *FastAPI · React · PostgreSQL + pgvector · Redis · Docker.*

- **QCloud / CloudMover**. Many-to-many migration platform aimed at the post-VMware-pricing-shift market. Pluggable source and target providers, single-binary Go agent on source hosts, separation of orchestration and data movement, and an LLM-assisted assessment service.
  *FastAPI · Go · React · PostgreSQL · Redis.*

- **VOH (Vestiges of History)**. ASCII roguelike and MUD with persistent characters, multi-class progression, and a player-driven economy. Engineered like a product: dual auth (Entra ID + JWT/BCrypt), session-ownership middleware, real-time WebSocket gameplay, and a six-layer automated security stack.
  *.NET 9 · React · TypeScript · PostgreSQL · Docker.*

- **Grant Discovery (Vertical SaaS Prototype)**. Multi-tenant SaaS for nonprofits to discover, score, and apply for grants. Weighted-signal fit ranker plus a RAG pipeline that drafts new applications from a tenant's library of prior winning submissions.
  *Next.js · FastAPI · PostgreSQL + pgvector · Meilisearch.*

- **This portfolio site**. React + Vite + Vercel serverless function that proxies to Claude. The same data drives both the rendered page and the chatbot, with sensitivity rules that gate pre-launch product details behind an NDA handshake. Upstash-backed sliding-window rate limit and a hardened security posture.
  *React · Vite · TypeScript · Anthropic SDK · Upstash Redis.*

- **filecopy**. Field-services-friendly PowerShell migration scripts written at Veeam. Each script self-bootstraps required modules, encrypts credentials with DPAPI, and writes a timestamped audit log. Used in customer engagements to validate SaaS backup performance.
  *PowerShell 7 · Az and AWS modules · DPAPI.*

I am also serving as **VP of Engineering and Cloud Architect** for two stealth-stage SaaS products under NDA (one current, one concluded). Sole architect and engineer for both, shipping from pilot-stage exploration through production-hardened release. Architecture and code reviews available to qualified hiring teams.

## How I work

Hands-on with the AI stack: Claude API, Google Gemini, local Ollama, pgvector, prompt engineering, multi-tier fallback with backoff, structured outputs, and tool use. Cloud-first across Azure, AWS, and GCP. Built Azure Stack at Dell EMC; led the AVS, ARM, and Bicep work at Neudesic and IBM Consulting. Comfortable in Python, TypeScript and React, C# and .NET, PowerShell, and Go. Engineering hygiene includes DevSecOps, CI/CD, IaC, SLI and SLO, RCA loops, and automated security scanning (CodeQL, Semgrep, Trivy, gitleaks, Dependabot).

## Track record

- **$81M** first-year revenue from hybrid-cloud platform delivery at Dell EMC
- **60%** reduction in support incidents from production GenAI automation for a Fortune-100 reseller (Neudesic and IBM Consulting era); designed the two-phase AI Ops platform after triaging 1,182 incidents on the customer's e-commerce and logistics platforms
- **$700M** in VMware-based cloud offerings revenue at EMC; $120M direct attribution
- **$1.8M** Tiger Team authorization on a snap call to keep 6 marquee Fortune-100 customers on the Enterprise Hybrid Cloud GA path; protected over $100M of annual EMC sales without forking the code-tree
- **Product Manager and Program Lead** for Microsoft Private Cloud Fast Track v3 through v4. Secured corporate funding, owned the product through end-of-life, managed Microsoft Services contractors authoring the reference architectures, and managed a 9-partner OEM/IHV ecosystem
- **70+ engineer** global organization founded and scaled at Dell EMC
- **$1M+** in client business delivered in the first 8 months as Principal / Technology Strategy Consultant at Indigo Slate
- **>90%** on-time and on-budget delivery across modernization programs
- **5,000-attendee** VMUG Chicago hybrid-cloud keynote
- **Microsoft Gold Star Award (×2)**, Values Award, Best Practice Award (event stream grew 25× after the OEM call-data project landed), Top Contributor Award (Windows Defender code acquisition), Circle of Excellence, multiple Ship-It Awards
- **District-wide Teacher of the Year** at Highline Public Schools (1993 to 1998)

---

*Repos here are mostly private; the contribution graph is a better activity signal than the visible repo list. Want a deeper walkthrough of any of the projects? Use the AI chat at [michael-truitt.com](https://michael-truitt.com) or [reach out on LinkedIn](https://www.linkedin.com/in/michael-truitt/).*
