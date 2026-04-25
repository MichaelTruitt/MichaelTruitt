# Michael Truitt

Director-level engineering & delivery leader in the Greater Seattle Area. 25+ years shipping cloud platforms and enterprise modernization. Currently exploring **Director of Software Engineering / Technical Program Management / Product Management** roles.

🌐 [michael-truitt.com](https://michael-truitt.com) · 💼 [LinkedIn](https://www.linkedin.com/in/michael-truitt/) · ✉️ mike.truitt@gmail.com

---

## What I'm building

Most of my repos are private (IP-protected) — every project below is documented in detail with **animated architecture diagrams** and **live interactive demos** at [michael-truitt.com](https://michael-truitt.com). The site itself has an AI chat panel (Claude-powered) grounded in my resume, so you can ask questions and get grounded answers.

- **Career Runway** ([career-runway.com](https://career-runway.com)) — AI-powered job search, resume tailoring, ATS scoring, and interview prep. Three-tier AI fallback (Claude → Gemini → local Ollama), 16 Celery tasks, semantic job matching via pgvector.
  *FastAPI · React · Postgres · 6 Docker containers.*

- **VOH (Vestiges of History)** — ASCII roguelike with persistent characters, 8 dungeons, 12 classes, and a player-run marketplace. Dual auth (Entra ID + JWT/BCrypt), session-ownership middleware, real-time WebSocket gameplay, six-layer automated security stack.
  *.NET 9 · React · TypeScript · Postgres · Docker.*

- **QCloud / CloudMover** — many-to-many cloud migration platform for the post-Broadcom-VMware-pricing exodus. Pluggable source/target providers, canonical raw-disk format (avoids the N×M converter explosion), Go agent on the source host, Claude-powered sizing reports.
  *FastAPI · Go · React · Anthropic SDK.*

- **filecopy** — production PowerShell migration scripts (Azure Blob, AWS S3, UNC shares, on-prem backup repos) with self-bootstrapping module installs + DPAPI credential vault. Used in customer engagements at Veeam.

## How I work

Hands-on with the AI stack: Claude API, Google Gemini, local Ollama, pgvector, prompt engineering, multi-tier fallback with backoff, structured outputs, tool use. Cloud-first across Azure / AWS / GCP — built Azure Stack at Dell EMC, AVS / ARM / Bicep at Neudesic. Comfortable in Python · TypeScript/React · C#/.NET · PowerShell · Go. Engineering hygiene: DevSecOps · CI/CD · IaC · SLI/SLO · RCA loops · automated security scanning (CodeQL / Semgrep / Trivy / gitleaks / Dependabot).

## Track record

- **$81M** first-year revenue from hybrid-cloud platform delivery at Dell EMC
- **60%** reduction in support incidents from production GenAI automation (Fortune 100 client, Neudesic)
- **$700M** in VMware-based cloud offerings revenue at EMC ($120M direct attribution)
- **70+ engineer** global org founded and scaled at Dell EMC
- **>90%** on-time / on-budget delivery across modernization programs
- **Microsoft Gold Star Award (×2)**, Values Award, Best Practice Award, Top Contributor Award (Windows Defender code acquisition)

---

*Repos here are mostly private — the contribution graph above is a better activity signal than the visible repo list. Want a deep dive on any of the projects? Use the AI chat at [michael-truitt.com](https://michael-truitt.com) or [reach out on LinkedIn](https://www.linkedin.com/in/michael-truitt/).*
