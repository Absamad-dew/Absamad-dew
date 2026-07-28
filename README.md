<p align="center">
  <a href="https://github.com/Absamad-dew/chronofield-investor-materials">
    <img src="https://raw.githubusercontent.com/Absamad-dew/chronofield-investor-materials/main/chronofield-banner.png" alt="ChronoField — exact video and storage compression" width="100%">
  </a>
</p>

<h1 align="center">Absamad Manturov</h1>

<p align="center">
  <strong>Founder of ChronoField</strong><br>
  Building strict-lossless video compression for storage- and compute-heavy infrastructure.
</p>

<p align="center">
  <a href="https://github.com/Absamad-dew/chronofield-investor-materials"><strong>ChronoField investor overview →</strong></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/Absamad-dew/chronofield-investor-materials/blob/main/ChronoField-safe-investor-deck.pdf"><strong>Investor deck →</strong></a>
</p>

---

## ChronoField

ChronoField is an early-stage codec R&D project focused on exact reconstruction, materially smaller storage footprints, and practical decode performance.

Current internal Full-HD benchmark:

| Profile | Compressed size vs. strict-lossless AV1 | Encode speed vs. strict-lossless AV1 |
| --- | ---: | ---: |
| **Realtime** | **48.20% fewer bytes** | **22.59× faster** |
| **Archive** | **55.25% fewer bytes** | **1.43× faster** |

- **900 Full-HD frames** from two real 1080p sources;
- exact RGB reconstruction for every decoded frame;
- six measured profiles beat the measured AV1 baseline on both size and encode speed;
- **461/461 native tests** passing.

> Results are internal and corpus-specific. They have not yet been independently validated and are not presented as a universal performance claim.

## Current objective

Turn the internal result into independently reproduced infrastructure:

1. controlled third-party benchmarking on independently selected content and hardware;
2. broader reproducible codec comparisons;
3. server-grade Linux optimization;
4. early validation partnerships in media, archival, AI-dataset, and exact-source workflows.

I am open to conversations with early-stage investors, technical validation partners, and infrastructure teams with a real lossless-video cost problem.

## Selected engineering work

- [ChronoField investor materials](https://github.com/Absamad-dew/chronofield-investor-materials) — non-confidential project overview and safe deck.
- [ruagent-compat](https://github.com/Absamad-dew/ruagent-compat) — provider-neutral executable contracts for reliable tool-using agents.
- [ru-hardness-30](https://github.com/Absamad-dew/ru-hardness-30) — deterministic Russian LLM hardness harness with reproducible baselines.
- [agentic-service-desk-pilot](https://github.com/Absamad-dew/agentic-service-desk-pilot) — human-gated agent workflow with idempotency and audit traces.

## Contact

[Email](mailto:absamad.manturov@gmail.com) · [Telegram](https://t.me/Absamad_m)

Moscow, Russia · open to relocation.

<sub>ChronoField source code, binaries, formulas, dictionaries, bitstream grammar, benchmark corpus, internal architecture, and protected implementation mechanics are not published.</sub>
