# UrlChart

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

UrlChart provides a Chart Image API compatible with Google Image Charts URLs. It renders legacy chart URLs into PNG images via a simple GET request, supporting multi‑axis charts, thousand‑separator formatting, gradient fills and detailed compatibility reports. The service offers a free tier with 1,000 unique renders per month and paid plans for higher limits, all without requiring an API key for basic use. It aims to help developers migrate away from deprecated Google Image Charts by offering a drop‑in replacement that preserves existing URL parameters.

**Areas:** charts · image-generation · png · legacy-migration · api

## UrlChart on APIs.io

Everything profiled for UrlChart is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/urlchart/](https://apis.io/providers/urlchart/)** — or go straight to one of the APIs or properties below.

### APIs (2)

- [UrlChart Chart Image API](https://apis.io/apis/urlchart/urlchart-chart-image-api/) — Render a chart image (PNG) from a GET request using the legacy Google Image Charts parameter set (cht, chs, chd, chxt, chco and related parameters).…
- [UrlChart API](https://apis.io/apis/urlchart/urlchart-api/) — UrlChart API as documented publicly: 4 operations. Contract generated from the documentation by API Evangelist (2026-11-25); not the provider's own document.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (5)

The data models the API reads and writes.

- [GetApiMeResponse](https://apis.io/schemas/urlchart/urlchart-get-api-me-response/)
- [GetApiUsageResponse](https://apis.io/schemas/urlchart/urlchart-get-api-usage-response/)
- [PostChartRequest](https://apis.io/schemas/urlchart/urlchart-post-chart-request/)
- [PostChartResponse](https://apis.io/schemas/urlchart/urlchart-post-chart-response/)
- [PostGchartResponse](https://apis.io/schemas/urlchart/urlchart-post-gchart-response/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Urlchart Context](https://apis.io/jsonld/urlchart/urlchart-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [UrlChart API Rules](https://apis.io/rules/urlchart/urlchart-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [UrlChart Domain Security](https://apis.io/security/urlchart/urlchart-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [UrlChart Plans Pricing](https://apis.io/plans/urlchart/urlchart-plans-pricing/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://urlchart.com)
- [Documentation](https://urlchart.com/apis.json)
- [Pricing](https://urlchart.com/pricing)
- [Support](https://urlchart.com/support)
- [Terms of service](https://urlchart.com/terms)
- [Privacy policy](https://urlchart.com/privacy)

## API Evangelist rating

**Kin Score 39.0** — thin · rubric 0.28.0 · scored 2026-11-25

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 54.0 |
| Contract governance | 79.1 |
| Operational transparency | 0.0 |
| Developer ergonomics | 14.3 |
| Access clarity | 40.9 |

**Agent readiness 22.8** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |
| MCP Tool Quality | na |

**Regulatory alignment 12.7** — AI & Biometrics

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/urlchart/](https://apis.io/providers/urlchart/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for UrlChart: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/urlchart/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
