# FASHN AI (fashn)

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
