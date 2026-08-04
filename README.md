# Hong Kong University of Science and Technology (hkust)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The Hong Kong University of Science and Technology (HKUST) is a public research university in Clear Water Bay, Hong Kong SAR, ranked #82 in the QS World University Rankings 2025. This repository catalogs HKUST's public developer and API footprint as an [APIs.json](http://apisjson.org/) profile for the API Evangelist network.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/hkust/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=hkust-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Data, Hong Kong, China

## APIs

- **HKUST API Portal & Gateway** — Centralized Azure API Management developer portal and API Gateway run by HKUST ITSO; departments publish application APIs, developers discover and sign up for keys. Docs: https://hkust.developer.azure-api.net/ — Service overview: https://itso.hkust.edu.hk/services/it-infrastructure/api-gateway-api-portal
- **DataSpace@HKUST Research Data Repository API** — Institutional research data repository on Dataverse 6.1 with the standard Dataverse Native REST API and DOI persistent identifiers. Site: https://dataspace.hkust.edu.hk/ — Native API docs: https://guides.dataverse.org/en/latest/api/native-api.html
- **HKUST Open Data Platform** — Secure central smart-campus data repository built on the Elastic Stack. Docs: https://itso.hkust.edu.hk/services/it-infrastructure/smart-campus-infrastructure/open-data-platform

## Plans

- [plans/hkust-plans-pricing.yml](plans/hkust-plans-pricing.yml)

## Rate Limits

- [rate-limits/hkust-rate-limits.yml](rate-limits/hkust-rate-limits.yml)

## FinOps

- [finops/hkust-finops.yml](finops/hkust-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.ust.hk/
- Developer Portal: https://hkust.developer.azure-api.net/
- LinkedIn: https://hk.linkedin.com/school/hkust/

## Notes

- All URLs were probed during cataloging. The developer portal, ITSO service pages, DataSpace, and the official website returned HTTP 200. DataSpace@HKUST returns a live Dataverse `/api/info/version` response (version 6.1), confirming an operational Native API.
- The DataSpace OAI-PMH endpoint (`/oai?verb=Identify`) returned HTTP 503 at the time of review and was not confirmed as functioning.
- The HKUST API Portal and API Gateway are primarily for HKUST-affiliated departments and developers; API access requires sign-up and a data access request rather than open self-service.
- There is no single official institutional "HKUST" GitHub organization; numerous departmental and research-lab GitHub orgs exist (e.g., HKUST-Aerial-Robotics), so no organization-wide GitHub property is asserted in the common block.
- No fabricated endpoints are included; only APIs and properties confirmed via public sources are listed.

## Maintainers

- Kin Lane — kin@apievangelist.com
