# Phind (phind)

Phind was an AI answer engine and coding assistant built for developers, offering conversational, multi-step technical search on the web and through a VS Code extension. Founded in 2022 by Michael Royzen and Justin Wei (Y Combinator S22, San Francisco), Phind trained its own code models and briefly held the top-ranked open-source coding model on Hugging Face.

**Access model — read this first:** Phind was a subscription **consumer product**, not a developer API platform. The phind.com service **never shipped an official public or partner developer API** — no documented base URL, authentication, OpenAPI, REST reference, SSE, or WebSocket surface. The only genuinely public developer artifacts are Phind's **open-weight models on Hugging Face** ([huggingface.co/Phind](https://huggingface.co/Phind)). Community "Phind API" projects on GitHub and RapidAPI are **unofficial reverse-engineered wrappers** of the website's internal endpoints and are not represented here as official.

**Status: discontinued.** Phind shut down on **January 16, 2026**. Pro subscribers received prorated refunds and could export chat history through January 30, 2026 before servers were wiped. This entry is a **historical record**; the API surfaces below are modeled (`endpointsModeled: true`), not officially documented.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/phind/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/phind/refs/heads/main/apis.yml)

## Tags

- AI Coding Assistant
- AI Search
- Developer Tools
- LLM
- Answer Engine
- Open Weights
- Discontinued

## Timestamps

- **Created:** 2026-07-11
- **Modified:** 2026-07-11

## APIs

> Both entries are marked `endpointsModeled` — they are listed for discovery only. Phind published no official API reference for either.

### Phind AI Answer Engine

Conceptual (modeled) surface for Phind's AI answer engine — the developer-focused conversational search that powered phind.com and the VS Code extension. Phind never published an official public or partner developer API for this service; it was consumed only through the Phind web UI and editor extension. No official base URL, authentication, OpenAPI, or endpoint reference was ever documented. Any third-party "Phind API" on GitHub or RapidAPI is an unofficial reverse-engineered wrapper and is not represented here as official.

- **Human URL:** [https://www.phind.com](https://www.phind.com)

#### Tags

- AI Coding Assistant
- AI Search
- Answer Engine
- LLM

#### Properties

- [Website](https://www.phind.com)

### Phind Open-Weight Models

Phind's genuinely public developer artifacts — open-weight models published to the Phind organization on Hugging Face. These include the code models Phind-CodeLlama-34B-v1, Phind-CodeLlama-34B-v2, and Phind-CodeLlama-34B-Python-v1 (fine-tunes of Meta's Code Llama 34B, released August 2023 and briefly the top-ranked open-source coding models on HumanEval), plus the later Phind-70B, Phind-SVG, and Magic-Edit. These are downloadable model weights hosted on Hugging Face, **not** a hosted HTTP inference API operated by Phind; they can be self-hosted or run through third-party inference stacks.

- **Human URL:** [https://huggingface.co/Phind](https://huggingface.co/Phind)

#### Tags

- Open Weights
- Models
- Code Models
- LLM

#### Properties

- [Documentation](https://huggingface.co/Phind)
- [Source Code](https://huggingface.co/Phind/Phind-CodeLlama-34B-v2)

## Common Properties

- [Plans](plans/phind-plans-pricing.yml)
- [LinkedIn](https://www.linkedin.com/company/phind)
- [Website](https://www.phind.com)
- [Hugging Face](https://huggingface.co/Phind)
- [CrunchBase](https://www.crunchbase.com/organization/phind)

## Plans

Phind was billed per-seat (subscription), not per-token/per-call — it had no API pricing because it had no public API. Historical, pre-shutdown consumer tiers (approximate, no longer purchasable):

- **Free** — limited daily uses, default models.
- **Plus** — ~$17/mo; frontier models, higher daily limits.
- **Pro** — ~$20/mo (~$17/mo billed annually); core developer tier.
- **Pro Max** — ~$70/mo; heavy daily users.
- **Enterprise** — ~$40/user/mo; team management, 99.9% uptime SLA, priority support.

See [plans/phind-plans-pricing.yml](plans/phind-plans-pricing.yml). The open-weight models on Hugging Face remain available under their own model licenses, independent of these plans.

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
