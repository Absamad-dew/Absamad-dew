# Absamad Manturov

I build reproducible evaluation, reliability, and automation tooling for Russian-language and tool-using AI systems.

Делаю воспроизводимые eval-наборы, инструменты надёжности AI-агентов и прикладную автоматизацию. Предпочитаю runnable proof-of-work, raw traces и измеримые критерии вместо неподтверждённых обещаний.

[One-page technical portfolio (PDF)](Absamad_Manturov_AI_Technical_Portfolio.pdf)

[Targeted case: Procurement AI research plan (PDF)](Absamad_Manturov_Procurement_AI_Research_Plan.pdf)

**Available for fixed-scope paid pilots:** [Telegram](https://t.me/Absamad_m) · [Gmail](mailto:absamad.manturov@gmail.com)

- **Agent reliability preflight, 2–4 days:** 15–30 client-owned scenarios, raw traces and JUnit/JSON/Markdown report.
- **Serving-correctness audit, 1–3 days:** raw-output audit, conservative normalization, sampling/token ablation and explicit stop criteria.
- **Price/data reconciliation, 3–5 days:** 2–3 anonymized CSV/XLSX files, acceptance sample, review queue and auditable delivery.

## Current public work

- [GigaChat Python SDK PR #117](https://github.com/ai-forever/gigachat/pull/117) — **open, awaiting maintainer review**; typed sync/async support for `POST /filter/check`; 490 tests, Ruff and mypy passed locally.
- [GigaChat Python SDK PR #118](https://github.com/ai-forever/gigachat/pull/118) — **open, awaiting maintainer review**; closes issue #79 with complete ContextVar/header mappings, lifecycle guidance, and an explicit boundary between SDK behavior and application tracing conventions.
- [Giga Agent PR #131](https://github.com/ai-forever/giga_agent/pull/131) — **open, mergeable clean**; converts an embedding deletion blocked by a RAG collection into an explicit `409 Conflict`, with 21 targeted tests and Ruff passing locally.
- [Yandex AI Studio SDK PR #235](https://github.com/yandex-cloud/yandex-ai-studio-sdk/pull/235) — **open, awaiting maintainer review**; backward-compatible per-attempt retry timeout; 233 tests passed locally.
- [ruagent-compat v0.2.0](https://github.com/Absamad-dew/ruagent-compat/releases/tag/v0.2.0) — 48 tests for provider-neutral agent contracts plus provenance-aware structured-output auditing; green Ubuntu/Windows CI.
- [ru-agent-eval-kit v0.1.1](https://github.com/Absamad-dew/ru-agent-eval-kit/releases/tag/v0.1.1) — 22 synthetic MCP security and reliability scenarios, raw traces, JSON/Markdown/JUnit exports, Ubuntu/Windows CI.
- [price-intelligence-demo v0.1.1](https://github.com/Absamad-dew/price-intelligence-demo/releases/tag/v0.1.1) — deterministic CSV/XLSX normalization, matching, audit trail, quality gate, independently inspected Excel output, Ubuntu/Windows CI.

## Useful collaboration scopes

- Russian hardness and regression suites with fixed rubrics and reproducible model runs;
- tool-agent reliability: timeouts, retries, idempotency, schema drift and unknown outcomes;
- authorized MCP/agent security evaluation with human-in-the-loop controls;
- narrow data-automation pilots with an acceptance dataset and measurable quality gates.

All demo results are labeled as synthetic unless they come from a versioned live run. Security testing is performed only in an explicitly authorized scope.

The first call freezes the acceptance set, allowed environment and success metrics. No production security testing or external side effects without written scope.

## Contact

- Telegram: [@Absamad_m](https://t.me/Absamad_m)
- Gmail: [absamad.manturov@gmail.com](mailto:absamad.manturov@gmail.com)
