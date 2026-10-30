# Nacha

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

Nacha (formerly the National Automated Clearing House Association) is the nonprofit, member-governed steward of the ACH Network, the batch-based account-to-account payment rail that moves consumer and business direct deposits, direct payments, bill pay, and B2B transfers across the United States — more than 30 billion payments and over $80 trillion in value annually. Nacha writes and enforces the Nacha Operating Rules that bind the network's participating depository financial institutions, but it is not itself an ACH Operator (the Federal Reserve and The Clearing House clear and settle the files). Nacha is documentation- and rulebook-first rather than a self-serve PSP: it does not operate a public production payments API of its own. Its API posture is delivered through Afinis Interoperability Standards, the Nacha-stewarded group that publishes royalty-free, standardized financial-services API specifications (payment initiation, account validation, transaction status, returns reporting, and directory services) as Swagger/OpenAPI documents on SwaggerHub, and through Phixius, its payment-information exchange platform. Its home market is the United States.

**Areas:** Payments · United States · ACH · Account-to-Account · Real-Time Payments · Account Validation · Payment Rails · ISO 20022 · Standards · Afinis

## Nacha on APIs.io

Everything profiled for Nacha is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/nacha/](https://apis.io/providers/nacha/)** — or go straight to one of the APIs or properties below.

### APIs (19)

- [Nacha Account Validation API](https://apis.io/apis/nacha/nacha-account-validation-api/) — The Account Validation API from Nacha — 1 operation(s) for account validation.
- [Nacha Accounts API](https://apis.io/apis/nacha/nacha-accounts-api/) — The Accounts API from Nacha — 4 operation(s) for accounts.
- [Nacha ACH Payments API](https://apis.io/apis/nacha/nacha-ach-payments-api/) — The ACH Payments API from Nacha — 2 operation(s) for ach payments.
- [Nacha ACH Transaction Status API](https://apis.io/apis/nacha/nacha-ach-transaction-status-api/) — The ACH Transaction Status API from Nacha — 4 operation(s) for ach transaction status.
- [Nacha Authorize to Pay API](https://apis.io/apis/nacha/nacha-authorize-to-pay-api/) — The Authorize to Pay API from Nacha — 1 operation(s) for authorize to pay.
- [Nacha Banks API](https://apis.io/apis/nacha/nacha-banks-api/) — The Banks API from Nacha — 1 operation(s) for banks.
- [Nacha Expand Bank Contact V2 API](https://apis.io/apis/nacha/nacha-expand-bank-contact-v2-api/) — The Expand Bank Contact V2 API from Nacha — 1 operation(s) for expand bank contact v2.
- [Nacha Get Corporate Account Balances API](https://apis.io/apis/nacha/nacha-get-corporate-account-balances-api/) — The Get Corporate Account Balances API from Nacha — 1 operation(s) for get corporate account balances.
- [Nacha Get Corporate Transaction History API](https://apis.io/apis/nacha/nacha-get-corporate-transaction-history-api/) — The Get Corporate Transaction History API from Nacha — 2 operation(s) for get corporate transaction history.
- [Nacha Get Participants Profile API](https://apis.io/apis/nacha/nacha-get-participants-profile-api/) — The Get Participants Profile API from Nacha — 1 operation(s) for get participants profile.
- [Nacha Initiate Payment API](https://apis.io/apis/nacha/nacha-initiate-payment-api/) — The Initiate Payment API from Nacha — 1 operation(s) for initiate payment.
- [Nacha Instant Payment API](https://apis.io/apis/nacha/nacha-instant-payment-api/) — The Instant Payment API from Nacha — 1 operation(s) for instant payment.
- [Nacha Instant Payment Transfer API](https://apis.io/apis/nacha/nacha-instant-payment-transfer-api/) — The Instant Payment Transfer API from Nacha — 1 operation(s) for instant payment transfer.
- [Nacha International ACH Remittance (IAR) API](https://apis.io/apis/nacha/nacha-international-ach-remittance-iar-api/) — The International ACH Remittance (IAR) API from Nacha — 2 operation(s) for international ach remittance (iar).
- [Nacha Proof of Authorization API](https://apis.io/apis/nacha/nacha-proof-of-authorization-api/) — The Proof of Authorization API from Nacha — 1 operation(s) for proof of authorization.
- [Nacha Reporting ACH Return Payments API](https://apis.io/apis/nacha/nacha-reporting-ach-return-payments-api/) — The Reporting ACH Return Payments API from Nacha — 1 operation(s) for reporting ach return payments.
- [Nacha Route Billing Information API](https://apis.io/apis/nacha/nacha-route-billing-information-api/) — The Route Billing Information API from Nacha — 1 operation(s) for route billing information.
- [Nacha Wire Transfer API](https://apis.io/apis/nacha/nacha-wire-transfer-api/) — The Wire Transfer API from Nacha — 2 operation(s) for wire transfer.
- [Nacha Written Statement of Unauthorized Debit (WSUD) API](https://apis.io/apis/nacha/nacha-written-statement-of-unauthorized-debit-wsud-api/) — The Written Statement of Unauthorized Debit (WSUD) API from Nacha — 1 operation(s) for written statement of unauthorized debit (wsud).

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [nacha-afinis](https://apis.io/servers/nacha/nacha-afinis/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Nacha Agentic Access](https://apis.io/agentic-access/nacha/nacha-agentic-access/)

#### Collections (24)

Postman and Open Collection request collections.

- [Account Validation APIs](https://apis.io/collections/nacha/open-nacha-account-validation/)
- [Account Validation Plus Ownership API](https://apis.io/collections/nacha/open-nacha-account-validation-plus-name/)
- [AV + Name + Return](https://apis.io/collections/nacha/open-nacha-account-validation-plus-name-ret/)
- [Debit Authorizations](https://apis.io/collections/nacha/open-nacha-authorize-to-pay/)
- [Bank Contact V2](https://apis.io/collections/nacha/open-nacha-bank-contact-v2/)
- [Bank Contacts APIs](https://apis.io/collections/nacha/open-nacha-bank-contacts/)
- [Get Corporate Account Balances API](https://apis.io/collections/nacha/open-nacha-corporate-account-balances/)
- [Get Transaction Detail API](https://apis.io/collections/nacha/open-nacha-corporate-transaction-detail/)
- [Get Corporate Transaction History API](https://apis.io/collections/nacha/open-nacha-corporate-transaction-history/)
- [Get Wire Status](https://apis.io/collections/nacha/open-nacha-get-wire-status/)
- [IAR_API](https://apis.io/collections/nacha/open-nacha-iar/)
- [IAR Plus API](https://apis.io/collections/nacha/open-nacha-iar-plus/)
- [Initiate Instant Payment API (IIP)](https://apis.io/collections/nacha/open-nacha-initiate-instant-payment/)
- [Initiate Payment API](https://apis.io/collections/nacha/open-nacha-initiate-payment/)
- [Initiate Payment API](https://apis.io/collections/nacha/open-nacha-initiate-payment-api/)
- [Initiate Wire Payment API](https://apis.io/collections/nacha/open-nacha-initiate-wire-payment/)
- [Instant Payment Transfer (IPT)](https://apis.io/collections/nacha/open-nacha-instant-payment-transfer/)
- [Pay Me API](https://apis.io/collections/nacha/open-nacha-pay-me/)
- [Payee Profile API](https://apis.io/collections/nacha/open-nacha-payee-profile/)
- [Proof of Authorization API](https://apis.io/collections/nacha/open-nacha-proof-of-authorization/)
- [Real Time Billing Account Validation User Story 1](https://apis.io/collections/nacha/open-nacha-realtime-billing-account-validation/)
- [RET (Reporting ACH Return Payments) API](https://apis.io/collections/nacha/open-nacha-ret/)
- [Transaction Status API](https://apis.io/collections/nacha/open-nacha-transaction-status/)
- [Request Copy of Written Statement of Unauthorized Debit (WSUD) API](https://apis.io/collections/nacha/open-nacha-wsud/)

#### Overlays (24)

OpenAPI overlays, including conversational phrasing for each operation.

- [Nacha Account Validation Overlay](https://apis.io/overlays/nacha/nacha-account-validation-overlay/)
- [Nacha Account Validation Plus Name Overlay](https://apis.io/overlays/nacha/nacha-account-validation-plus-name-overlay/)
- [Nacha Account Validation Plus Name Ret Overlay](https://apis.io/overlays/nacha/nacha-account-validation-plus-name-ret-overlay/)
- [Nacha Authorize To Pay Overlay](https://apis.io/overlays/nacha/nacha-authorize-to-pay-overlay/)
- [Nacha Bank Contact V2 Overlay](https://apis.io/overlays/nacha/nacha-bank-contact-v2-overlay/)
- [Nacha Bank Contacts Overlay](https://apis.io/overlays/nacha/nacha-bank-contacts-overlay/)
- [Nacha Corporate Account Balances Overlay](https://apis.io/overlays/nacha/nacha-corporate-account-balances-overlay/)
- [Nacha Corporate Transaction Detail Overlay](https://apis.io/overlays/nacha/nacha-corporate-transaction-detail-overlay/)
- [Nacha Corporate Transaction History Overlay](https://apis.io/overlays/nacha/nacha-corporate-transaction-history-overlay/)
- [Nacha Get Wire Status Overlay](https://apis.io/overlays/nacha/nacha-get-wire-status-overlay/)
- [Nacha Iar Overlay](https://apis.io/overlays/nacha/nacha-iar-overlay/)
- [Nacha Iar Plus Overlay](https://apis.io/overlays/nacha/nacha-iar-plus-overlay/)
- [Nacha Initiate Instant Payment Overlay](https://apis.io/overlays/nacha/nacha-initiate-instant-payment-overlay/)
- [Nacha Initiate Payment Api Overlay](https://apis.io/overlays/nacha/nacha-initiate-payment-api-overlay/)
- [Nacha Initiate Payment Overlay](https://apis.io/overlays/nacha/nacha-initiate-payment-overlay/)
- [Nacha Initiate Wire Payment Overlay](https://apis.io/overlays/nacha/nacha-initiate-wire-payment-overlay/)
- [Nacha Instant Payment Transfer Overlay](https://apis.io/overlays/nacha/nacha-instant-payment-transfer-overlay/)
- [Nacha Pay Me Overlay](https://apis.io/overlays/nacha/nacha-pay-me-overlay/)
- [Nacha Payee Profile Overlay](https://apis.io/overlays/nacha/nacha-payee-profile-overlay/)
- [Nacha Proof Of Authorization Overlay](https://apis.io/overlays/nacha/nacha-proof-of-authorization-overlay/)
- [Nacha Realtime Billing Account Validation Overlay](https://apis.io/overlays/nacha/nacha-realtime-billing-account-validation-overlay/)
- [Nacha Ret Overlay](https://apis.io/overlays/nacha/nacha-ret-overlay/)
- [Nacha Transaction Status Overlay](https://apis.io/overlays/nacha/nacha-transaction-status-overlay/)
- [Nacha Wsud Overlay](https://apis.io/overlays/nacha/nacha-wsud-overlay/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Nacha Authentication](https://apis.io/security/nacha/nacha-authentication/)
- [Nacha Domain Security](https://apis.io/security/nacha/nacha-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.nacha.org/)
- [Documentation](https://www.nacha.org/content/afinis-interoperability-standards)
- [Getting started](https://achdevguide.nacha.org/)
- [API reference](https://www.nacha.org/content/afinis-api-catalog)
- [Blog](https://www.nacha.org/news)
- [Terms of service](https://www.nacha.org/content/legal-information)
- [Privacy policy](https://www.nacha.org/content/privacy-policy)

## API Evangelist rating

**Kin Score 36.1** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 44.5 |
| Contract governance | 4.5 |
| Operational transparency | 0.0 |
| Developer ergonomics | 54.2 |
| Access clarity | 27.6 |

**Agent readiness 26.4** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 25.9** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/nacha/](https://apis.io/providers/nacha/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Nacha: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/nacha/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
