# Massey University

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

Massey University (Te Kunenga ki Pūrehuroa) is a public research university in New Zealand with campuses in Palmerston North (Manawatū), Wellington and Albany (Auckland). Its machine-readable footprint is real but small, and it is three different things at once. The university itself operates three callable surfaces: an OAI-PMH 2.0 endpoint and a DSpace 8.3 HAL/JSON REST API on its own host for Massey Research Online / Pātaka Rangahau, and the M-API, a news, events and staff-directory web service documented at www.massey.ac.nz/api/v1/ which is live and answering but API-key gated, self-described as unsupported, and closed to new key applications; the later M-API v1_2 host, api.massey.ac.nz, now states the service is no longer available. It operates two identity surfaces that are stronger than any of its APIs: a Shibboleth SAML 2.0 Identity Provider at idp.massey.ac.nz published through the Tuakiri Federation and eduGAIN, and a Microsoft Entra ID tenant discoverable by domain. And it is registered in three identifier registries - DataCite (as a DataCite New Zealand consortium organization with two repositories), Crossref (two members, three prefixes) and ROR. Everything else that looks like a Massey API is a vendor's: library discovery is EBSCO Discovery Service, opening hours and enquiries run on Springshare LibCal and LibAnswers. There is no central developer portal, no published API catalog, no llms.txt and no .well-known/apis.json.

**Areas:** Education · Higher Education · University · New Zealand · Research · Research Data · Open Access · Institutional Repository · OAI-PMH · DSpace · Identity Federation · Shibboleth

## Massey University on APIs.io

Everything profiled for Massey University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/massey/](https://apis.io/providers/massey/)** — or go straight to one of the APIs or properties below.

### APIs (12)

- [Massey University Shibboleth Identity Provider](https://apis.io/apis/massey/idp-shibboleth/) — Massey University's own SAML 2.0 / Shibboleth Identity Provider. The metadata document is public, machine-readable and continuously published to federation…
- [Massey University Microsoft Entra ID Tenant](https://apis.io/apis/massey/entra-id/) — Massey University's Microsoft Entra ID tenant, discoverable by domain. The OpenID Connect discovery document is public and machine-readable and gives the…
- [DataCite Membership — Massey University](https://apis.io/apis/massey/datacite/) — Massey University is a DataCite member organization within the DataCite New Zealand consortium and mints DOIs through two active repositories -…
- [Crossref Membership — Massey University](https://apis.io/apis/massey/crossref/) — Massey University registers DOIs with Crossref under member id 12895, prefixes 10.33217 and 10.54322, 314 DOIs recorded (22 current, 292 backfile). A second…
- [ROR Registration — Massey University](https://apis.io/apis/massey/ror/) — Massey University's entry in the Research Organization Registry. This is the canonical machine-readable identifier for the institution and the anchor every…
- [Discover — EBSCO Discovery Service (Massey tenancy)](https://apis.io/apis/massey/ebsco-discover/) — "Discover" is Massey University Library's discovery layer, an EBSCO Discovery Service tenancy under customer scope 4egzpd, selected by the library in 2012.…
- [Massey Library Hours & Bookings — Springshare LibCal (Massey tenancy)](https://apis.io/apis/massey/libcal/) — Massey University Library's opening hours, room bookings and events run on a Springshare LibCal tenancy. LibCal exposes a REST API at /api/1.1/ which…
- [Massey Library Enquiries — Springshare LibAnswers (Massey tenancy)](https://apis.io/apis/massey/libanswers/) — Massey University Library's public enquiry and FAQ service, running on a Springshare LibAnswers tenancy. Verified live 2026-09-01. Springshare's contract,…
- [Massey University Core API](https://apis.io/apis/massey/massey-core-api/) — Communities, collections, items and bitstreams.
- [Massey University Discovery API](https://apis.io/apis/massey/massey-discovery-api/) — Search and browse indexes.
- [Massey University News API](https://apis.io/apis/massey/massey-news-api/) — Massey news system data.
- [Massey University Root API](https://apis.io/apis/massey/massey-root-api/) — The Root API from Massey University — 1 operation(s) for root.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (4)

The data models the API reads and writes.

- [Massey M-API Response Envelope](https://apis.io/schemas/massey/massey-mapi-envelope/)
- [Massey M-API News Article](https://apis.io/schemas/massey/massey-mapi-news-article/)
- [Massey Research Online Repository Root](https://apis.io/schemas/massey/massey-mro-dspace-root/)
- [Massey Research Online Paged HAL Collection](https://apis.io/schemas/massey/massey-mro-paged-hal/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Massey Context](https://apis.io/jsonld/massey/massey-context/)

#### Examples (3)

Example requests and responses.

- [Massey Idp Metadata Summary](https://apis.io/examples/massey/massey-idp-metadata-summary/)
- [Massey Mro Communities](https://apis.io/examples/massey/massey-mro-communities/)
- [Massey Mro Root](https://apis.io/examples/massey/massey-mro-root/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Massey University — openapi rules](https://apis.io/rules/massey/massey-openapi-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Massey Authentication](https://apis.io/security/massey/massey-authentication/)
- [Massey Domain Security](https://apis.io/security/massey/massey-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Massey Plans Pricing](https://apis.io/plans/massey/massey-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Massey Rate Limits](https://apis.io/rate-limits/massey/massey-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Massey Finops](https://apis.io/finops/massey/massey-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.massey.ac.nz/)
- [Documentation](https://www.massey.ac.nz/api/v1/)
- [API reference](https://www.massey.ac.nz/api/v1/)
- [Support](https://www.massey.ac.nz/about/contact-us/)
- [Blog](https://sites.massey.ac.nz/library/)
- [Terms of service](https://www.massey.ac.nz/about/policies-procedures-and-guidelines/)
- [Privacy policy](https://www.massey.ac.nz/privacy/)
- [GitHub](https://github.com/Massey-Uni)

## API Evangelist rating

**Kin Score 29.4** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 63.4 |
| Contract quality | 29.2 |
| Contract governance | 11.4 |
| Operational transparency | 7.9 |
| Developer ergonomics | 35.7 |
| Access clarity | 26.3 |

**Agent readiness 31.1** — agent-ready

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
| Rate Limit Signal | derived (partial credit) |
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

**Regulatory alignment 24.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/massey/](https://apis.io/providers/massey/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Massey University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/massey/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
