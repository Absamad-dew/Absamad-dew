# Реестр проверяемых доказательств

Статусы:

- `synthetic proof` — самостоятельный прототип на версионных демо-данных;
- `open upstream PR` — изменение предложено upstream, но ещё не принято;
- `paid client case` — оплаченный клиентский результат. Таких публичных кейсов сейчас нет.

| Утверждение | Статус и проверяемый источник | Что действительно доказано | Что не доказано |
|---|---|---|---|
| Импорт, нормализация и сверка CSV/XLSX | `synthetic proof`: [price-intelligence-demo v0.1.1](https://github.com/Absamad-dew/price-intelligence-demo/releases/tag/v0.1.1), [visual proof](https://github.com/Absamad-dew/price-intelligence-demo/blob/main/docs/price-demo-preview.png), [quality metrics](https://github.com/Absamad-dew/price-intelligence-demo/blob/main/output/quality_metrics.json), [CI](https://github.com/Absamad-dew/price-intelligence-demo/actions/runs/29398313109) | Детерминированный pipeline, mappings, fingerprints, review queue, Excel output и тесты на Windows/Linux | Production accuracy, экономический эффект и клиентская эксплуатация; текущий gold sample содержит 8 строк |
| Повторяемая evaluation AI-агентов | `synthetic proof`: [ru-agent-eval-kit v0.1.1](https://github.com/Absamad-dew/ru-agent-eval-kit/releases/tag/v0.1.1), [comparison JSON](https://github.com/Absamad-dew/ru-agent-eval-kit/blob/main/results/demo/comparison.json), [CI](https://github.com/Absamad-dew/ru-agent-eval-kit/actions/runs/29397478049) | 22 versioned security/reliability сценария, 3 повтора, raw traces и JUnit/JSON/Markdown | Качество конкретной коммерческой модели, production security и полнота относительно MERA |
| Контракты надёжных tool-agents | `synthetic proof`: [ruagent-compat v0.2.0](https://github.com/Absamad-dew/ruagent-compat/releases/tag/v0.2.0), [CI](https://github.com/Absamad-dew/ruagent-compat/actions/runs/29397477661) | 48 тестов на idempotency, retries, permission gates, state/effect integrity и structured-output provenance | Production SLA, поддержка всех провайдеров и реальная нагрузка |
| Typed API `POST /filter/check` | `open upstream PR`: [GigaChat SDK #117](https://github.com/ai-forever/gigachat/pull/117) | Код, тесты, sync/async surface и документация доступны для review | PR не смержен и пока не имеет maintainer review |
| Semantics ContextVar/header mappings | `open upstream PR`: [GigaChat SDK #118](https://github.com/ai-forever/gigachat/pull/118) | Документация mappings, lifecycle и границы tracing доступна для review | PR не смержен и пока не имеет maintainer review |
| Явный 409 для используемого RAG embedding | `open upstream PR`: [Giga Agent #131](https://github.com/ai-forever/giga_agent/pull/131) | Failure-path реализация и 21 targeted test доступны для review | PR не смержен и пока не имеет maintainer review |
| Per-attempt timeout внутри общего retry deadline | `open upstream PR`: [Yandex AI Studio SDK #235](https://github.com/yandex-cloud/yandex-ai-studio-sdk/pull/235) | Backward-compatible API и 233 локальных теста доступны для review | PR не смержен; workflow ожидает одобрения maintainer |

Последняя ручная проверка статусов: 15 июля 2026 года. Числа тестов и статусы PR следует сверять по связанным страницам перед внешним использованием.
