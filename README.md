# Beam Checkout

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

Beam is a Thailand-focused payments platform that lets businesses accept payments across in-person and online channels. Its products include Beam Checkout (online payments for social media, websites, and apps via hosted payment links and a Charges API), Beam Bolt (an in-person payment device), and Beam Bridge (embedded payments for partner platforms). Beam supports cards, e-wallets, QR PromptPay, installments, and Alipay+, with card authorization/capture, refunds, tokenization, 3DS, and CIT/MIT recurring flows. The v1 REST API uses HTTP Basic auth (merchantId:apiKey), idempotency keys, HMAC-signed webhooks, and a playground sandbox. Beam states it is PCI DSS compliant and compliant with Bank of Thailand regulations. Backed by Peak XV, Partech, and SeaX Ventures.

**Areas:** Company · Financial Services · Payments · Checkout · Card Payments · Webhook · Thailand · Fintech

## Beam Checkout on APIs.io

Everything profiled for Beam Checkout is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/beam-checkout/](https://apis.io/providers/beam-checkout/)** — or go straight to one of the APIs or properties below.

### APIs (1)

- [Beam API v1](https://apis.io/apis/beam-checkout/beam-api-v1/) — Beam's v1 REST payments API — payment links, charges, refunds, transactions, card authorizations (auth/capture/cancel), network tokenization, and Beam Bolt…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Beam Checkout Webhooks](https://apis.io/asyncapis/beam-checkout/beam-checkout-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [beam-checkout](https://apis.io/servers/beam-checkout/beam-checkout/)

#### Collections (1)

Postman and Open Collection request collections.

- [[For merchant test] Playground (SANDBOX) version 1.14.0](https://apis.io/collections/beam-checkout/postman-beam-checkout-playground/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Beam Checkout Authentication](https://apis.io/security/beam-checkout/beam-checkout-authentication/)
- [Beam Checkout Domain Security](https://apis.io/security/beam-checkout/beam-checkout-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.beamcheckout.com/)
- [Documentation](https://docs.beamcheckout.com/)
- [Getting started](https://docs.beamcheckout.com/get-started/quickstart)
- [API reference](https://docs.beamcheckout.com/v1/api)
- [Pricing](https://www.beamcheckout.com/pricing)
- [Sign up](https://www.beamcheckout.com/getstarted)
- [Support](https://guides.beamcheckout.com/hc/en)
- [Terms of service](https://www.beamcheckout.com/tncs)
- [Privacy policy](https://www.beamcheckout.com/privacy)
- [Status](https://status.beamcheckout.com)

## API Evangelist rating

**Kin Score 51.1** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 39.0 |
| Contract governance | 18.2 |
| Operational transparency | 39.5 |
| Developer ergonomics | 66.2 |
| Access clarity | 52.6 |

**Agent readiness 25.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | documented (partial credit) |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | yes |
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
| Operation Distinctiveness | na |

**Regulatory alignment 39.3** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/beam-checkout/](https://apis.io/providers/beam-checkout/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Beam Checkout: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/beam-checkout/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
