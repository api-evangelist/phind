# Phind (phind)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
