# VA Lighthouse (va-gov)

VA Lighthouse is the US Department of Veterans Affairs' developer API platform. Published at developer.va.gov with production endpoints at api.va.gov, Lighthouse exposes 22+ APIs covering Benefits (claims, documents, reference data, intake), Health (HL7 FHIR R4 Patient Health and Clinical Health, Community Care Eligibility), Facilities, Forms, Veteran Verification and Confirmation, Appeals and Decision Reviews under the Appeals Modernization Act (AMA), Address Validation, Direct Deposit Management, VA Letter Generation, Education Benefits, and the full VA Home Loan Guaranty stack (Loan Guaranty, Loan Review, Guaranty Remittance, Health-Care-Costs Coverage). All authenticated APIs use OAuth 2.0 with both Authorization Code (Veteran consent) and Client Credentials (system) flows; the health APIs additionally support SMART-on-FHIR.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/va-gov/refs/heads/main/apis.yml)

**Portal:** [developer.va.gov](https://developer.va.gov)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=government-api-evangelist&utm_content=repo)

## Tags

 - Government, Veterans Affairs, Veterans, Healthcare, Benefits, FHIR, Open Data, Federal

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### VA Facilities API
Look up information on more than 2,000 VA facilities (health, benefits, cemeteries, Vet Centers) — addresses, geo coordinates, hours, services, mobile status, satisfaction scores, wait times. Open-data API; no auth required.

- [Documentation](https://developer.va.gov/explore/api/va-facilities/docs)
- [OpenAPI v1](openapi/va-gov-facilities-v1-openapi.json)
- [OpenAPI v0](openapi/va-gov-facilities-v0-openapi.json)

### VA Forms API
Search and retrieve the latest VA form metadata, PDF URLs, revision dates, related forms, and benefit categories.

- [Documentation](https://developer.va.gov/explore/api/va-forms/docs)
- [OpenAPI v0](openapi/va-gov-forms-v0-openapi.json)

### Benefits Claims API
Find existing claims, submit Intent to File and 526EZ, upload supporting documents, and check claim status for compensation, pension, education, and other VA benefits. Both OAuth flows.

- [Documentation](https://developer.va.gov/explore/api/benefits-claims/docs)
- [OpenAPI v2](openapi/va-gov-benefits-claims-v2-openapi.json)
- [OpenAPI v1](openapi/va-gov-benefits-claims-v1-openapi.json)

### Benefits Intake API
Submission path for third-party submitted Veteran-facing PDF benefits forms with supporting documents directly into VA's Centralized Mail Portal (CMP).

- [Documentation](https://developer.va.gov/explore/api/benefits-intake/docs)
- [OpenAPI v1](openapi/va-gov-benefits-intake-v1-openapi.json)

### Benefits Documents API
Upload supporting documents (PDF, JPG, PNG, TXT, BMP, TIFF) for a given Veteran's claim directly into VBMS for adjudicators. Client credentials only.

- [Documentation](https://developer.va.gov/explore/api/benefits-documents/docs)
- [OpenAPI v1](openapi/va-gov-benefits-documents-v1-openapi.json)

### Benefits Reference Data API
Authoritative reference values across VBA — contention classifications, disabilities, intake sites, special issues, treatment centers, country/state codes.

- [Documentation](https://developer.va.gov/explore/api/benefits-reference-data/docs)
- [OpenAPI v1](openapi/va-gov-benefits-reference-data-v1-openapi.json)

### Appeals Status API
Status of any benefits appeal under AMA — Higher-Level Reviews, Supplemental Claims, and Board Appeals — including docket position, alerts, and event history.

- [Documentation](https://developer.va.gov/explore/api/appeals-status/docs)
- [OpenAPI v1](openapi/va-gov-appeals-status-v1-openapi.json)
- [OpenAPI v0](openapi/va-gov-appeals-status-v0-openapi.json)

### Appealable Issues API
Issues a Veteran could appeal for a given benefit type. Drives the issue-picker on VA.gov decision review forms (NOD, HLR, SC).

- [Documentation](https://developer.va.gov/explore/api/appealable-issues/docs)
- [OpenAPI v0](openapi/va-gov-appealable-issues-v0-openapi.json)

### Legacy Appeals API
Pre-AMA legacy appeals (filed before Feb 19, 2019) on a Veteran's record — used alongside Appealable Issues to determine AMA opt-in.

- [Documentation](https://developer.va.gov/explore/api/legacy-appeals/docs)
- [OpenAPI v0](openapi/va-gov-legacy-appeals-v0-openapi.json)

### Decision Reviews API
Composite of the three AMA decision-review filing endpoints — HLR, SC, and Notice of Disagreement (Board Appeal / NOD) — for submitting and tracking decision reviews.

- [Documentation](https://developer.va.gov/explore/api/decision-reviews/docs)

### Patient Health API (FHIR)
Patient-context Veteran health record access conformant to HL7 FHIR R4 and SMART-on-FHIR — Allergy, Appointment, Condition, Encounter, Immunization, Medication, Observation, Procedure, plus US Core profiles.

- [Documentation](https://developer.va.gov/explore/api/patient-health/docs)
- [FHIR R4 CapabilityStatement](openapi/va-gov-patient-health-fhir-r4-capability.json)
- Live metadata: [api.va.gov/services/fhir/v0/r4/metadata](https://api.va.gov/services/fhir/v0/r4/metadata)

### Clinical Health API (FHIR)
Provider-facing FHIR R4 read access to Veteran clinical records (Patient, Practitioner, Organization, Location). SMART-on-FHIR scoped for clinical decision support and care-coordination apps.

- [Documentation](https://developer.va.gov/explore/api/clinical-health/docs)

### Community Care Eligibility API
Veteran eligibility for community (non-VA) care under the VA MISSION Act of 2018, including the six community-care criteria.

- [Documentation](https://developer.va.gov/explore/api/community-care-eligibility/docs)
- [OpenAPI v0](openapi/va-gov-community-care-eligibility-v0-openapi.json)

### Veteran Verification API
Confirms a Veteran's service history, disability rating, and military service eligibility for benefits.

- [Documentation](https://developer.va.gov/explore/api/veteran-service-history-and-eligibility/docs)
- [OpenAPI v2](openapi/va-gov-veteran-verification-v2-openapi.json)
- [OpenAPI v1](openapi/va-gov-veteran-verification-v1-openapi.json)
- [OpenAPI v0](openapi/va-gov-veteran-verification-v0-openapi.json)

### Veteran Confirmation API
Privacy-preserving Veteran status check — submit name, DOB, SSN, gender; receive confirmed/not_confirmed.

- [Documentation](https://developer.va.gov/explore/api/veteran-confirmation/docs)
- [OpenAPI v1](openapi/va-gov-veteran-confirmation-v1-openapi.json)
- [OpenAPI v0](openapi/va-gov-veteran-confirmation-v0-openapi.json)

### Address Validation API
Validates and standardizes addresses against USPS and VA address-canonicalization, returning geocoded coordinates and confidence scores.

- [Documentation](https://developer.va.gov/explore/api/address-validation/docs)
- [OpenAPI v3](openapi/va-gov-address-validation-v3-openapi.json)

### Direct Deposit Management API
Retrieve and update a Veteran's compensation, pension, and education benefit direct deposit information. Client credentials only.

- [Documentation](https://developer.va.gov/explore/api/direct-deposit-management/docs)
- [OpenAPI v1](openapi/va-gov-direct-deposit-management-v1-openapi.json)

### VA Letter Generator API
Generate official VA benefit letters (Benefit Summary, Service Verification, Civil Service Preference, Commissary, Proof of Service) on demand as PDFs.

- [Documentation](https://developer.va.gov/explore/api/va-letter-generator/docs)
- [OpenAPI v1](openapi/va-gov-va-letter-generator-v1-openapi.json)

### Education Benefits API
SCOs (School Certifying Officials) read and submit GI Bill / Post-9/11 enrollment data — VA Form 22-1999 enrollment certifications.

- [Documentation](https://developer.va.gov/explore/api/education-benefits/docs)

### Loan Guaranty API
Digital surface for the VA Home Loan Guaranty program — eligibility, appraisals, loan setup, and certificate-of-eligibility (COE) operations.

- [Documentation](https://developer.va.gov/explore/api/loan-guaranty/docs)

### Loan Review API
Submits Loan Review file packages — Substantially Complete Real Estate (SCRE) appraisal and Substitution of Entitlement (SOE) — to VA's Loan Guaranty Service.

- [Documentation](https://developer.va.gov/explore/api/loan-review/docs)
- [OpenAPI v1](openapi/va-gov-loan-review-v1-openapi.json)

### Guaranty Remittance API
Lets VA Loan Guaranty servicers remit funding-fee, late, and other Loan Guaranty payments to VA electronically. Client credentials only; sandbox available.

- [Documentation](https://developer.va.gov/explore/api/guaranty-remittance/docs)

### Health Care Costs Coverage API
Insurance-coordination API for VA's CPAC — submit and update third-party health insurance coverage on a Veteran's record so VA can correctly bill private insurers. Client credentials only.

- [Documentation](https://developer.va.gov/explore/api/health-care-costs-coverage/docs)

## Common Properties

- [Portal — developer.va.gov](https://developer.va.gov)
- [Portal — api.va.gov](https://api.va.gov)
- [GettingStarted](https://developer.va.gov/onboarding)
- [SignUp — Request Sandbox Access](https://developer.va.gov/onboarding/request-sandbox-access)
- [Path to Production](https://developer.va.gov/onboarding/request-production-access)
- [Authentication — Authorization Code Grant](https://developer.va.gov/explore/api/authorization-code)
- [Authentication — Client Credentials Grant](https://developer.va.gov/explore/api/client-credentials)
- [Support](https://developer.va.gov/support)
- [ContactEmail — api@va.gov](mailto:api@va.gov)
- [StatusPage — valighthouse.statuspage.io](https://valighthouse.statuspage.io/)
- [TermsOfService](https://developer.va.gov/terms-of-service)
- [PrivacyPolicy](https://www.va.gov/privacy-policy/)
- [Sandbox — sandbox-api.va.gov](https://sandbox-api.va.gov)
- [OAuth2 Authorize](https://api.va.gov/oauth2/authorization)
- [OAuth2 Token](https://api.va.gov/oauth2/token)
- [OAuth2 Revoke](https://api.va.gov/oauth2/revoke)
- [GitHubOrganization](https://github.com/department-of-veterans-affairs)
- [SourceCode — vets-api](https://github.com/department-of-veterans-affairs/vets-api)
- [SourceCode — vets-website](https://github.com/department-of-veterans-affairs/vets-website)
- [SourceCode — vets-api-clients](https://github.com/department-of-veterans-affairs/vets-api-clients)
- [SourceCode — lighthouse-fhir-apis-consumer-docs](https://github.com/department-of-veterans-affairs/lighthouse-fhir-apis-consumer-docs)
- [SourceCode — lighthouse-oas-tests](https://github.com/department-of-veterans-affairs/lighthouse-oas-tests)
- [SourceCode — health-apis-bulk-fhir](https://github.com/department-of-veterans-affairs/health-apis-bulk-fhir)
- [Documentation — SMART-on-FHIR](http://docs.smarthealthit.org/)
- [Documentation — HL7 FHIR US Core](https://hl7.org/fhir/us/core/)
- [LinkedIn — US Department of Veterans Affairs](https://www.linkedin.com/company/us-veteransaffairs/)
- [Blog — VA News](https://news.va.gov/)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [VA Facilities v1](openapi/va-gov-facilities-v1-openapi.json)
- [VA Facilities v0](openapi/va-gov-facilities-v0-openapi.json)
- [VA Forms v0](openapi/va-gov-forms-v0-openapi.json)
- [Benefits Claims v2](openapi/va-gov-benefits-claims-v2-openapi.json)
- [Benefits Claims v1](openapi/va-gov-benefits-claims-v1-openapi.json)
- [Benefits Intake v1](openapi/va-gov-benefits-intake-v1-openapi.json)
- [Benefits Documents v1](openapi/va-gov-benefits-documents-v1-openapi.json)
- [Benefits Reference Data v1](openapi/va-gov-benefits-reference-data-v1-openapi.json)
- [Appeals Status v1](openapi/va-gov-appeals-status-v1-openapi.json)
- [Appeals Status v0](openapi/va-gov-appeals-status-v0-openapi.json)
- [Appealable Issues v0](openapi/va-gov-appealable-issues-v0-openapi.json)
- [Legacy Appeals v0](openapi/va-gov-legacy-appeals-v0-openapi.json)
- [Community Care Eligibility v0](openapi/va-gov-community-care-eligibility-v0-openapi.json)
- [Veteran Verification v2](openapi/va-gov-veteran-verification-v2-openapi.json)
- [Veteran Verification v1](openapi/va-gov-veteran-verification-v1-openapi.json)
- [Veteran Verification v0](openapi/va-gov-veteran-verification-v0-openapi.json)
- [Veteran Confirmation v1](openapi/va-gov-veteran-confirmation-v1-openapi.json)
- [Veteran Confirmation v0](openapi/va-gov-veteran-confirmation-v0-openapi.json)
- [Address Validation v3](openapi/va-gov-address-validation-v3-openapi.json)
- [Direct Deposit Management v1](openapi/va-gov-direct-deposit-management-v1-openapi.json)
- [VA Letter Generator v1](openapi/va-gov-va-letter-generator-v1-openapi.json)
- [Loan Review v1](openapi/va-gov-loan-review-v1-openapi.json)

### FHIR

- [Patient Health FHIR R4 CapabilityStatement](openapi/va-gov-patient-health-fhir-r4-capability.json)
- Live metadata: [api.va.gov/services/fhir/v0/r4/metadata](https://api.va.gov/services/fhir/v0/r4/metadata)

### JSON-LD

- [VA Lighthouse Context](json-ld/va-gov-context.jsonld)

## Tier Assessment — Tier 1

VA Lighthouse is a Tier-1 government API provider:

- **Breadth:** 22+ live production APIs across Benefits, Health, Facilities, Forms, Verification, Appeals, Address, Direct Deposit, Letters, Education, and the entire VA Home Loan Guaranty stack
- **Standards:** HL7 FHIR R4 + US Core + SMART-on-FHIR for the health APIs; OAuth 2.0 (authorization code + client credentials) with PKCE for the rest
- **Discoverability:** Public OpenAPI 3.x specs for every documented REST API at `api.va.gov/internal/docs/{slug}/{version}/openapi.json`
- **Transparency:** Public statuspage (valighthouse.statuspage.io), release notes per API, documented Path-to-Production, open-source backend (vets-api), open-source reference clients (vets-api-clients), and a public OAS conformance test repo (lighthouse-oas-tests)
- **Sandbox:** Fully provisioned sandbox-api.va.gov with documented synthetic Veteran test accounts
- **Scale:** Powers VA.gov, third-party Veteran-facing apps, lenders, employers, retailers, EHR vendors, and downstream federal partners

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
