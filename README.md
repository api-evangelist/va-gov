# Department of Veterans Affairs (VA Lighthouse)

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

VA Lighthouse is the US Department of Veterans Affairs' developer API platform. Published at developer.va.gov with production endpoints at api.va.gov, Lighthouse exposes 22+ APIs covering Benefits (claims, documents, reference data, intake), Health (HL7 FHIR R4 Patient Health and Clinical Health, Community Care Eligibility), Facilities, Forms, Veteran Verification and Confirmation, Appeals and Decision Reviews under the Appeals Modernization Act (AMA), Address Validation, Direct Deposit Management, VA Letter Generation, Education Benefits, and the full VA Home Loan Guaranty stack (Loan Guaranty, Loan Review, Guaranty Remittance, Health-Care-Costs Coverage). All authenticated APIs use OAuth 2.0 with both Authorization Code (Veteran consent) and Client Credentials (system) flows; the health APIs additionally support SMART-on-FHIR. The platform is operated by the VA Office of the CTO with open-source backend code in github.com/department-of-veterans-affairs/vets-api and reference clients in vets-api-clients.

**Areas:** Government · Veterans Affairs · Veterans · Healthcare · Benefits · FHIR · Open Data · Federal · Health · Appeals · Federal Government

## Department of Veterans Affairs (VA Lighthouse) on APIs.io

Everything profiled for Department of Veterans Affairs (VA Lighthouse) is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/va-gov/](https://apis.io/providers/va-gov/)** — or go straight to one of the APIs or properties below.

### APIs (36)

- [Decision Reviews API](https://apis.io/apis/va-gov/decision-reviews-api/) — Composite of the three AMA decision-review filing endpoints — Higher-Level Review (HLR), Supplemental Claim (SC), and Notice of Disagreement (Board Appeal /…
- [Education Benefits API](https://apis.io/apis/va-gov/education-benefits-api/) — School Certifying Officials (SCOs) and education benefit administrators read and submit GI Bill / Post-9/11 education benefit enrollment data — VA Form…
- [Loan Guaranty API](https://apis.io/apis/va-gov/loan-guaranty-api/) — Provides lenders and servicers the digital surface for the VA Home Loan Guaranty program — eligibility, appraisals, loan setup, and…
- [Guaranty Remittance API](https://apis.io/apis/va-gov/guaranty-remittance-api/) — Lets VA Loan Guaranty servicers remit funding-fee, late, and other Loan Guaranty payments to VA electronically instead of through legacy paper-based…
- [Health Care Costs Coverage API](https://apis.io/apis/va-gov/health-care-costs-coverage-api/) — Insurance-coordination API for VA's Consolidated Patient Account Center (CPAC) — submit and update third-party health insurance coverage on a Veteran's…
- [VA Lighthouse 5103 Waiver API](https://apis.io/apis/va-gov/va-gov-5103-waiver-api/) — Allows authenticated and authorized users to file a 5103 Notice Response on a claim.
- [VA Lighthouse ACA Coverage API](https://apis.io/apis/va-gov/va-gov-aca-coverage-api/) — The ACA Coverage API from VA Lighthouse — 1 operation(s) for aca coverage.
- [VA Lighthouse AddressValidation-v3 API](https://apis.io/apis/va-gov/va-gov-addressvalidation-v3-api/) — Address Standardization and Validation endpoints
- [VA Lighthouse Appealable Issues API](https://apis.io/apis/va-gov/va-gov-appealable-issues-api/) — The Appealable Issues API from VA Lighthouse — 1 operation(s) for appealable issues.
- [VA Lighthouse Appeals Status API](https://apis.io/apis/va-gov/va-gov-appeals-status-api/) — Caseflow appeals status API
- [VA Lighthouse Claims API](https://apis.io/apis/va-gov/va-gov-claims-api/) — Allows authenticated and authorized users to access claims data for a single claim by ID, or for all claims based on claimant data. No data is returned if…
- [VA Lighthouse Disability API](https://apis.io/apis/va-gov/va-gov-disability-api/) — Used for 526 claims.
- [VA Lighthouse Disability Compensation Claims API](https://apis.io/apis/va-gov/va-gov-disability-compensation-claims-api/) — Allows authenticated and authorized users to automatically establish a Disability Compensation Claim (21-526EZ) in VBMS
- [VA Lighthouse Disability Rating API](https://apis.io/apis/va-gov/va-gov-disability-rating-api/) — The Disability Rating API from VA Lighthouse — 4 operation(s) for disability rating.
- [VA Lighthouse Documents Service API](https://apis.io/apis/va-gov/va-gov-documents-service-api/) — The Documents Service API from VA Lighthouse — 9 operation(s) for documents service.
- [VA Lighthouse Enrolled Benefits API](https://apis.io/apis/va-gov/va-gov-enrolled-benefits-api/) — The Enrolled Benefits API from VA Lighthouse — 1 operation(s) for enrolled benefits.
- [VA Lighthouse Facilities API](https://apis.io/apis/va-gov/va-gov-facilities-api/) — VA Facilities API
- [VA Lighthouse Flashes API](https://apis.io/apis/va-gov/va-gov-flashes-api/) — The Flashes API from VA Lighthouse — 1 operation(s) for flashes.
- [VA Lighthouse Forms API](https://apis.io/apis/va-gov/va-gov-forms-api/) — The Forms API from VA Lighthouse — 2 operation(s) for forms.
- [VA Lighthouse Intent to File API](https://apis.io/apis/va-gov/va-gov-intent-to-file-api/) — Used for 0966 submissions.
- [VA Lighthouse JWS Validation API](https://apis.io/apis/va-gov/va-gov-jws-validation-api/) — The JWS Validation API from VA Lighthouse — 1 operation(s) for jws validation.
- [VA Lighthouse Legacy Appeals API](https://apis.io/apis/va-gov/va-gov-legacy-appeals-api/) — The Legacy Appeals API from VA Lighthouse — 1 operation(s) for legacy appeals.
- [VA Lighthouse Letters API](https://apis.io/apis/va-gov/va-gov-letters-api/) — The Letters API from VA Lighthouse — 3 operation(s) for letters.
- [VA Lighthouse Loan Review Public API](https://apis.io/apis/va-gov/va-gov-loanreviewpublic-api/) — Loan Review Public Resource
- [VA Lighthouse Path API](https://apis.io/apis/va-gov/va-gov-path-api/) — The Path API from VA Lighthouse — 1 operation(s) for path.
- [VA Lighthouse Permanent And Total Disability API](https://apis.io/apis/va-gov/va-gov-permanent-and-total-disability-api/) — The Permanent And Total Disability API from VA Lighthouse — 2 operation(s) for permanent and total disability.
- [VA Lighthouse Power of Attorney API](https://apis.io/apis/va-gov/va-gov-power-of-attorney-api/) — Used for 21-22 and 21-22a form submissions.
- [VA Lighthouse Reference Data API](https://apis.io/apis/va-gov/va-gov-reference-data-api/) — The Reference Data API from VA Lighthouse — 9 operation(s) for reference data.
- [VA Lighthouse Search API](https://apis.io/apis/va-gov/va-gov-search-api/) — The Search API from VA Lighthouse — 1 operation(s) for search.
- [VA Lighthouse Service History API](https://apis.io/apis/va-gov/va-gov-service-history-api/) — The Service History API from VA Lighthouse — 1 operation(s) for service history.
- [VA Lighthouse Status API](https://apis.io/apis/va-gov/va-gov-status-api/) — The Status API from VA Lighthouse — 2 operation(s) for status.
- [VA Lighthouse Uploads API](https://apis.io/apis/va-gov/va-gov-uploads-api/) — The Uploads API from VA Lighthouse — 5 operation(s) for uploads.
- [VA Lighthouse Veteran Verification API](https://apis.io/apis/va-gov/va-gov-veteran-verification-api/) — The Veteran Verification API from VA Lighthouse — 3 operation(s) for veteran verification.
- [VA Community Care Eligibility API](https://apis.io/apis/va-gov/va-community-care-eligibility-api/) — Determine whether a Veteran is eligible for community-care services under VA referral programs.
- [Patient Health API (FHIR)](https://apis.io/apis/va-gov/patient-health-api-fhir/) — Allows Veterans and authorized third parties to access patient health data using the HL7 FHIR R4 standard, including records, medications, conditions,…
- [Department of Veterans Affairs (VA Lighthouse) Direct Deposit API](https://apis.io/apis/va-gov/va-gov-direct-deposit-api/) — The Direct Deposit API from Department of Veterans Affairs (VA Lighthouse) — 1 operation(s) for direct deposit.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Va Gov Agentic Access](https://apis.io/agentic-access/va-gov/va-gov-agentic-access/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Va Gov Context](https://apis.io/jsonld/va-gov/va-gov-context/)

#### Collections (52)

Postman and Open Collection request collections.

- [Address Validation 5103 Waiver API](https://apis.io/collections/va-gov/open-va-gov-5103-waiver-api/)
- [Address Validation 5103 Waiver ACA Coverage API](https://apis.io/collections/va-gov/open-va-gov-aca-coverage-api/)
- [Address Validation](https://apis.io/collections/va-gov/open-va-gov-address-validation-v3/)
- [Address Validation 5103 Waiver AddressValidation-v3 API](https://apis.io/collections/va-gov/open-va-gov-addressvalidation-v3-api/)
- [Address Validation 5103 Waiver Appealable Issues API](https://apis.io/collections/va-gov/open-va-gov-appealable-issues-api/)
- [Appealable Issues](https://apis.io/collections/va-gov/open-va-gov-appealable-issues-v0/)
- [Address Validation 5103 Waiver Appeals Status API](https://apis.io/collections/va-gov/open-va-gov-appeals-status-api/)
- [Appeals](https://apis.io/collections/va-gov/open-va-gov-appeals-status-v0/)
- [Appeals Status](https://apis.io/collections/va-gov/open-va-gov-appeals-status-v1/)
- [Benefits Claims](https://apis.io/collections/va-gov/open-va-gov-benefits-claims-v1/)
- [Benefits Claims](https://apis.io/collections/va-gov/open-va-gov-benefits-claims-v2/)
- [Benefits Documents Service API](https://apis.io/collections/va-gov/open-va-gov-benefits-documents-v1/)
- [Benefits Intake](https://apis.io/collections/va-gov/open-va-gov-benefits-intake-v1/)
- [Benefits Data Lookup API](https://apis.io/collections/va-gov/open-va-gov-benefits-reference-data-v1/)
- [Address Validation 5103 Waiver Claims API](https://apis.io/collections/va-gov/open-va-gov-claims-api/)
- [Community Care Eligibility](https://apis.io/collections/va-gov/open-va-gov-community-care-eligibility-v0/)
- [Direct Deposit Management API](https://apis.io/collections/va-gov/open-va-gov-direct-deposit-management-v1/)
- [Address Validation 5103 Waiver DirectDeposit API](https://apis.io/collections/va-gov/open-va-gov-directdeposit-api/)
- [Address Validation 5103 Waiver Disability API](https://apis.io/collections/va-gov/open-va-gov-disability-api/)
- [Address Validation 5103 Waiver Disability Compensation Claims API](https://apis.io/collections/va-gov/open-va-gov-disability-compensation-claims-api/)
- [Address Validation 5103 Waiver Disability Rating API](https://apis.io/collections/va-gov/open-va-gov-disability-rating-api/)
- [Address Validation 5103 Waiver Documents Service API](https://apis.io/collections/va-gov/open-va-gov-documents-service-api/)
- [Address Validation 5103 Waiver Enrolled Benefits API](https://apis.io/collections/va-gov/open-va-gov-enrolled-benefits-api/)
- [Address Validation 5103 Waiver facilities API](https://apis.io/collections/va-gov/open-va-gov-facilities-api/)
- [VA Facilities](https://apis.io/collections/va-gov/open-va-gov-facilities-v0/)
- …and 27 more published on APIs.io

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Va Gov Authentication](https://apis.io/security/va-gov/va-gov-authentication/)
- [Va Gov Domain Security](https://apis.io/security/va-gov/va-gov-domain-security/)
- [Va Gov Vulnerability Disclosure](https://apis.io/security/va-gov/va-gov-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Va Gov Scopes](https://apis.io/scopes/va-gov/va-gov-scopes/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.va.gov/)
- [Documentation](https://developer.va.gov/explore)
- [Getting started](https://developer.va.gov/onboarding)
- [Support](https://developer.va.gov/support)
- [Blog](https://news.va.gov/)
- [Terms of service](https://developer.va.gov/terms-of-service)
- [Privacy policy](https://www.va.gov/privacy-policy/)
- [GitHub](https://github.com/department-of-veterans-affairs)
- [Status](https://valighthouse.statuspage.io/)

## API Evangelist rating

**Kin Score 41.8** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 60.6 |
| Contract governance | 0.0 |
| Operational transparency | 28.9 |
| Developer ergonomics | 31.0 |
| Access clarity | 23.7 |

**Agent readiness 30.3** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | — |

**Regulatory alignment 34.4** — Health

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/va-gov/](https://apis.io/providers/va-gov/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Department of Veterans Affairs (VA Lighthouse): the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/va-gov/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
