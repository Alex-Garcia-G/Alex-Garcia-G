# Alex Garcia

Full-stack software engineer focused on AI systems, multi-agent pipelines, and developer tooling. I build end-to-end products using TypeScript, React, Node.js, and the Anthropic Claude API.

Currently seeking junior software engineering roles — particularly in AI systems, developer tools, or backend architecture.

**Contact:** wheelergarciaa@gmail.com

---

## Projects

### [Accessibility Audit Tool](https://github.com/Alex-Garcia-G/accessibility-audit-tool) — [Live Demo](https://accessibility-audit-tool-production.up.railway.app)

[![CI](https://github.com/Alex-Garcia-G/accessibility-audit-tool/actions/workflows/ci.yml/badge.svg)](https://github.com/Alex-Garcia-G/accessibility-audit-tool/actions/workflows/ci.yml)

AI-powered WCAG 2.1 accessibility auditor. Submit a URL or HTML file, watch four Claude agents run in sequence, and receive a scored report (0–100) with prioritized violations and AI-generated code fixes.

**Pipeline:** Scanner → Auditor → Severity → Reporter (Claude Haiku + Sonnet)  
**Stack:** React 18, Vite, TypeScript, Node.js, Express, PostgreSQL, Prisma, Railway  
**Features:** GitHub OAuth, SSE live progress, prompt caching (~80% latency reduction on the Auditor), score calculated deterministically in TypeScript (not by Claude), Prisma-backed session store (sessions survive restarts), SSRF protection via DNS resolution, per-user rate limiting, React error boundary  
**Tests:** Vitest suite — score algorithm unit tests + pipeline integration tests with mocked agents; GitHub Actions CI on every push

---

### [AI Code Review Pipeline](https://github.com/Alex-Garcia-G/ai-code-review-pipeline) — [Live Demo](https://ai-code-review-pipeline-production.up.railway.app)

Multi-agent system that reviews GitHub pull requests using Claude. Four specialized agents coordinate in parallel: one plans the review, two analyze code simultaneously (logic + security), and one synthesizes a final verdict.

**Stack:** Node.js, Express, TypeScript, Server-Sent Events, Railway  
**Features:** ~30 second review time, live UI updates via SSE, parallel agent execution

---

## Technical skills

**Languages:** TypeScript, JavaScript, SQL  
**Frontend:** React 18, Vite, Tailwind CSS  
**Backend:** Node.js, Express, Prisma ORM, PostgreSQL  
**AI:** Anthropic Claude API, multi-agent orchestration, prompt engineering, prompt caching, SSE streaming  
**Infrastructure:** Docker, Railway, GitHub Actions CI/CD, GitHub OAuth  
**Tooling:** Vitest, ESLint, Prettier, Husky, Zod
