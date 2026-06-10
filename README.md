22. AI Engineer building production LLM systems.

Currently at [Akatsuki AI Technologies](https://akatsuki.co.jp/) (Tokyo), shipping multi-agent and RAG systems for Japanese enterprise clients across pharma, entertainment, and e-commerce. Promoted from intern to full-time within my first month.

### What I work on

* → Production RAG systems with semantic retrieval, evaluation pipelines (Precision@K, Recall@K), and multi-agent orchestration using LangGraph
* → Open source — primarily in the AI agent infrastructure ecosystem, plus ongoing contributions to security and developer tooling
* → Contract work for [Outlier (Scale AI)](https://outlier.ai/) on agent trajectory evaluation

### Production work at Akatsuki

* → **Real-time meeting advisor** — streaming STT, semantic RAG over 5,961 chunks of internal enterprise docs, page-level citation tracking, Precision@K / Recall@K evaluation methodology. Built for a major Japanese enterprise client.
* → **Multi-agent email security platform** — 5 specialized LangGraph workers (Ingest, Intent, Sandbox, Aggregator, Action) over Gemini, classifying email into 16 threat categories with 0–100 risk scoring. The project that got me promoted from intern to full-time.
* → **Competitive intelligence extraction tool** — LLM pipeline mining market signals from unstructured CRM data for a Japanese pharma client.
* → **Voice-of-Customer sensory evaluation system** — aggregates review data from YouTube and Japanese e-commerce platforms, LLM-scores sensory attributes into structured reports. Built for a Japanese consumer goods client.


### Open source

**Google Summer of Code 2025** at [Python Software Foundation](https://www.python.org/psf/), mentored by Terri Oda. Built multi-format VEX validation tooling for [Intel/cve-bin-tool](https://github.com/intel/cve-bin-tool) — a 1.7k-star software supply chain security project.

Substantive contributions:
* ➤ [Vex-Validate](https://github.com/intel/cve-bin-tool/pull/5144) — multi-format VEX validation (CycloneDX, CSAF, OpenVEX)
* ➤ [Vex-Archive](https://github.com/intel/cve-bin-tool/pull/5297) — archival tooling for triage workflows
* ➤ [CVSS-V4 support](https://github.com/intel/cve-bin-tool/pull/4944) — integrated CVSS v4 scoring across the codebase
* ➤ [Triage HTML report fix](https://github.com/intel/cve-bin-tool/pull/5295) — resolved a critical data-loss bug for products with special characters in their names
* ➤ Standalone tool: [Vex-Updater](https://github.com/JigyasuRajput/vex-updater)

### Personal projects

* → [Knox](https://knox.bz) — AI-powered UGC ad-creative platform for marketing teams. Built the generation-orchestration layer on top of third-party video/avatar APIs. Next.js, Supabase, Clerk.
* → [NeuralMeet](https://github.com/JigyasuRajput/neuralmeet) — [live](https://neuralmeet.vercel.app/sign-in) — AI video-call platform with role-specific agents (tutor, coach) on Gemini, with auto-generated summaries and transcripts.
* → [GSoC-Spy](https://gsoc-spy.vercel.app/) — ⭐ 82+ — tool to track PR activity and surface top contributors across GSoC organizations. Smart caching cut API calls by ~80%.

### Tech I work with

**AI / ML:** LangGraph, multi-agent systems, RAG, vector embeddings, semantic search, agent evaluation, prompt engineering, LLM APIs (Gemini, OpenAI, Claude)

**Stack:** Python, TypeScript, Next.js, FastAPI, Node.js, PostgreSQL, Redis, pgvector, Docker, GCP

### Elsewhere

[LinkedIn](https://www.linkedin.com/in/jigyasu-rajput-218657284/) · [X](https://x.com/rajputwt) · [Email](mailto:jigyasu2021@gmail.com)

Open to remote AI engineering roles, especially at agent infrastructure companies.
