cat > README.md <<'EOF'
# Fazle Rabbi

Freelance **AI Engineer** specializing in secure production AI systems and workflow automation. Multi-tenant RAG, AI agents and LLM security, from the database to the web app. 50+ clients, 100+ AI agents and 500+ workflows shipped.

## Tech

**AI & Agents:** Python • LangGraph • LangChain • RAG (hybrid search, CRAG) • RAGAS • LiteLLM • Claude API • OpenAI • Gemini • Voyage AI • MCP

**Backend & Data:** FastAPI • Pydantic v2 • PostgreSQL (Row Level Security) • pgvector • Qdrant • Redis • Supabase

**Frontend:** TypeScript • React • Next.js

**Security & Governance:** Presidio (PII redaction) • Keycloak (OAuth2) • OPA • hash-chained audit logging • garak • OWASP LLM Top 10 • MITRE ATLAS • CVSS • Trivy • CodeQL

**Observability & Testing:** Langfuse • OpenTelemetry • Locust • pytest • Vitest • Playwright

**Infra:** Docker • Docker Compose • GitHub Actions • AWS • GCP • Azure • Render • uv

**Automation:** n8n • Make.com • Zapier

## What I Do

- Build AI products from database and API design to the dashboards and interfaces users actually touch
- Build multi-tenant RAG and agent platforms with row-level security, cited answers and tamper-evident audit logs
- Harden LLM apps against prompt injection, PII leakage and jailbreaks (OWASP LLM Top 10 aligned)
- Run authorized AI red teaming against LLM and RAG apps, with scored findings and re-tests after fixes
- Design compliance-aware AI systems (GDPR, HIPAA, EU AI Act tooling, SOC 2-aligned controls)
- Ship workflow automation and autonomous agent systems for SaaS teams (Make.com certified)

## Proof

- Kill switch halts a simulated runaway agent in under 5 seconds
- RAGAS quality gate in CI fails the build when faithfulness, answer relevancy or context precision drop
- Red team run: 25 attacks, 3 got through, fixed and re-tested, 0 got through on the re-run (one run each, a weak signal)
- Hash-chained, insert-only audit log with a tamper test
- Both flagship repos are MIT-licensed, with tests and CI

## Projects

| Project | What it is |
|---|---|
| [fazle-enterprise-ai-platform](https://github.com/md-fazle-rabbi/fazle-enterprise-ai-platform) | Multi-tenant RAG and agent platform: Postgres RLS, prompt injection firewall, Presidio PII redaction, Keycloak and OPA access control, signed agent messaging, kill switch, hash-chained audit log, tracing, governance tooling. Runs locally with Docker Compose. |
| [fazle-ai-red-team-toolkit](https://github.com/md-fazle-rabbi/fazle-ai-red-team-toolkit) | Authorized red-team toolkit for LLM/RAG apps. Needs a written scope file to run, 25 OWASP-mapped probes, CVSS-scored reports with MITRE ATLAS mappings that never store prompts or answers. |
| [fazle-llm-cost-router](https://github.com/md-fazle-rabbi/fazle-llm-cost-router) | Routes LLM requests by complexity with Redis caching and Langfuse cost tracking. |
| [fazle-llm-budget-dashboard](https://github.com/md-fazle-rabbi/fazle-llm-budget-dashboard) | Streamlit dashboard that shows whether the cost router is actually saving money. |
| [fazle-ai-health-api](https://github.com/md-fazle-rabbi/fazle-ai-health-api) | Health-focused AI API built with FastAPI and LangGraph. |

## Interests

AI Security • AI Red Teaming • RAG Systems • Agent Architectures • Workflow Automation • Compliance Engineering

## Open To

Remote full-time roles, plus freelance and contract work in AI engineering and workflow automation.

## Contact

- Email: mfrabbi.ai@gmail.com
- LinkedIn: https://www.linkedin.com/in/fazle-rabbi-ai/
EOF
