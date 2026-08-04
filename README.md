# Indian Institute of Technology Kharagpur (indian-institute-of-technology-kharagpur)

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

Indian Institute of Technology Kharagpur (IIT KGP) is a public technical and research university in West Bengal, India — the first of the IITs — ranked #222 in the QS World University Rankings 2025. This repository catalogs its publicly reachable, standards-based API and data footprint as an [APIs.json](https://apievangelist.com/) provider profile. IIT Kharagpur does not operate a formal institution-wide developer portal; the entries below are the public, standards-based endpoints that could be confirmed.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/indian-institute-of-technology-kharagpur/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=indian-institute-of-technology-kharagpur-api-evangelist&utm_content=repo

## Type

- Type: Index
- Position: Consumer
- Access: 3rd-Party

## Tags

Education, Higher Education, University, Research, Library, Institutional Repository, DSpace, India

## APIs

- **Institutional Digital Repository (DSpace)** — DSpace-based open repository of IIT Kharagpur scholarly output; public XMLUI interface. Docs: http://www.idr.iitkgp.ac.in/xmlui/
- **IRINS Research Information Portal** — INFLIBNET-hosted research-profile portal ingesting ORCID/Scopus/Crossref data. Docs: https://iitkgp.irins.org/
- **ERP / Single Sign-On (Gated)** — Official ERP/SSO server for enrolled members; gated, no public API docs. Docs: https://erp.iitkgp.ac.in/

## Plans

See [plans/indian-institute-of-technology-kharagpur-plans-pricing.yml](plans/indian-institute-of-technology-kharagpur-plans-pricing.yml).

## Rate Limits

See [rate-limits/indian-institute-of-technology-kharagpur-rate-limits.yml](rate-limits/indian-institute-of-technology-kharagpur-rate-limits.yml).

## FinOps

See [finops/indian-institute-of-technology-kharagpur-finops.yml](finops/indian-institute-of-technology-kharagpur-finops.yml).

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.iitkgp.ac.in/
- GitHub: https://github.com/IIT-KGP
- LinkedIn: https://www.linkedin.com/school/indian-institute-of-technology-kharagpur/
- Library: https://library.iitkgp.ac.in/
- Review: [review.yml](review.yml)

## Notes

- No official institution-wide developer portal or documented public API was found. Catalog entries are limited to publicly reachable, standards-based endpoints.
- The DSpace IR XMLUI front end is live; the conventional OAI-PMH verb path probed returned 404, so the exact OAI endpoint location is unconfirmed.
- The ERP/SSO system is gated (OTP + secret question); its SSO endpoint expects POST and returns 405 on GET.
- Community organizations (metakgp, devsoc-iitkgp) maintain unofficial tooling around IIT KGP services and are intentionally excluded from this official-institution catalog.
- HTTP statuses recorded as of 2026-06-03; the main website returns 200 only with a browser User-Agent.

## Maintainers

- Kin Lane — kin@apievangelist.com
