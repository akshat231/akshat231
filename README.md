# Akshat Sharma

Backend Engineer · Systems & AI Infrastructure · NIT Hamirpur

Building distributed systems and AI-powered automation tools at **SearchUnify**,
where I work on R&D and architecture — shipping things that run in production
across 50+ client servers.

---

## 🔧 Tech Stack

**Languages:** JavaScript · TypeScript · C++ · Python

**Frameworks & Libraries:** Node.js · Express · React · OpenAI API

**Databases:** PostgreSQL · MongoDB · Elasticsearch · Redis

**Cloud & DevOps:** AWS S3 · Docker · Jenkins · Ansible · GitLab CI · Vercel

**Monitoring & Analytics:** Apache Superset · DevLake

---

## 💼 Experience

### Software Engineer — [SearchUnify](https://www.searchunify.com)
**Jan 2024 – Present**

- Designed a **no-code ETL pipeline framework** for agentic analytics — multi-step
  extract (key-value SQL), transform (raw SQL + sandboxed Node.js via `isolated-vm`),
  and load workflows via API, with ordered execution and auto table provisioning.
- Built an **Outage Analysis Agent** that aggregates logs and metrics on server
  outages and feeds them to an LLM to generate RCA and CAPA reports — delivered
  via Google Chat webhook and Jira within minutes of detection.
- Developed an **AI-powered MR Analyzer** on GitLab webhooks that generates
  structured Markdown review reports and posts them as reviewer comments.
- Engineered a **centralized analytics dashboard** across 50+ client servers (10
  multi-tenant) — Node.js shipper via Ansible, AWS S3, Postgres, Apache Superset.
- Automated **client upgrade workflows** with a Claude-powered skill, reducing
  cycles from months to days and per-iteration review to ~2 hours.
- Drove **CI/CD and infra improvements** — parallelized container builds (40%
  faster), Jenkins automations for branch protection and blue-green deployments.

---

## 🚀 Projects

### [API Metrics System](https://www.npmjs.com/package/api-metrics-system) · [GitHub](https://github.com/akshat231/ams)
`Node.js` · `TypeScript` · `Elasticsearch`

Published **npm middleware package** for zero-config API observability — captures
request method, response time, and status codes to Elasticsearch in real-time.
Includes a self-hosted dashboard with time-range filtering and a CLI via
`npx api-metrics-system init`.

---

## 📫 Connect

[GitHub](https://github.com/akshat231) ·
[Email](mailto:akshatsharmasde@gmail.com) ·
[Twitter/X](https://twitter.com/akshatismyname)
