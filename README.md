# Fatih Karataş

**Product engineer** | backend and applied AI.

I work on systems that are already running and can't be taken down to be fixed. Legacy platforms, client backends, and the operational workflows on top of them. Java and Spring on the backend, Next.js when there's a UI, and LLMs where a workflow needs judgment rather than another rule.

## What I've shipped

Most of it is client and startup work under NDA.

- **Germany-based agency.** Modernized a legacy web platform and its operational workflows while it stayed in production. Old and new ran in parallel. I mapped the existing workflows and what each one touched before changing anything, then refactored against specific targets instead of rewriting wholesale. Public, portal and admin surfaces, auth, i18n routing, relational data modeling.
- **AI systems, same client.** LLM and RAG pipelines over the platform's own documents and data, built into the existing operational workflows.
- **Marketplace platform**, early-stage international startup. Listing and application workflows, REST APIs, SEO-critical Next.js rendering, data-driven risk scoring.
- **Internal admin and reporting panel** on the same backend, role-based.

## Open source

**[heymrun/heym](https://github.com/heymrun/heym)**, AI-native workflow automation. [PR #500](https://github.com/heymrun/heym/pull/500), merged: pulled ClickHouse execution out of the monolithic workflow executor into its own node module, with tests.

## Public code

**[Fintech RTS](https://github.com/fatihkaratash/toyota_rts_fintech)**. Real-time market data through Kafka into Redis, PostgreSQL and OpenSearch. Built around two constraints: a replayed message must not corrupt state, and one tick must stay traceable end to end under concurrent consumers. _Java 21 · Spring Boot · Docker_

**[FitMind AI](https://github.com/fatihkaratash/fitmind_ai)**. Gym management and appointments with a Gemini-backed assistant. _C# · ASP.NET Core MVC · PostgreSQL_

---

[LinkedIn](https://www.linkedin.com/in/fatihkaratash/) · [f.karatash.dev@gmail.com](mailto:f.karatash.dev@gmail.com)
