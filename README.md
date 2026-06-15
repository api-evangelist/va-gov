# VA Lighthouse (va-gov)

VA Lighthouse is the US Department of Veterans Affairs' developer API platform. Published at developer.va.gov with production endpoints at api.va.gov, Lighthouse exposes 22+ APIs covering Benefits (claims, documents, reference data, intake), Health (HL7 FHIR R4 Patient Health and Clinical Health, Community Care Eligibility), Facilities, Forms, Veteran Verification and Confirmation, Appeals and Decision Reviews under the Appeals Modernization Act (AMA), Address Validation, Direct Deposit Management, VA Letter Generation, Education Benefits, and the full VA Home Loan Guaranty stack (Loan Guaranty, Loan Review, Guaranty Remittance, Health-Care-Costs Coverage). All authenticated APIs use OAuth 2.0 with both Authorization Code (Veteran consent) and Client Credentials (system) flows; the health APIs additionally support SMART-on-FHIR. The platform is operated by the VA Office of the CTO with open-source backend code in github.com/department-of-veterans-affairs/vets-api and reference clients in vets-api-clients.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/va-gov/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/va-gov/refs/heads/main/apis.yml)

## Scope

- **Position:** Providing
- **Access:** 3rd-Party

## Tags

- Government
- Veterans Affairs
- Veterans
- Healthcare
- Benefits
- FHIR
- Open Data
- Federal

## Timestamps

- **Created:** 2026-05-25T00:00:00.000Z
- **Modified:** 2026-05-25

## APIs

### VA Facilities API

Look up information on more than 2,000 VA facilities — VA health facilities, benefits offices, cemeteries, Vet Centers — including addresses, geographic coordinates, hours, services offered, mobile/non-mobile status, satisfaction scores, and wait times. Open data API; no authentication required for v1.

- **Human URL:** [https://developer.va.gov/explore/api/va-facilities/docs](https://developer.va.gov/explore/api/va-facilities/docs)
- **Base URL:** `https://api.va.gov/services/va_facilities/v1`

#### Tags

- Government
- Healthcare
- Facilities
- Veterans Affairs
- Geospatial

#### Properties

- [Documentation](https://developer.va.gov/explore/api/va-facilities/docs)
- [OpenAPI](https://api.va.gov/internal/docs/facilities/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/va-gov-facilities-v1-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/va-gov-facilities-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-facilities-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](openapi/va-gov-facilities-v0-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/va-gov-facilities-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-facilities-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Changelog](https://developer.va.gov/explore/api/va-facilities/release-notes)

### VA Forms API

Search and retrieve the latest VA form information, including PDF URLs, revision dates, related forms, and benefit categories for every VA form. Backed by VA Forms data so consumers can keep their integrations aligned with the current canonical PDFs.

- **Human URL:** [https://developer.va.gov/explore/api/va-forms/docs](https://developer.va.gov/explore/api/va-forms/docs)
- **Base URL:** `https://api.va.gov/services/va_forms/v0`

#### Tags

- Government
- Forms
- Veterans Affairs
- Documents

#### Properties

- [Documentation](https://developer.va.gov/explore/api/va-forms/docs)
- [OpenAPI](https://api.va.gov/internal/docs/forms/v0/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/va-gov-forms-v0-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/va-gov-forms-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-forms-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Changelog](https://developer.va.gov/explore/api/va-forms/release-notes)

### Benefits Claims API

Lets Veterans, accredited representatives, and approved third-party consumers find existing benefits claims, submit Intent to File and 526EZ forms, upload supporting documentation, and check claim status for compensation, pension, education, and other VA benefits programs. Supports both authorization code and client credentials OAuth flows.

- **Human URL:** [https://developer.va.gov/explore/api/benefits-claims/docs](https://developer.va.gov/explore/api/benefits-claims/docs)
- **Base URL:** `https://api.va.gov/services/claims/v2`

#### Tags

- Government
- Veterans Affairs
- Benefits
- Claims

#### Properties

- [Documentation](https://developer.va.gov/explore/api/benefits-claims/docs)
- [OpenAPI](https://api.va.gov/internal/docs/benefits-claims/v2/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/va-gov-benefits-claims-v2-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/va-gov-benefits-claims-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-claims-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](openapi/va-gov-benefits-claims-v1-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/va-gov-benefits-claims-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-claims-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developer.va.gov/explore/api/benefits-claims/authorization-code)
- [Changelog](https://developer.va.gov/explore/api/benefits-claims/release-notes)

### Benefits Intake API

Provides a third-party submission path for veteran-facing PDF benefits forms with supporting documentation directly into VA's Centralized Mail Portal (CMP). Supports the same 4142, 686C, 526EZ, and dozens of other VA benefit forms — replacing the former eBenefits paper-equivalent upload flow.

- **Human URL:** [https://developer.va.gov/explore/api/benefits-intake/docs](https://developer.va.gov/explore/api/benefits-intake/docs)
- **Base URL:** `https://api.va.gov/services/vba_documents/v1`

#### Tags

- Government
- Veterans Affairs
- Benefits
- Documents
- Uploads

#### Properties

- [Documentation](https://developer.va.gov/explore/api/benefits-intake/docs)
- [OpenAPI](https://api.va.gov/internal/docs/benefits-intake/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/va-gov-benefits-intake-v1-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/va-gov-benefits-intake-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-intake-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Changelog](https://developer.va.gov/explore/api/benefits-intake/release-notes)

### Benefits Documents API

Upload supporting documents (PDF, JPG, PNG, TXT, BMP, TIFF) for a given Veteran's benefits claim directly into VBMS for adjudicators. Client credentials OAuth flow only.

- **Human URL:** [https://developer.va.gov/explore/api/benefits-documents/docs](https://developer.va.gov/explore/api/benefits-documents/docs)
- **Base URL:** `https://api.va.gov/services/benefits-documents/v1`

#### Tags

- Government
- Veterans Affairs
- Benefits
- Documents

#### Properties

- [Documentation](https://developer.va.gov/explore/api/benefits-documents/docs)
- [OpenAPI](https://api.va.gov/internal/docs/benefits-documents/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/va-gov-benefits-documents-v1-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/va-gov-benefits-documents-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-documents-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developer.va.gov/explore/api/benefits-documents/client-credentials)
- [Changelog](https://developer.va.gov/explore/api/benefits-documents/release-notes)

### Benefits Reference Data API

Authoritative reference values consumed across the VBA stack — contention classifications, disabilities, intake sites, special issues, treatment centers, and country/state codes. Used by claim-establishment and form-submission integrations to validate enumerated values.

- **Human URL:** [https://developer.va.gov/explore/api/benefits-reference-data/docs](https://developer.va.gov/explore/api/benefits-reference-data/docs)
- **Base URL:** `https://api.va.gov/services/benefits-reference-data/v1`

#### Tags

- Government
- Veterans Affairs
- Benefits
- Reference Data

#### Properties

- [Documentation](https://developer.va.gov/explore/api/benefits-reference-data/docs)
- [OpenAPI](https://api.va.gov/internal/docs/benefits-reference-data/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/va-gov-benefits-reference-data-v1-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/va-gov-benefits-reference-data-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-reference-data-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Changelog](https://developer.va.gov/explore/api/benefits-reference-data/release-notes)

### Appeals Status API

Returns the status of any benefits appeal — Higher-Level Reviews, Supplemental Claims, and Board Appeals under the Appeals Modernization Act (AMA) — including the docket position, alerts, and event history for a Veteran.

- **Human URL:** [https://developer.va.gov/explore/api/appeals-status/docs](https://developer.va.gov/explore/api/appeals-status/docs)
- **Base URL:** `https://api.va.gov/services/appeals/v1`

#### Tags

- Government
- Veterans Affairs
- Appeals
- Status

#### Properties

- [Documentation](https://developer.va.gov/explore/api/appeals-status/docs)
- [OpenAPI](https://api.va.gov/internal/docs/appeals-status/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/va-gov-appeals-status-v1-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/va-gov-appeals-status-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-appeals-status-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](openapi/va-gov-appeals-status-v0-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/va-gov-appeals-status-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-appeals-status-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Changelog](https://developer.va.gov/explore/api/appeals-status/release-notes)

### Appealable Issues API

Lists the issues a Veteran could appeal for a given benefit type (compensation, pension, etc.). Drives the issue-picker on VA.gov decision review forms — Notice of Disagreement (NOD), Higher-Level Review (HLR), and Supplemental Claim (SC).

- **Human URL:** [https://developer.va.gov/explore/api/appealable-issues/docs](https://developer.va.gov/explore/api/appealable-issues/docs)
- **Base URL:** `https://api.va.gov/services/appeals/appealable-issues/v0`

#### Tags

- Government
- Veterans Affairs
- Appeals
- Decision Reviews

#### Properties

- [Documentation](https://developer.va.gov/explore/api/appealable-issues/docs)
- [OpenAPI](https://api.va.gov/internal/docs/appealable-issues/v0/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/va-gov-appealable-issues-v0-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/va-gov-appealable-issues-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-appealable-issues-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Changelog](https://developer.va.gov/explore/api/appealable-issues/release-notes)

### Legacy Appeals API

Returns pre-AMA legacy appeals (filed before Feb 19, 2019) on a Veteran's record. Used in tandem with Appealable Issues to determine whether the Veteran must opt-in to AMA before requesting a decision review.

- **Human URL:** [https://developer.va.gov/explore/api/legacy-appeals/docs](https://developer.va.gov/explore/api/legacy-appeals/docs)
- **Base URL:** `https://api.va.gov/services/appeals/legacy-appeals/v0`

#### Tags

- Government
- Veterans Affairs
- Appeals
- Legacy

#### Properties

- [Documentation](https://developer.va.gov/explore/api/legacy-appeals/docs)
- [OpenAPI](https://api.va.gov/internal/docs/legacy-appeals/v0/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/va-gov-legacy-appeals-v0-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/va-gov-legacy-appeals-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-legacy-appeals-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Changelog](https://developer.va.gov/explore/api/legacy-appeals/release-notes)

### Decision Reviews API

Composite of the three AMA decision-review filing endpoints — Higher-Level Review (HLR), Supplemental Claim (SC), and Notice of Disagreement (Board Appeal / NOD) — for submitting and tracking decision reviews under the Veterans Appeals Improvement and Modernization Act.

- **Human URL:** [https://developer.va.gov/explore/api/decision-reviews/docs](https://developer.va.gov/explore/api/decision-reviews/docs)
- **Base URL:** `https://api.va.gov/services/appeals/v2`

#### Tags

- Government
- Veterans Affairs
- Appeals
- Decision Reviews

#### Properties

- [Documentation](https://developer.va.gov/explore/api/decision-reviews/docs)
- [Changelog](https://developer.va.gov/explore/api/decision-reviews/release-notes)
- [Postman Collection](collections/va-gov-address-validation-v3.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-address-validation-v3.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-appealable-issues-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-appealable-issues-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-appeals-status-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-appeals-status-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-appeals-status-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-appeals-status-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-claims-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-claims-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-claims-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-claims-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-documents-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-documents-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-intake-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-intake-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-reference-data-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-reference-data-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-community-care-eligibility-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-community-care-eligibility-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-direct-deposit-management-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-direct-deposit-management-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-facilities-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-facilities-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-facilities-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-facilities-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-forms-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-forms-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-legacy-appeals-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-legacy-appeals-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-loan-review-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-loan-review-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-va-letter-generator-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-va-letter-generator-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-confirmation-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-confirmation-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-confirmation-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-confirmation-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-verification-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-verification-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-verification-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-verification-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-verification-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-verification-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Patient Health API (FHIR)

Patient-context Veteran health record access conformant to HL7 FHIR R4 and SMART-on-FHIR — AllergyIntolerance, Appointment, Condition, DiagnosticReport, Encounter, Immunization, Medication, MedicationRequest, Observation, Patient, Procedure, and more, plus US Core profiles. Authorization code (Veteran consent) and client credentials flows.

- **Human URL:** [https://developer.va.gov/explore/api/patient-health/docs](https://developer.va.gov/explore/api/patient-health/docs)
- **Base URL:** `https://api.va.gov/services/fhir/v0/r4`

#### Tags

- Government
- Veterans Affairs
- Healthcare
- FHIR
- SMART on FHIR
- HL7

#### Properties

- [Documentation](https://developer.va.gov/explore/api/patient-health/docs)
- [OpenAPI](https://api.va.gov/services/fhir/v0/r4/metadata) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://developer.va.gov/explore/api/patient-health/authorization-code)
- [Postman Collection](collections/va-gov-address-validation-v3.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-address-validation-v3.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-appealable-issues-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-appealable-issues-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-appeals-status-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-appeals-status-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-appeals-status-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-appeals-status-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-claims-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-claims-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-claims-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-claims-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-documents-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-documents-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-intake-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-intake-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-reference-data-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-reference-data-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-community-care-eligibility-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-community-care-eligibility-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-direct-deposit-management-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-direct-deposit-management-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-facilities-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-facilities-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-facilities-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-facilities-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-forms-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-forms-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-legacy-appeals-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-legacy-appeals-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-loan-review-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-loan-review-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-va-letter-generator-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-va-letter-generator-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-confirmation-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-confirmation-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-confirmation-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-confirmation-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-verification-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-verification-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-verification-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-verification-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-verification-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-verification-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Clinical Health API (FHIR)

Provider-facing FHIR R4 read access to Veteran clinical records (Patient, Practitioner, Organization, Location, and related resources). Same SMART-on-FHIR authorization model as Patient Health but scoped for clinical decision support and care-coordination apps.

- **Human URL:** [https://developer.va.gov/explore/api/clinical-health/docs](https://developer.va.gov/explore/api/clinical-health/docs)
- **Base URL:** `https://api.va.gov/services/fhir/v0/r4`

#### Tags

- Government
- Veterans Affairs
- Healthcare
- FHIR
- Clinical
- HL7

#### Properties

- [Documentation](https://developer.va.gov/explore/api/clinical-health/docs)
- [OpenAPI](https://api.va.gov/services/fhir/v0/r4/metadata) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://developer.va.gov/explore/api/clinical-health/authorization-code)
- [Postman Collection](collections/va-gov-address-validation-v3.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-address-validation-v3.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-appealable-issues-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-appealable-issues-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-appeals-status-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-appeals-status-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-appeals-status-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-appeals-status-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-claims-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-claims-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-claims-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-claims-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-documents-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-documents-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-intake-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-intake-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-reference-data-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-reference-data-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-community-care-eligibility-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-community-care-eligibility-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-direct-deposit-management-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-direct-deposit-management-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-facilities-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-facilities-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-facilities-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-facilities-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-forms-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-forms-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-legacy-appeals-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-legacy-appeals-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-loan-review-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-loan-review-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-va-letter-generator-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-va-letter-generator-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-confirmation-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-confirmation-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-confirmation-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-confirmation-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-verification-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-verification-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-verification-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-verification-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-verification-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-verification-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Community Care Eligibility API

Determines whether a Veteran is eligible to receive care from a community (non-VA) provider under the VA MISSION Act of 2018. Returns eligibility decisions for the six community care criteria — distance, wait time, grandfathered status, hardship, no-full-service VA, and best medical interest.

- **Human URL:** [https://developer.va.gov/explore/api/community-care-eligibility/docs](https://developer.va.gov/explore/api/community-care-eligibility/docs)
- **Base URL:** `https://api.va.gov/services/community-care/v0`

#### Tags

- Government
- Veterans Affairs
- Healthcare
- Eligibility
- Community Care

#### Properties

- [Documentation](https://developer.va.gov/explore/api/community-care-eligibility/docs)
- [OpenAPI](https://api.va.gov/internal/docs/community-care-eligibility/v0/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/va-gov-community-care-eligibility-v0-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/va-gov-community-care-eligibility-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-community-care-eligibility-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Changelog](https://developer.va.gov/explore/api/community-care-eligibility/release-notes)

### Veteran Verification API

Confirms a Veteran's service history, disability rating, and military service eligibility for benefits. Provides the data behind employer/lender/retailer Veteran-discount verification flows and downstream eligibility integrations.

- **Human URL:** [https://developer.va.gov/explore/api/veteran-service-history-and-eligibility/docs](https://developer.va.gov/explore/api/veteran-service-history-and-eligibility/docs)
- **Base URL:** `https://api.va.gov/services/veteran_verification/v2`

#### Tags

- Government
- Veterans Affairs
- Identity
- Verification

#### Properties

- [Documentation](https://developer.va.gov/explore/api/veteran-service-history-and-eligibility/docs)
- [OpenAPI](https://api.va.gov/internal/docs/veteran-verification/v2/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/va-gov-veteran-verification-v2-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/va-gov-veteran-verification-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-verification-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](openapi/va-gov-veteran-verification-v1-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/va-gov-veteran-verification-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-verification-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](openapi/va-gov-veteran-verification-v0-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/va-gov-veteran-verification-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-verification-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Veteran Confirmation API

Confirms Veteran status without revealing PII. Send a Veteran's name, date of birth, SSN, and gender; receive a simple confirmed/not_confirmed response. Powers Veteran-discount and Veteran-status checks for retail and SaaS integrators.

- **Human URL:** [https://developer.va.gov/explore/api/veteran-confirmation/docs](https://developer.va.gov/explore/api/veteran-confirmation/docs)
- **Base URL:** `https://api.va.gov/services/veteran_confirmation/v1`

#### Tags

- Government
- Veterans Affairs
- Identity
- Verification

#### Properties

- [Documentation](https://developer.va.gov/explore/api/veteran-confirmation/docs)
- [OpenAPI](https://api.va.gov/internal/docs/veteran-confirmation/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/va-gov-veteran-confirmation-v1-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/va-gov-veteran-confirmation-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-confirmation-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](openapi/va-gov-veteran-confirmation-v0-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/va-gov-veteran-confirmation-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-confirmation-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Changelog](https://developer.va.gov/explore/api/veteran-confirmation/release-notes)

### Address Validation API

Validates and standardizes addresses against the USPS and VA address-canonicalization stack, returning geocoded coordinates and confidence scores. Used across VBA, VHA, and VA.gov to keep Veteran addresses correct before mailing benefit decisions or scheduling care.

- **Human URL:** [https://developer.va.gov/explore/api/address-validation/docs](https://developer.va.gov/explore/api/address-validation/docs)
- **Base URL:** `https://api.va.gov/services/address_validation/v3`

#### Tags

- Government
- Veterans Affairs
- Address
- Validation
- Geocoding

#### Properties

- [Documentation](https://developer.va.gov/explore/api/address-validation/docs)
- [OpenAPI](https://api.va.gov/internal/docs/address-validation/v3/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/va-gov-address-validation-v3-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/va-gov-address-validation-v3.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-address-validation-v3.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Direct Deposit Management API

Retrieve and update a Veteran's compensation, pension, and education benefit direct deposit information — routing number, account number, account type, and payment status. Client credentials only.

- **Human URL:** [https://developer.va.gov/explore/api/direct-deposit-management/docs](https://developer.va.gov/explore/api/direct-deposit-management/docs)
- **Base URL:** `https://api.va.gov/services/direct-deposit-management/v1`

#### Tags

- Government
- Veterans Affairs
- Banking
- Direct Deposit
- Payments

#### Properties

- [Documentation](https://developer.va.gov/explore/api/direct-deposit-management/docs)
- [OpenAPI](https://api.va.gov/internal/docs/direct-deposit-management/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/va-gov-direct-deposit-management-v1-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/va-gov-direct-deposit-management-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-direct-deposit-management-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developer.va.gov/explore/api/direct-deposit-management/client-credentials)

### VA Letter Generator API

Generate official VA benefit letters (Benefit Summary, Service Verification, Civil Service Preference, Commissary, Proof of Service, etc.) on demand as PDFs — used by lenders, employers, and Veteran-service organizations that need authoritative VA documentation.

- **Human URL:** [https://developer.va.gov/explore/api/va-letter-generator/docs](https://developer.va.gov/explore/api/va-letter-generator/docs)
- **Base URL:** `https://api.va.gov/services/va-letter-generator/v1`

#### Tags

- Government
- Veterans Affairs
- Letters
- Documents
- Benefits

#### Properties

- [Documentation](https://developer.va.gov/explore/api/va-letter-generator/docs)
- [OpenAPI](https://api.va.gov/internal/docs/va-letter-generator/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/va-gov-va-letter-generator-v1-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/va-gov-va-letter-generator-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-va-letter-generator-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developer.va.gov/explore/api/va-letter-generator/client-credentials)

### Education Benefits API

School Certifying Officials (SCOs) and education benefit administrators read and submit GI Bill / Post-9/11 education benefit enrollment data — VA Form 22-1999 enrollment certifications — on behalf of enrolled student Veterans.

- **Human URL:** [https://developer.va.gov/explore/api/education-benefits/docs](https://developer.va.gov/explore/api/education-benefits/docs)
- **Base URL:** `https://api.va.gov/services/education/v0`

#### Tags

- Government
- Veterans Affairs
- Education
- GI Bill
- Benefits

#### Properties

- [Documentation](https://developer.va.gov/explore/api/education-benefits/docs)
- [Authentication](https://developer.va.gov/explore/api/education-benefits/client-credentials)
- [Changelog](https://developer.va.gov/explore/api/education-benefits/release-notes)
- [Postman Collection](collections/va-gov-address-validation-v3.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-address-validation-v3.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-appealable-issues-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-appealable-issues-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-appeals-status-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-appeals-status-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-appeals-status-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-appeals-status-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-claims-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-claims-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-claims-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-claims-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-documents-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-documents-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-intake-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-intake-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-reference-data-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-reference-data-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-community-care-eligibility-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-community-care-eligibility-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-direct-deposit-management-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-direct-deposit-management-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-facilities-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-facilities-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-facilities-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-facilities-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-forms-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-forms-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-legacy-appeals-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-legacy-appeals-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-loan-review-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-loan-review-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-va-letter-generator-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-va-letter-generator-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-confirmation-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-confirmation-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-confirmation-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-confirmation-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-verification-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-verification-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-verification-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-verification-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-verification-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-verification-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Loan Guaranty API

Provides lenders and servicers the digital surface for the VA Home Loan Guaranty program — eligibility, appraisals, loan setup, and certificate-of-eligibility (COE) operations. Companion APIs handle Loan Review, Guaranty Remittance, and Health-Care-Costs Coverage.

- **Human URL:** [https://developer.va.gov/explore/api/loan-guaranty/docs](https://developer.va.gov/explore/api/loan-guaranty/docs)
- **Base URL:** `https://api.va.gov/services/loan-guaranty/v1`

#### Tags

- Government
- Veterans Affairs
- Home Loans
- Mortgages
- Loan Guaranty

#### Properties

- [Documentation](https://developer.va.gov/explore/api/loan-guaranty/docs)
- [Changelog](https://developer.va.gov/explore/api/loan-guaranty/release-notes)
- [Postman Collection](collections/va-gov-address-validation-v3.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-address-validation-v3.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-appealable-issues-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-appealable-issues-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-appeals-status-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-appeals-status-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-appeals-status-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-appeals-status-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-claims-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-claims-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-claims-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-claims-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-documents-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-documents-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-intake-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-intake-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-reference-data-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-reference-data-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-community-care-eligibility-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-community-care-eligibility-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-direct-deposit-management-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-direct-deposit-management-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-facilities-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-facilities-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-facilities-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-facilities-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-forms-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-forms-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-legacy-appeals-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-legacy-appeals-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-loan-review-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-loan-review-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-va-letter-generator-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-va-letter-generator-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-confirmation-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-confirmation-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-confirmation-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-confirmation-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-verification-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-verification-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-verification-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-verification-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-verification-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-verification-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Loan Review API

Submits Loan Review file packages — Substantially Complete Real Estate (SCRE) appraisal and Substitution of Entitlement (SOE) — to VA's Loan Guaranty Service. Used by VA-approved automatic-authority lenders for prior-approval review.

- **Human URL:** [https://developer.va.gov/explore/api/loan-review/docs](https://developer.va.gov/explore/api/loan-review/docs)
- **Base URL:** `https://api.va.gov/services/loan-review/v1`

#### Tags

- Government
- Veterans Affairs
- Home Loans
- Loan Guaranty

#### Properties

- [Documentation](https://developer.va.gov/explore/api/loan-review/docs)
- [OpenAPI](https://api.va.gov/internal/docs/loan-review/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/va-gov-loan-review-v1-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/va-gov-loan-review-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-loan-review-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developer.va.gov/explore/api/loan-review/client-credentials)

### Guaranty Remittance API

Lets VA Loan Guaranty servicers remit funding-fee, late, and other Loan Guaranty payments to VA electronically instead of through legacy paper-based remittance. Client credentials only; sandbox available.

- **Human URL:** [https://developer.va.gov/explore/api/guaranty-remittance/docs](https://developer.va.gov/explore/api/guaranty-remittance/docs)
- **Base URL:** `https://api.va.gov/services/guaranty-remittance/v1`

#### Tags

- Government
- Veterans Affairs
- Home Loans
- Loan Guaranty
- Payments

#### Properties

- [Documentation](https://developer.va.gov/explore/api/guaranty-remittance/docs)
- [Authentication](https://developer.va.gov/explore/api/guaranty-remittance/client-credentials)
- [Postman Collection](collections/va-gov-address-validation-v3.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-address-validation-v3.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-appealable-issues-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-appealable-issues-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-appeals-status-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-appeals-status-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-appeals-status-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-appeals-status-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-claims-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-claims-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-claims-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-claims-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-documents-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-documents-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-intake-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-intake-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-reference-data-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-reference-data-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-community-care-eligibility-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-community-care-eligibility-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-direct-deposit-management-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-direct-deposit-management-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-facilities-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-facilities-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-facilities-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-facilities-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-forms-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-forms-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-legacy-appeals-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-legacy-appeals-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-loan-review-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-loan-review-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-va-letter-generator-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-va-letter-generator-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-confirmation-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-confirmation-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-confirmation-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-confirmation-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-verification-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-verification-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-verification-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-verification-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-verification-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-verification-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Health Care Costs Coverage API

Insurance-coordination API for VA's Consolidated Patient Account Center (CPAC) — submit and update third-party health insurance coverage on a Veteran's record so VA can correctly bill private insurers for non-service-connected care. Client credentials only; sandbox available.

- **Human URL:** [https://developer.va.gov/explore/api/health-care-costs-coverage/docs](https://developer.va.gov/explore/api/health-care-costs-coverage/docs)
- **Base URL:** `https://api.va.gov/services/health-care-costs-coverage/v1`

#### Tags

- Government
- Veterans Affairs
- Healthcare
- Insurance
- Coverage

#### Properties

- [Documentation](https://developer.va.gov/explore/api/health-care-costs-coverage/docs)
- [Authentication](https://developer.va.gov/explore/api/health-care-costs-coverage/client-credentials)
- [Postman Collection](collections/va-gov-address-validation-v3.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-address-validation-v3.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-appealable-issues-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-appealable-issues-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-appeals-status-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-appeals-status-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-appeals-status-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-appeals-status-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-claims-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-claims-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-claims-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-claims-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-documents-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-documents-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-intake-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-intake-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-benefits-reference-data-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-benefits-reference-data-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-community-care-eligibility-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-community-care-eligibility-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-direct-deposit-management-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-direct-deposit-management-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-facilities-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-facilities-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-facilities-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-facilities-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-forms-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-forms-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-legacy-appeals-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-legacy-appeals-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-loan-review-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-loan-review-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-va-letter-generator-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-va-letter-generator-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-confirmation-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-confirmation-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-confirmation-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-confirmation-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-verification-v0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-verification-v0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-verification-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-verification-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-gov-veteran-verification-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-gov-veteran-verification-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://developer.va.gov)
- [Portal](https://api.va.gov)
- [Documentation](https://developer.va.gov/explore)
- [Getting Started](https://developer.va.gov/onboarding)
- [Sign Up](https://developer.va.gov/onboarding/request-sandbox-access)
- [Authentication](https://developer.va.gov/explore/api/authorization-code)
- [Authentication](https://developer.va.gov/explore/api/client-credentials)
- [Documentation](https://developer.va.gov/onboarding/request-production-access)
- [Documentation](https://developer.va.gov/api-publishing)
- [Support](https://developer.va.gov/support)
- [Contact Email](mailto:api@va.gov)
- [Status Page](https://valighthouse.statuspage.io/)
- [Terms of Service](https://developer.va.gov/terms-of-service)
- [Privacy Policy](https://www.va.gov/privacy-policy/)
- [Documentation](https://www.va.gov/accessibility/)
- [Blog](https://news.va.gov/)
- [GitHub Organization](https://github.com/department-of-veterans-affairs)
- [Source Code](https://github.com/department-of-veterans-affairs/vets-api)
- [Source Code](https://github.com/department-of-veterans-affairs/vets-website)
- [Source Code](https://github.com/department-of-veterans-affairs/vets-api-clients)
- [Source Code](https://github.com/department-of-veterans-affairs/lighthouse-fhir-apis-consumer-docs)
- [Source Code](https://github.com/department-of-veterans-affairs/health-apis-bulk-fhir)
- [Source Code](https://github.com/department-of-veterans-affairs/health-apis-clinical-fhir)
- [Source Code](https://github.com/department-of-veterans-affairs/lighthouse-oas-tests)
- [Source Code](https://github.com/department-of-veterans-affairs/VHA-Facilities)
- [Documentation](https://developer.va.gov/api-publishing/getting-started)
- [Documentation](https://developer.va.gov/onboarding/working-with-lighthouse-apis)
- [Sandbox](https://sandbox-api.va.gov)
- [Authentication](https://api.va.gov/oauth2/authorization)
- [Authentication](https://api.va.gov/oauth2/token)
- [Authentication](https://api.va.gov/oauth2/revoke)
- [Documentation](http://docs.smarthealthit.org/)
- [Documentation](https://hl7.org/fhir/us/core/)
- [LinkedIn](https://www.linkedin.com/company/us-veteransaffairs/)
- [Terms of Service](https://www.va.gov/policy-and-compliance/notice-of-privacy-practices/)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
