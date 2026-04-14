# Hi, I'm Alex Garcia

I'm a software engineer focused on AI systems — designing multi-agent pipelines, orchestration layers, and AI-powered developer tooling.

---

## What I'm building

**[AI Code Review Pipeline](https://github.com/Alex-Garcia-G/ai-code-review-pipeline)** — A multi-agent system that reviews pull requests like a senior engineer. Four specialized Claude AI agents work in a coordinated pipeline: one plans the review, two analyze code in parallel (logic + security), and one synthesizes a final verdict.

- Live demo: [ai-code-review-pipeline-production.up.railway.app](https://ai-code-review-pipeline-production.up.railway.app)
- Reviewer + security agents run **concurrently** per file to reduce latency
- Streams live progress to the UI via Server-Sent Events
- Paste any public GitHub PR URL and get a full review in ~30 seconds

---

**[AI Accessibility Audit Tool](https://github.com/Alex-Garcia-G/accessibility-audit-tool)** *(in development)* — A full-stack web app that audits any URL or HTML file for WCAG accessibility violations and returns a scored report with AI-generated code fixes.

- Four-agent Claude pipeline: Scanner → Auditor → Severity → Reporter
- React 18 + TypeScript frontend with Tailwind CSS
- Node.js + Express + Prisma + PostgreSQL backend
- GitHub OAuth authentication + per-user audit history
- Architecture mirrors production standards: typed end-to-end, Dockerized DB, Railway deployment target

---

## Skills

- **Languages:** JavaScript, TypeScript, Node.js, HTML/CSS
- **AI:** Anthropic Claude API, multi-agent orchestration, prompt engineering, SSE streaming
- **Frontend:** React 18, Vite, Tailwind CSS
- **Backend:** Express, REST APIs, Prisma ORM, PostgreSQL
- **Infrastructure:** Railway, Docker, Git, GitHub OAuth

---

## What I'm looking for

Junior software engineering roles — especially anything touching AI systems, developer tooling, or backend infrastructure. I think clearly about system design and I build things that actually work end-to-end.

---

## Connect

- **Email:** wheelergarciaa@gmail.com
- **Live project:** [ai-code-review-pipeline-production.up.railway.app](https://ai-code-review-pipeline-production.up.railway.app)
