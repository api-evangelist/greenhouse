# Greenhouse (greenhouse)

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

Greenhouse is an applicant tracking system (ATS) and recruiting software platform. It exposes a family of APIs and webhooks that let partners and customers manage candidates, jobs, applications, onboarding, audit logs, and assessment integrations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/greenhouse/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/greenhouse/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- ATS
- Recruiting
- Candidates
- Jobs
- Onboarding
- HR

## Timestamps

- **Created:** 2025-01-07
- **Modified:** 2026-05-19

## APIs

### Greenhouse Harvest API

The Harvest API provides programmatic access to Greenhouse Recruiting data, including candidates, applications, jobs, departments, offices, and users.

- **Human URL:** [https://developers.greenhouse.io/harvest.html](https://developers.greenhouse.io/harvest.html)
- **Base URL:** `https://harvest.greenhouse.io/v1`

#### Tags

- Harvest
- Candidates
- Jobs
- Applications

#### Properties

- [Documentation](https://developers.greenhouse.io/harvest.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/greenhouse/refs/heads/main/openapi/greenhouse-harvest-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/greenhouse-harvest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-harvest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/greenhouse-ingestion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-ingestion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/greenhouse-job-board.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-job-board.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/greenhouse-onboarding.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-onboarding.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Greenhouse Job Board API

The Job Board API enables building careers pages with custom look and feel, retrieving jobs, offices, departments, sections, education reference data, and submitting applications.

- **Human URL:** [https://developers.greenhouse.io/job-board.html](https://developers.greenhouse.io/job-board.html)
- **Base URL:** `https://boards-api.greenhouse.io/v1/boards`

#### Tags

- Job Board
- Careers
- Jobs

#### Properties

- [Documentation](https://developers.greenhouse.io/job-board.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/greenhouse/refs/heads/main/openapi/greenhouse-job-board-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/greenhouse-harvest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-harvest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/greenhouse-ingestion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-ingestion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/greenhouse-job-board.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-job-board.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/greenhouse-onboarding.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-onboarding.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Greenhouse Candidate Ingestion API

The Ingestion API enables sourcing partners to submit prospects and candidates to Greenhouse and to retrieve job and prospect pool information.

- **Human URL:** [https://developers.greenhouse.io/candidate-ingestion.html](https://developers.greenhouse.io/candidate-ingestion.html)
- **Base URL:** `https://api.greenhouse.io/v1/partner`

#### Tags

- Ingestion
- Candidates
- Sourcing

#### Properties

- [Documentation](https://developers.greenhouse.io/candidate-ingestion.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/greenhouse/refs/heads/main/openapi/greenhouse-ingestion-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/greenhouse-harvest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-harvest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/greenhouse-ingestion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-ingestion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/greenhouse-job-board.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-job-board.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/greenhouse-onboarding.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-onboarding.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Greenhouse Onboarding API

A GraphQL API for Greenhouse Onboarding. Provides queries and mutations for employees, departments, locations, custom fields, teams, and pending hires.

- **Human URL:** [https://developers.greenhouse.io/gho.html](https://developers.greenhouse.io/gho.html)
- **Base URL:** `https://onboarding-api.greenhouse.io/graphql`

#### Tags

- Onboarding
- GraphQL
- Employees

#### Properties

- [Documentation](https://developers.greenhouse.io/gho.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/greenhouse/refs/heads/main/openapi/greenhouse-onboarding-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/greenhouse-harvest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-harvest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/greenhouse-ingestion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-ingestion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/greenhouse-job-board.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-job-board.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/greenhouse-onboarding.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-onboarding.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Greenhouse Assessment API

The Assessment Partner API enables assessment platforms (code testing, video interviewing, personality testing) to seamlessly integrate with the Greenhouse interview workflow.

- **Human URL:** [https://developers.greenhouse.io/assessment.html](https://developers.greenhouse.io/assessment.html)

#### Tags

- Assessment
- Testing
- Candidates

#### Properties

- [Documentation](https://developers.greenhouse.io/assessment.html)
- [Postman Collection](collections/greenhouse-harvest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-harvest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/greenhouse-ingestion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-ingestion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/greenhouse-job-board.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-job-board.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/greenhouse-onboarding.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-onboarding.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Greenhouse Audit Log API

The Audit Log API offers a record of important events, providing insight into who accessed or edited information in Greenhouse.

- **Human URL:** [https://developers.greenhouse.io/audit-log.html](https://developers.greenhouse.io/audit-log.html)

#### Tags

- Audit
- Compliance
- Logging

#### Properties

- [Documentation](https://developers.greenhouse.io/audit-log.html)
- [Postman Collection](collections/greenhouse-harvest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-harvest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/greenhouse-ingestion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-ingestion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/greenhouse-job-board.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-job-board.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/greenhouse-onboarding.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-onboarding.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Greenhouse Recruiting Webhooks

Recruiting Webhooks deliver event notifications for Greenhouse Recruiting activities such as candidate updates, application stage changes, and offers.

- **Human URL:** [https://developers.greenhouse.io/webhooks.html](https://developers.greenhouse.io/webhooks.html)

#### Tags

- Webhooks
- Recruiting
- Events

#### Properties

- [Documentation](https://developers.greenhouse.io/webhooks.html)
- [Postman Collection](collections/greenhouse-harvest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-harvest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/greenhouse-ingestion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-ingestion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/greenhouse-job-board.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-job-board.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/greenhouse-onboarding.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-onboarding.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Greenhouse Onboarding Webhooks

Onboarding Webhooks deliver event notifications for Greenhouse Onboarding activities such as new hires and employee updates.

- **Human URL:** [https://developers.greenhouse.io/onboarding_webhooks.html](https://developers.greenhouse.io/onboarding_webhooks.html)

#### Tags

- Webhooks
- Onboarding
- Events

#### Properties

- [Documentation](https://developers.greenhouse.io/onboarding_webhooks.html)
- [Postman Collection](collections/greenhouse-harvest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-harvest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/greenhouse-ingestion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-ingestion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/greenhouse-job-board.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-job-board.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/greenhouse-onboarding.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenhouse-onboarding.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/greenhouse-inc-)
- [Documentation](https://developers.greenhouse.io)
- [Git Hub Org](https://github.com/grnhse)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
