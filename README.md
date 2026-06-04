# Massey University (massey)

Massey University is a public research university in New Zealand (Palmerston North, Wellington, and Auckland), ranked #239 in the QS World University Rankings 2025. Its public, machine-readable footprint is centered on Massey Research Online (MRO), a DSpace 8.3 institutional repository exposing standards-based OAI-PMH and REST interfaces. This repository catalogs that footprint as an APIs.json profile.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/massey/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=massey-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Access, Institutional Repository, New Zealand

## APIs

- **Massey Research Online OAI-PMH** — OAI-PMH 2.0 metadata-harvesting interface for the MRO DSpace repository. Docs: https://mro.massey.ac.nz/ — Base URL: https://mro.massey.ac.nz/server/oai/request
- **Massey Research Online DSpace REST API** — HAL/JSON REST API (DSpace 8.3) for repository communities, collections, items, and bitstreams. Docs: https://mro.massey.ac.nz/ — Base URL: https://mro.massey.ac.nz/server/api

## Plans / Rate Limits / FinOps

- Plans: [plans/massey-plans-pricing.yml](plans/massey-plans-pricing.yml)
- Rate Limits: [rate-limits/massey-rate-limits.yml](rate-limits/massey-rate-limits.yml)
- FinOps: [finops/massey-finops.yml](finops/massey-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.massey.ac.nz/
- LinkedIn: https://www.linkedin.com/school/massey-university/
- Review: [review.yml](review.yml)

## Notes

All endpoints were probed live on 2026-06-03. The MRO OAI-PMH and DSpace REST API endpoints returned valid responses (HTTP 200). The legacy M-API WebService (https://www.massey.ac.nz/api/v1_2/) loads but states the service is no longer available; its historical access was gated behind an ITS Service Desk developer-key request and is therefore not cataloged as an active API. The `MasseyUniversity` GitHub organization exists but has no public repositories, so it is not listed as a developer resource. No endpoints or documentation were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
