# Hong Kong University of Science and Technology (hkust)

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
