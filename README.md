# Hong Kong University of Science and Technology

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

The Hong Kong University of Science and Technology (HKUST) is a public research university in Clear Water Bay, Hong Kong SAR. Its programmable footprint is real but small and mostly closed. One API on an HKUST host is public and keyless: the Path Advisor campus wayfinding API at pathadvisor.ust.hk, which serves buildings, calibrated floor plans, point-of-interest categories and named map nodes with GeoJSON footprints, CORS-open and with no key. Beyond it, the IT Services Office runs an Azure API Management gateway and portal — live and callable at hkust.azure-api.net, but every product needs an ITSO account, a subscription request and human approval, and the catalog cannot be enumerated anonymously. DataSpace@HKUST is a Dataverse 6.1 instance HKUST self-hosts on its own domain and network, serving 151 published datasets over the upstream Dataverse Native API; its OAI-PMH provider is switched off. The institution's most substantial machine-readable assets are not developer APIs at all: a Shibboleth SAML identity provider published into eduGAIN through the Hong Kong Access Federation, and HKUST Library's Crossref membership under DOI prefix 10.14711, with 14,453 registered records. HKUST publishes no OpenAPI, no changelog, no status page and no security.txt for any of it. A previously catalogued API base URL of api.ust.hk does not exist — HKUST's own authoritative nameservers return NXDOMAIN for that hostname — and has been removed.

**Areas:** University · Higher Education · Education · Research · Hong Kong · China · Research Data · Open Data · Identity Federation · Course Catalog · Library · Smart Campus

## Hong Kong University of Science and Technology on APIs.io

Everything profiled for Hong Kong University of Science and Technology is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/hkust/](https://apis.io/providers/hkust/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [HKUST API Gateway and API Portal](https://apis.io/apis/hkust/api-gateway/) — HKUST's Azure API Management tenant, operated by the IT Services Office. The gateway is live and callable at hkust.azure-api.net and returns the Azure APIM…
- [DataSpace@HKUST Research Data Repository API](https://apis.io/apis/hkust/dataspace/) — The institutional research data repository, running Dataverse 6.1 on Payara. HKUST self-hosts it: dataspace.hkust.edu.hk is on the university's own…
- [HKUST Shibboleth Identity Provider](https://apis.io/apis/hkust/identity-federation/) — HKUST's own SAML 2.0 identity provider, serving machine-readable metadata at idp.ust.hk/idp/shibboleth. Asserts the scopes ust.hk, connect.ust.hk and…
- [HKUST Library Crossref DOI Registration](https://apis.io/apis/hkust/crossref-doi/) — HKUST Library is Crossref member 5801 and owns DOI prefix 10.14711, under which 14,453 records are registered and retrievable through the Crossref REST API…
- [HKUST Open Data Platform](https://apis.io/apis/hkust/open-data-platform/) — Central Elastic Stack repository established by ITSO to collect, search and visualise smart-campus data, including the IoT sensor inventory and sensor…
- [Hong Kong University of Science and Technology Buildings API](https://apis.io/apis/hkust/hkust-buildings-api/) — Campus buildings.
- [Hong Kong University of Science and Technology Floors API](https://apis.io/apis/hkust/hkust-floors-api/) — Floor plans and their map calibration.
- [Hong Kong University of Science and Technology Nodes API](https://apis.io/apis/hkust/hkust-nodes-api/) — Named map features with GeoJSON footprints.
- [Hong Kong University of Science and Technology Tags API](https://apis.io/apis/hkust/hkust-tags-api/) — Point-of-interest categories.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (6)

The data models the API reads and writes.

- [HKUST Path Advisor Building](https://apis.io/schemas/hkust/hkust-path-advisor-building/)
- [HKUST Path Advisor Error](https://apis.io/schemas/hkust/hkust-path-advisor-error/)
- [HKUST Path Advisor Floor](https://apis.io/schemas/hkust/hkust-path-advisor-floor/)
- [HKUST Path Advisor MultiPolygon](https://apis.io/schemas/hkust/hkust-path-advisor-multipolygon/)
- [HKUST Path Advisor Node](https://apis.io/schemas/hkust/hkust-path-advisor-node/)
- [HKUST Path Advisor Tag](https://apis.io/schemas/hkust/hkust-path-advisor-tag/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Hkust Context](https://apis.io/jsonld/hkust/hkust-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Hong Kong University of Science and Technology — path advisor rules](https://apis.io/rules/hkust/hkust-path-advisor-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Hkust Authentication](https://apis.io/security/hkust/hkust-authentication/)
- [Hkust Domain Security](https://apis.io/security/hkust/hkust-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Hkust Scopes](https://apis.io/scopes/hkust/hkust-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Hkust Plans Pricing](https://apis.io/plans/hkust/hkust-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Hkust Rate Limits](https://apis.io/rate-limits/hkust/hkust-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Hkust Finops](https://apis.io/finops/hkust/hkust-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.ust.hk/)
- [Documentation](https://itso.hkust.edu.hk/services/it-infrastructure/api-gateway-api-portal)
- [API reference](https://itso.hkust.edu.hk/services/it-infrastructure/smart-campus-infrastructure/open-data-platform/retrieve-iot-data-api)
- [Support](https://itso.hkust.edu.hk/)
- [Privacy policy](https://dataprivacy.hkust.edu.hk/university-data-privacy-policy-statement/)

## API Evangelist rating

**Kin Score 40.0** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 54.4 |
| Contract governance | 3.8 |
| Operational transparency | 31.6 |
| Developer ergonomics | 42.9 |
| Access clarity | 28.9 |

**Agent readiness 33.6** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 30.4** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/hkust/](https://apis.io/providers/hkust/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Hong Kong University of Science and Technology: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/hkust/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
