# Queensland University of Technology

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

Queensland University of Technology (QUT) is a public research university in Brisbane, Australia, serving around 50,000 students with an applied emphasis in teaching and research. It is not an API producer and it publishes no developer portal, no API keys and no OpenAPI of its own — but it is one of the few institutions in this cohort whose machine-readable surfaces are genuinely its own engineering rather than a vendor's contract running under its name. Three surfaces were verified live on QUT-owned infrastructure inside APNIC allocation QUT-AU (AS7575), with no CNAME to a managed platform: the QUT ePrints OAI-PMH 2.0 repository interface at eprints.qut.edu.au, fully public and advertising oai_dc, oai_bibl, oai_openaire and uketd_dc; a self-hosted Shibboleth SAML 2.0 identity provider at idp.qut.edu.au registered in the Australian Access Federation and asserting the qut.edu.au scope; and a Keycloak OpenID Connect authorization server at esoe.qut.edu.au publishing a complete discovery document, JWKS, RFC 8414 metadata, dynamic client registration, PAR, CIBA and certificate-bound tokens, brokering interactive login to Microsoft Entra ID. QUT eResearch additionally publishes a public agent plugin marketplace carrying an MCP server definition, which is rare for a university — though the documentation host it targets, docs.eres.qut.edu.au, resolves publicly to an RFC 1918 private address and is unreachable from outside QUT. Everything else is bought: library discovery is an Ex Libris Primo VE tenancy, the LMS is Instructure Canvas, research data is contributed to ARDC's national registry, and identity is registered in DataCite, Crossref and ROR. Those relationships are recorded here; their contracts are not, because they are not QUT's. There is no open data portal, no course or timetable API, and no public route to a credential for the one authorization server QUT does run.

**Areas:** University · Higher Education · Education · Australia · Research · Research Repository · Identity Federation · OAI-PMH · SAML · Institutional Repository · Open Access

## Queensland University of Technology on APIs.io

Everything profiled for Queensland University of Technology is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/qut/](https://apis.io/providers/qut/)** — or go straight to one of the APIs or properties below.

### APIs (16)

- [QUT Shibboleth Identity Provider](https://apis.io/apis/qut/qut-shibboleth-identity-provider/) — QUT's self-hosted Shibboleth SAML 2.0 identity provider. Publishes per-entity metadata that dereferences from its own entityID, asserts shibmd:Scope…
- [QUT eResearch Agent Plugin Marketplace](https://apis.io/apis/qut/qut-eresearch-agent-plugin-marketplace/) — A public agent plugin marketplace published by QUT eResearch, carrying one MCP server definition that wraps the QUT eResearch documentation site.…
- [QUT Library Discovery (Ex Libris Primo VE tenant)](https://apis.io/apis/qut/qut-library-discovery-ex-libris-primo-ve-tenant/) — QUT's library discovery layer runs on Ex Libris Primo VE / Alma under view id 61QUT_INST:QUT. The collection and the configuration are QUT's; the platform…
- [QUT Canvas LMS (Instructure tenant)](https://apis.io/apis/qut/qut-canvas-lms-instructure-tenant/) — QUT's learning management system, an Instructure Canvas tenancy on a QUT hostname, front-ended by Microsoft Entra ID sign-in. Canvas is an LTI 1.3 platform…
- [QUT collection in ARDC Research Data Australia](https://apis.io/apis/qut/qut-collection-in-ardc-research-data-australia/) — QUT contributes a named group to the Australian Research Data Commons national registry. A live query for group "Queensland University of Technology"…
- [DataCite DOI and RAiD registration](https://apis.io/apis/qut/datacite-doi-and-raid-registration/) — QUT registers persistent identifiers with DataCite through the ARDC consortium. Two clients are evidenced: ARDCX.QUT1, a repository client registered 2020…
- [Crossref membership](https://apis.io/apis/qut/crossref-membership/) — QUT is a Crossref member, id 3230, primary-name "Queensland University of Technology", verified live against Crossref's member API. Recorded as a…
- [ROR registration](https://apis.io/apis/qut/ror-registration/) — QUT's Research Organization Registry identifier is https://ror.org/03pnv4752. The canonical machine-readable identifier for the institution itself, used…
- [Australian Access Federation membership](https://apis.io/apis/qut/australian-access-federation-membership/) — QUT is a member of the Australian Access Federation, which is interfederated with eduGAIN. Five entity descriptors naming QUT appear in the production…
- [Queensland University of Technology Authorization API](https://apis.io/apis/qut/qut-authorization-api/) — OAuth 2.0 authorization and device / CIBA initiation.
- [Queensland University of Technology Client Registration API](https://apis.io/apis/qut/qut-client-registration-api/) — OpenID Connect Dynamic Client Registration.
- [Queensland University of Technology Datasets API](https://apis.io/apis/qut/qut-datasets-api/) — EPrints REST dataset navigation.
- [Queensland University of Technology Discovery API](https://apis.io/apis/qut/qut-discovery-api/) — Provider metadata documents.
- [Queensland University of Technology Identity API](https://apis.io/apis/qut/qut-identity-api/) — End-user claims and session termination.
- [Queensland University of Technology OAI PMH API](https://apis.io/apis/qut/qut-oai-pmh-api/) — The six OAI-PMH 2.0 verbs, all dispatched from a single /oai2 resource by the `verb` parameter.
- [Queensland University of Technology Token API](https://apis.io/apis/qut/qut-token-api/) — Token issuance, inspection and revocation.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (3)

The data models the API reads and writes.

- [QUT ESOE OpenID Provider Metadata](https://apis.io/schemas/qut/qut-esoe-openid-configuration/)
- [QUT ePrints OAI-PMH Identify Response](https://apis.io/schemas/qut/qut-oai-pmh-identify/)
- [QUT ePrints OAI-PMH Metadata Format](https://apis.io/schemas/qut/qut-oai-pmh-metadata-format/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Qut Context](https://apis.io/jsonld/qut/qut-context/)

#### Examples (1)

Example requests and responses.

- [Qut Esoe Openid Configuration](https://apis.io/examples/qut/qut-esoe-openid-configuration/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Queensland University of Technology — openapi rules](https://apis.io/rules/qut/qut-openapi-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Qut Authentication](https://apis.io/security/qut/qut-authentication/)
- [Qut Domain Security](https://apis.io/security/qut/qut-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Qut Scopes](https://apis.io/scopes/qut/qut-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Qut Plans Pricing](https://apis.io/plans/qut/qut-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Qut Rate Limits](https://apis.io/rate-limits/qut/qut-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Qut Finops](https://apis.io/finops/qut/qut-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.qut.edu.au/)
- [Documentation](https://www.library.qut.edu.au/about/collections/qut-eprints/)

## API Evangelist rating

**Kin Score 23.3** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 82.1 |
| Contract quality | 26.1 |
| Contract governance | 11.4 |
| Operational transparency | 10.5 |
| Developer ergonomics | 21.4 |
| Access clarity | 5.3 |

**Agent readiness 32.9** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 26.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/qut/](https://apis.io/providers/qut/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Queensland University of Technology: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/qut/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
