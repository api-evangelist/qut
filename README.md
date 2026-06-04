# Queensland University of Technology (qut)

Queensland University of Technology (QUT) is a public research university in Brisbane, Australia, ranked #213 in the QS World University Rankings 2025. This repository catalogs QUT's public developer and API footprint as an [APIs.json](https://apisjson.org) profile. QUT's machine-accessible footprint is modest and centered on open research infrastructure — most notably the QUT ePrints institutional repository's OAI-PMH metadata interface — alongside several active research-group GitHub organizations.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/qut/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=qut-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Data, Australia, OAI-PMH

## APIs

- **QUT ePrints OAI-PMH** — OAI-PMH 2.0 metadata harvesting for the QUT ePrints institutional research repository (oai_dc, oai_bibl, oai_openaire, uketd_dc). Base URL: `https://eprints.qut.edu.au/cgi/oai2`. Docs: https://www.library.qut.edu.au/about/collections/qut-eprints/

## Plans

- [plans/qut-plans-pricing.yml](plans/qut-plans-pricing.yml)

## Rate Limits

- [rate-limits/qut-rate-limits.yml](rate-limits/qut-rate-limits.yml)

## FinOps

- [finops/qut-finops.yml](finops/qut-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.qut.edu.au/
- GitHub: https://github.com/eresearchqut
- LinkedIn: https://au.linkedin.com/school/queensland-university-of-technology/
- Review: [review.yml](review.yml)

## Notes

All entries were verified against live public sources on 2026-06-03. The QUT ePrints OAI-PMH endpoint was confirmed live (verb=Identify and verb=ListMetadataFormats returned valid responses). QUT Library Search runs on Ex Libris Primo VE / Alma, which have vendor APIs, but QUT publishes no open developer documentation or keys for them, so they are not cataloged as public APIs. The Timetable Planner, mobile app backend, and SSO/identity layer are gated and undocumented. No public open-data portal (e.g. data.qut.edu.au) was found. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
