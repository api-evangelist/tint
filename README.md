# Tint (tint)

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
