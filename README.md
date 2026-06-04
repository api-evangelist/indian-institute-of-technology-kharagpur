# Indian Institute of Technology Kharagpur (indian-institute-of-technology-kharagpur)

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
