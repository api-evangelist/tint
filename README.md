# Tint (tint)

Tint is an embedded protection / insurance-as-a-service infrastructure provider whose Hermes platform lets tech platforms launch and operate embedded insurance programs. The Tint API v2 exposes programmatic quoting, binding, policy lifecycle management, endorsements, claims, payments, and webhooks under a single Bearer-authenticated REST surface at https://api.tint.ai/v2.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tint/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tint/refs/heads/main/apis.yml)

## Tags

- Insurance
- Embedded Insurance
- InsurTech
- Insurance as a Service
- Protection

## Timestamps

- **Created:** 2026-06-25
- **Modified:** 2026-06-25

## APIs

### Tint Programs API

Lists the embedded insurance products (programs) configured for an account and the plans available within each product, the building blocks platforms quote and bind policies against.

- **Human URL:** [https://docs.tint.ai](https://docs.tint.ai)
- **Base URL:** `https://api.tint.ai/v2`

#### Tags

- Programs
- Insurance Products
- Plans

#### Properties

- [Documentation](https://docs.tint.ai)
- [OpenAPI](openapi/tint-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tint.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tint.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tint Quotes API

Retrieves rated plan quotes for a policy via the Rating Engine. Coverage details are returned inline within quotes rather than as a standalone resource.

- **Human URL:** [https://docs.tint.ai](https://docs.tint.ai)
- **Base URL:** `https://api.tint.ai/v2`

#### Tags

- Quotes
- Rating
- Coverages

#### Properties

- [Documentation](https://docs.tint.ai)
- [OpenAPI](openapi/tint-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tint.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tint.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tint Policies API

Full policy lifecycle - create, retrieve, update, issue, report usage, record payment, cancel, and void - plus endorsement workflows for mid-term changes with their own quote and decision sub-resources.

- **Human URL:** [https://docs.tint.ai](https://docs.tint.ai)
- **Base URL:** `https://api.tint.ai/v2`

#### Tags

- Policies
- Endorsements
- Lifecycle

#### Properties

- [Documentation](https://docs.tint.ai)
- [OpenAPI](openapi/tint-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tint.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tint.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tint Claims API

End-to-end claims handling from first notice of loss through receive, review, approve, settle, deny, or withdraw, with notes, document upload URLs, and claim payments.

- **Human URL:** [https://docs.tint.ai](https://docs.tint.ai)
- **Base URL:** `https://api.tint.ai/v2`

#### Tags

- Claims
- FNOL
- Payments

#### Properties

- [Documentation](https://docs.tint.ai)
- [OpenAPI](openapi/tint-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tint.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tint.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tint Decisions API

Calculates and retrieves Decision Engine decisions and Score Module scores for a policy, enforcing the business rules that drive underwriting and pricing.

- **Human URL:** [https://docs.tint.ai](https://docs.tint.ai)
- **Base URL:** `https://api.tint.ai/v2`

#### Tags

- Decision Engine
- Underwriting
- Scores

#### Properties

- [Documentation](https://docs.tint.ai)
- [OpenAPI](openapi/tint-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tint.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tint.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tint Questionnaires API

Retrieves the questionnaire definition attached to a policy by slug, used to collect the underwriting and rating data a program requires.

- **Human URL:** [https://docs.tint.ai](https://docs.tint.ai)
- **Base URL:** `https://api.tint.ai/v2`

#### Tags

- Questionnaires
- Data Collection

#### Properties

- [Documentation](https://docs.tint.ai)
- [OpenAPI](openapi/tint-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tint.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tint.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tint Webhooks API

Real-time event notifications for the policy lifecycle (CREATED, ISSUED, CANCELLED, ENDORSED, RENEWED, PAYMENT, USAGE_REPORTED, VOID) and claims (CREATED, APPROVED, SETTLED, DENIED, payment events, and more) with retry and delivery assurance.

- **Human URL:** [https://docs.tint.ai/webhooks](https://docs.tint.ai/webhooks)
- **Base URL:** `https://api.tint.ai/v2`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://docs.tint.ai/webhooks)
- [OpenAPI](openapi/tint-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tint.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tint.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/tint-ai)
- [LinkedIn](https://www.linkedin.com/company/tint-ai)
- [Website](https://www.tint.ai)
- [Documentation](https://docs.tint.ai)
- [Plans](plans/tint-plans-pricing.yml)
- [Rate Limits](rate-limits/tint-rate-limits.yml)
- [Fin Ops](finops/tint-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
