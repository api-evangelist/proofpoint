# Proofpoint

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

Proofpoint is an enterprise cybersecurity company focused on human-centric security — email and collaboration security, data loss prevention, insider threat management, digital communications governance, security awareness training and threat intelligence. Its public API surface is substantial but gateway-shaped rather than developer-portal-shaped: the Targeted Attack Protection (TAP) v2 API, the Threat Protection dashboard Reports API, the Emerging Threats (ET) Intelligence Query API, the ZenGuide / Security Awareness Training Results API, the Secure Email Relay email submission API, the Proofpoint Essentials SIEM API and the Proofpoint on Demand (PoD) log stream. Every one of them is documented in public HTML and every one of them is credential-gated at runtime; Proofpoint publishes no OpenAPI, AsyncAPI, GraphQL or MCP contract for any of them.

**Areas:** Security · Cybersecurity · Email Security · Threat Intelligence · Data Loss Prevention · Security Awareness Training · Insider Threat · SIEM · Compliance · Email

## Proofpoint on APIs.io

Everything profiled for Proofpoint is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/proofpoint/](https://apis.io/providers/proofpoint/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [Proofpoint Targeted Attack Protection (TAP) API v2](https://apis.io/apis/proofpoint/proofpoint-tap/) — The TAP v2 API exposes the Threat Insight Dashboard to machines: SIEM event download (blocked/permitted clicks, blocked/delivered messages, issues, all),…
- [Proofpoint Threat Protection Dashboard Reports API v1](https://apis.io/apis/proofpoint/proofpoint-threat-protection-reports/) — The Dashboard Reports API returns the same executive-summary, effectiveness, people, organization and threat-landscape report cards the Threat Protection…
- [Emerging Threats (ET) Intelligence Query API v1](https://apis.io/apis/proofpoint/proofpoint-et-intelligence/) — The ET Intelligence Query API is Proofpoint's threat-intelligence lookup service, reached at api.emergingthreats.net. Thirty-six documented GET endpoints…
- [Proofpoint Security Awareness Training (ZenGuide) Results API](https://apis.io/apis/proofpoint/proofpoint-psat-results/) — The Results API exports Security Awareness Training outcomes for business-intelligence and LMS integration: CyberStrength knowledge assessments, PhishAlarm…
- [Proofpoint Secure Email Relay (SER) Email Submission API](https://apis.io/apis/proofpoint/proofpoint-secure-email-relay/) — Secure Email Relay lets applications send authenticated transactional mail through Proofpoint rather than through an unmanaged relay, which is what makes a…
- [Proofpoint Essentials Threat (SIEM) API](https://apis.io/apis/proofpoint/proofpoint-essentials-siem/) — Proofpoint Essentials — the SMB and MSP edition of the platform — exposes the same /v2/siem shape as TAP on its own regional hosts, returning blocked and…
- [Proofpoint on Demand (PoD) Log API](https://apis.io/apis/proofpoint/proofpoint-pod-log/) — The PoD Log API is Proofpoint's streaming surface rather than a request/response one: a client opens a WebSocket to logstream.proofpoint.com and subscribes…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Proofpoint Authentication](https://apis.io/security/proofpoint/proofpoint-authentication/)
- [Proofpoint Domain Security](https://apis.io/security/proofpoint/proofpoint-domain-security/)
- [Proofpoint Trust Center](https://apis.io/security/proofpoint/proofpoint-trust-center/)
- [Proofpoint Vulnerability Disclosure](https://apis.io/security/proofpoint/proofpoint-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Proofpoint Plans Pricing](https://apis.io/plans/proofpoint/proofpoint-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Proofpoint Rate Limits](https://apis.io/rate-limits/proofpoint/proofpoint-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.proofpoint.com/us)
- [Documentation](https://help.proofpoint.com/Threat_Insight_Dashboard/API_Documentation)
- [API reference](https://apidocs.emergingthreats.net/)
- [Support](https://www.proofpoint.com/us/support-services)
- [Blog](https://www.proofpoint.com/us/blog)
- [Security](https://www.proofpoint.com/us/security/vulnerability-disclosure-policy)
- [Compliance](https://www.proofpoint.com/us/legal/trust/product-certifications)
- [Terms of service](https://www.proofpoint.com/us/legal/api-terms-of-use)
- [Privacy policy](https://www.proofpoint.com/us/legal/privacy-policy)
- [GitHub](https://github.com/pfptcommunity)

## API Evangelist rating

**Kin Score 40.1** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 0.0 |
| Contract governance | 18.2 |
| Operational transparency | 44.7 |
| Developer ergonomics | 59.5 |
| Access clarity | 50.0 |

**Agent readiness 7.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
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
| Operation Distinctiveness | na |

**Regulatory alignment 35.3** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/proofpoint/](https://apis.io/providers/proofpoint/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Proofpoint: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/proofpoint/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
