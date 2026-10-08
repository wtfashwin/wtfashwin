# Ashwin Upadhyay

**AI Systems Engineer · LLM Applications · Backend Platforms**

I build AI applications and the backend systems behind them: retrieval, APIs, data models, authorization, and asynchronous workflows. My work spans Python services, React/TypeScript applications, and PostgreSQL, with a focus on making behavior testable and failures recoverable.

Currently a **Founding AI Engineer at Sylox**, working on data privacy and AI systems. I carry features from requirements and system design through implementation, review, testing, and release.

[LinkedIn](https://www.linkedin.com/in/wtfashwin/) · [Portfolio](https://wtfashwin.github.io/Portfolio/) · [Email](mailto:ashwinupadhyay09@gmail.com)

## Recent work

- **Data privacy:** sensitive-data classification using regex, Presidio NER, checksum validation, context signals, and human review; FastAPI, React/TypeScript, and PostgreSQL.
- **Backend reliability:** test recovery, Alembic migration consolidation, authentication fixes, and CI checks that block failing changes.
- **Secure integrations:** Microsoft 365 and Google Workspace connections, encrypted credentials, API authorization, and tenant-aware controls.
- **LLM applications:** legal-document retrieval and grounded answers; provider-agnostic verification services; a conversational analytics prototype with read-only SQL validation.
- **System design:** proposed customer-hosted scanning and resumable job execution, with explicit source lineage and evidence storage.

These are professional work summaries. Employer source code is not included here; proposed architecture is described as proposed.

## Selected public projects

| Project | Focus |
| --- | --- |
| [Customer Support System](https://github.com/wtfashwin/Customer-Support-System) | FastAPI AI service, RAG, LangGraph tool workflows, streaming, and a TypeScript application. [Agent workflow PR](https://github.com/wtfashwin/Customer-Support-System/pull/5) · [Request tracing PR](https://github.com/wtfashwin/Customer-Support-System/pull/8) |
| [Context Dock](https://github.com/wtfashwin/ContextDock) | Native macOS developer tool built with Swift, SwiftUI, and AppKit; local task context, agent events, and decision journaling. |

## Selected merged contributions

I contribute fixes where correctness, resource use, or security breaks down. **11 merged PRs across seven upstream projects**, with selected changes below.

| Project | Contribution |
| --- | --- |
| [Prefect](https://github.com/PrefectHQ/prefect/pull/22035) | Allow Azure Blob result storage to overwrite on rewrite. |
| [dlt](https://github.com/dlt-hub/dlt/pull/3947) | Ingest Parquet row groups individually to bound ADBC driver memory use. |
| [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics/pull/10974) | Stop PromQL `integrate()` from extrapolating past the end of a series. |
| [Unsloth](https://github.com/unslothai/unsloth/pull/5651) | Hide non-matching chat threads in search. |
| [Langfuse Python SDK](https://github.com/langfuse/langfuse-python/pull/1664) | Add compatibility with `wrapt` 2.x. |
| [Tracecat](https://github.com/TracecatHQ/tracecat/pull/2715) | Add `_source` field filtering to Elastic Security detection queries. |
| [lollms-webui](https://github.com/ParisNeo/lollms-webui/pull/690) | Harden path sanitization against traversal with regression tests. |

[Complete OSS record: merged, open, and closed submissions](OPEN_SOURCE.md) · [Live merged PRs](https://github.com/search?q=author%3Awtfashwin+is%3Apr+is%3Amerged+-user%3Awtfashwin&type=pullrequests)

## Core tools

**Backend & data:** Python, SQL, FastAPI, SQLAlchemy, PostgreSQL, Alembic, Redis, Celery, Parquet

**AI applications:** RAG, LangGraph, LangChain, embeddings, reranking, retrieval evaluation

**Application & delivery:** React, TypeScript, Docker, GitHub Actions, pytest, OpenTelemetry

## Achievements & credentials

- **[LeetCode](https://leetcode.com/u/wtfashwin/):** 923 problems solved, including 155 hard; contest rating 1,752; 32 earned badges.
- **[Kaggle](https://www.kaggle.com/ashwinupadhyay):** reproducible ML experiments, including an [LLM preference CPU baseline](https://www.kaggle.com/code/ashwinupadhyay/llm-preference-measured-cpu-baseline); 19 confirmed badges.
- **[Credly](https://www.credly.com/users/ashwin-upadhyay.d80bc5d2/badges/credly):** Astronomer certifications in Apache Airflow 3 Fundamentals and DAG Authoring.

[Full achievement and badge record](ACHIEVEMENTS.md) · Counts checked October 8, 2026; platform profiles carry the latest totals.

I’m interested in AI systems and backend engineering roles where ownership includes system design, implementation, and verification.
