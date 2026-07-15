# Проектные AI / Python услуги

Я не продаю «внедрение нейросети» без проверяемого результата. Первый этап — ограниченный платный пилот: заранее фиксируются входные данные, baseline, критерии приёмки, human gate и stop rule. На выходе заказчик получает воспроизводимый результат либо аргументированный `no-go`.

Цены ниже — стартовые гипотезы до первых трёх оплаченных проектов, а не подтверждённая выручка.

## Быстрый выбор

| Задача | Стартовый пакет | Цена и срок | Что нужно прислать |
|---|---|---:|---|
| Понять, стоит ли автоматизировать один процесс | AI / Automation Preflight | 19 500 ₽ · 2 дня | Описание процесса, ограничения, 3–5 обезличенных примеров |
| Сверить разные прайсы и отделить неоднозначные строки | Диагностический пилот сверки прайсов | 39 000 ₽ · 5 дней | До трёх плоских CSV/XLSX, до 300 строк, один каталог |
| Найти нестабильность AI-агента до production | Agent Reliability Preflight | 29 000 ₽ · 3 дня + API | Одна версия агента, тестовый контур и 20 согласованных сценариев |

[Подробные критерии приёмки](ACCEPTANCE_BRIEFS_RU.md) · [Реестр доказательств и ограничений](EVIDENCE.md)

## 1. AI / Automation Preflight одного процесса

**19 500 ₽ · 2 рабочих дня**

Результат: AS-IS/TO-BE, до пяти узких мест, матрица `эффект × данные × риск`, три pilot charter и roadmap. Приёмка требует KPI, baseline, human gate и stop rule для каждой пилотной гипотезы.

Не входит: разработка, production-доступ, интеграции и обещание ROI.

Proof: [план исследования AI в закупках](Absamad_Manturov_Procurement_AI_Research_Plan.pdf) · [system-analysis case](https://github.com/Absamad-dew/price-intelligence-demo/blob/main/docs/system-analysis-case.md)

## 2. Диагностический пилот сверки прайсов

**39 000 ₽ · 5 рабочих дней**

Scope: до трёх плоских CSV/XLSX, до 300 строк, один каталог и одна валюта. Результат: нормализация, лучшие сопоставимые цены, review queue, import manifest, quality metrics, Excel-отчёт и письменный `go/no-go`.

Не входит: PDF, Google Sheets, PostgreSQL, API, UI и гарантированный accuracy.

Proof: [price-intelligence-demo v0.1.1](https://github.com/Absamad-dew/price-intelligence-demo/releases/tag/v0.1.1) · [quality metrics](https://github.com/Absamad-dew/price-intelligence-demo/blob/main/output/quality_metrics.json)

## 3. Agent Reliability Preflight

**29 000 ₽ · 3 рабочих дня** + фактические API/cloud-расходы

Scope: одна версия агента, один тестовый контур, 20 сценариев × 3 повтора. Результат: versioned cases, до 60 raw traces, JSON/Markdown/JUnit, failure taxonomy и список исправлений.

Не входит: pentest, сертификация безопасности, production side effects или гарантия безопасности модели.

Proof: [ru-agent-eval-kit v0.1.1](https://github.com/Absamad-dew/ru-agent-eval-kit/releases/tag/v0.1.1) · [demo comparison](https://github.com/Absamad-dew/ru-agent-eval-kit/blob/main/results/demo/comparison.json)

## 4. Structured Output & Tool Contract Hardening

**49 000 ₽ · 5 рабочих дней**

Scope: один Python-репозиторий, до трёх tools или один structured-output workflow. Результат: JSON Schemas, validation boundary, permission gate, duplicate-call policy, rollback/error contract, provenance trace и минимум 20 тестов.

Не входит: миграция фреймворка, production deployment, SLA и неограниченное число провайдеров.

Proof: [ruagent-compat v0.2.0](https://github.com/Absamad-dew/ruagent-compat/releases/tag/v0.2.0) · открытые [GigaChat PR #117](https://github.com/ai-forever/gigachat/pull/117) и [Giga Agent PR #131](https://github.com/ai-forever/giga_agent/pull/131)

## 5. Research-to-Pilot Pack

**32 000 ₽ · 5 рабочих дней**

Результат: 10–15 первичных источников, карта 8–12 зон процесса, сравнительная матрица, три pilot charter, risk/TCO register, roadmap и 45-минутная защита.

Не входит: интервью, юридическое заключение, финансовый аудит и гарантированная экономия.

Proof: [8-week procurement plan](Absamad_Manturov_Procurement_AI_Research_Plan.pdf) · [system-analysis case](https://github.com/Absamad-dew/price-intelligence-demo/blob/main/docs/system-analysis-case.md)

## Общие условия

- 50% предоплата, остаток после приёмки;
- цена фиксируется после просмотра обезличенного образца данных;
- один консолидированный раунд исправлений включён;
- изменение числа файлов, процессов, tools или интеграций — новый scope;
- API, облако, платные сервисы и налоги не входят в цену;
- секреты и необезличенные данные не принимаются в переписке;
- production security testing выполняется только в письменно разрешённом scope.

Контакты: Telegram [@Absamad_m](https://t.me/Absamad_m) · Gmail [absamad.manturov@gmail.com](mailto:absamad.manturov@gmail.com)
