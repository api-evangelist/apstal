# Apstal

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

AI-first website analytics and visitor tracking platform that replaces traditional dashboards with a natural-language chatbot interface, offering conversational analytics, cookieless tracking, session replays, heatmaps, funnels, error tracking, Core Web Vitals and AI-agent traffic detection. Apstal is agent-native by design: its primary programmatic surface is a hosted MCP server at https://apstal.com/api/mcp (JSON-RPC 2.0 over Streamable HTTP, protocol 2025-06-18) whose tools/list is answerable anonymously, backed by a documented REST ingestion and stats API, a WebSocket real-time stream, an SSE natural-language query endpoint, an A2A agent card, two provider-authored Agent Skills, an llms.txt, OAuth 2.0 authorization-server and protected-resource metadata, and an MCP server card. The company is based in Poland and publishes a GDPR Data Processing Agreement.

**Areas:** Analytics · Web Analytics · Privacy · Session Replay · Heatmaps · MCP · Agent-Native · Cookieless · llms-txt · BigQuery · GDPR · A2A

## Apstal on APIs.io

Everything profiled for Apstal is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/apstal/](https://apis.io/providers/apstal/)** — or go straight to one of the APIs or properties below.

### APIs (2)

- [Apstal MCP Server](https://apis.io/apis/apstal/apstal-mcp-server/) — Hosted MCP server exposing Apstal analytics via JSON-RPC 2.0 over Streamable HTTP. Public tools (login, register, server_info) and authenticated tools…
- [Apstal Analytics API](https://apis.io/apis/apstal/apstal-analytics-api/) — Documented REST surface for programmatic access to Apstal analytics: POST /api/v1/m for batched event ingestion (max 100 events per request), POST…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Apstal Realtime Events](https://apis.io/asyncapis/apstal/apstal-realtime-events/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [apstal-analytics](https://apis.io/servers/apstal/apstal-analytics/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Apstal Authentication](https://apis.io/security/apstal/apstal-authentication/)
- [Apstal Domain Security](https://apis.io/security/apstal/apstal-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Apstal Scopes](https://apis.io/scopes/apstal/apstal-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Apstal Plans Pricing](https://apis.io/plans/apstal/apstal-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Apstal Rate Limits](https://apis.io/rate-limits/apstal/apstal-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.apstal.com/)
- [Documentation](https://apstal.com/docs)
- [Getting started](https://apstal.com/docs/getting-started)
- [API reference](https://apstal.com/docs/api)
- [Pricing](https://apstal.com/pricing)
- [Sign up](https://apstal.com/login)
- [Support](https://apstal.com/contact)
- [Blog](https://apstal.com/blog)
- [Compliance](https://apstal.com/dpa)
- [Terms of service](https://apstal.com/terms)
- [Privacy policy](https://apstal.com/privacy)
- [GitHub](https://github.com/apstal)
- [Status](https://status.apstal.com)

## API Evangelist rating

**Kin Score 56.5** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 70.0 |
| Contract quality | 39.0 |
| Contract governance | 18.2 |
| Operational transparency | 42.1 |
| Developer ergonomics | 71.4 |
| Access clarity | 71.1 |

**Agent readiness 38.8** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | flavored (partial credit) |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 39.2** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/apstal/](https://apis.io/providers/apstal/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Apstal: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/apstal/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
