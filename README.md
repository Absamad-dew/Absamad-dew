# Absamad Manturov

I build reproducible evaluation, reliability, and automation tooling for Russian-language and tool-using AI systems.

Делаю воспроизводимые eval-наборы, инструменты надёжности AI-агентов и прикладную автоматизацию. Предпочитаю runnable proof-of-work, raw traces и измеримые критерии вместо неподтверждённых обещаний.

**Available for fixed-scope paid pilots:** [Telegram](https://t.me/Absamad_m) · [Gmail](mailto:absamad.manturov@gmail.com)

## Three paid starting scopes

| Scope | Fixed start | What you provide | Delivery and acceptance |
|---|---:|---|---|
| **AI / Automation Preflight** | **19 500 ₽ · 2 days** | Process description, constraints, 3–5 anonymized examples | AS-IS/TO-BE, bottleneck matrix and three pilot charters; each has a KPI, baseline, human gate and stop rule |
| **Price Reconciliation Pilot** | **39 000 ₽ · 5 days** | Up to three flat CSV/XLSX files, up to 300 rows, one catalog | Normalized data, review queue, quality metrics and Excel report; acceptance is checked on a frozen sample |
| **Agent Reliability Preflight** | **29 000 ₽ · 3 days** + API costs | One agent version, one test environment, 20 agreed scenarios | 20 scenarios × 3 runs, raw traces, JUnit/JSON/Markdown and failure taxonomy |

[Все пять пакетов, границы и условия](PROJECT_SERVICES_RU.md) · [Критерии приёмки трёх стартовых пилотов](ACCEPTANCE_BRIEFS_RU.md) · [Реестр проверяемых доказательств](EVIDENCE.md)

Чтобы зафиксировать scope, достаточно прислать цель, обезличенный пример входа и ограничение, которое нельзя нарушить. Секреты и необезличенные данные в переписке не принимаются.

**Profile artifacts:** [technical portfolio (PDF)](Absamad_Manturov_AI_Technical_Portfolio.pdf) · [русскоязычное проектное резюме (PDF)](Absamad_Manturov_Project_AI_Python_Resume_RU.pdf) · [резюме: AI и закупочные процессы (PDF)](Absamad_Manturov_Professionals4_Procurement_AI_Resume_RU.pdf) · [резюме: Junior Python (PDF)](Absamad_Manturov_ITK_Python_Resume_RU.pdf) · [procurement AI research plan (PDF)](Absamad_Manturov_Procurement_AI_Research_Plan.pdf)

## Current public work

The three demo repositories below are self-initiated, synthetic proof-of-work. They are not presented as paid client cases. Upstream PRs are open and are not presented as merged contributions.

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
