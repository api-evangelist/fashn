# FASHN AI (fashn)

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

FASHN AI is an AI-first company specializing in human-centric generative image models tailored for fashion applications. The public API offers an asynchronous prediction workflow against a catalog of models including Try-On Max, Product to Model, Face to Model, Model Create, Model Swap, Edit, Reframe, Image to Video, and Background Remove.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/fashn/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/fashn/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- AI
- Clothing
- Fashion
- Virtual Try-On

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-05-19

## APIs

### FASHN

The FASHN API is an asynchronous prediction service. Clients POST to /v1/run with a model_name and model-specific inputs, then poll /v1/status/{id} until the prediction completes. Authentication uses a Bearer token. Rate limits: 50 req/60s on /run, 50 req/10s on /status, 6 concurrent predictions. CDN outputs are retained for 72 hours.

- **Human URL:** [https://fashn.ai/products/api](https://fashn.ai/products/api)
- **Base URL:** `https://api.fashn.ai/v1`

#### Tags

- Clothing
- Fashion
- AI
- Virtual Try-On

#### Properties

- [Documentation](https://fashn.ai/products/api)
- [A P I  Documentation](https://docs.fashn.ai/)
- [API Reference](https://docs.fashn.ai/api-overview/api-fundamentals)
- [Developer  Portal](https://app.fashn.ai/api)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/fashn/refs/heads/main/openapi/fashn-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fashn.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fashn.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/fashn-AI)
- [LinkedIn](https://www.linkedin.com/company/fashn)
- [Website](https://fashn.ai/)
- [Documentation](https://fashn.ai/products/api)
- [A P I  Documentation](https://docs.fashn.ai/)
- [Developer  Portal](https://app.fashn.ai/api)
- [L L Ms Txt](https://docs.fashn.ai/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
