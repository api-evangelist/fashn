# FASHN AI (fashn)

FASHN AI is an AI-first company specializing in human-centric generative image models tailored for fashion applications. The public API exposes an asynchronous prediction workflow against a catalog of models including Try-On Max, Product to Model, Face to Model, Model Create, Model Swap, Edit, Reframe, Image to Video, and Background Remove.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/fashn/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags:

- AI, Clothing, Fashion, Virtual Try-On

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-04-28

## APIs

### FASHN

The FASHN API is an asynchronous prediction service. Clients submit a job by POSTing to `/v1/run` with a `model_name` and model-specific `inputs`, then poll `/v1/status/{id}` until the prediction reaches a terminal state. Authentication is via Bearer token. Rate limits: 50 req/60s on `/run`, 50 req/10s on `/status`, with a concurrency cap of 6. CDN output URLs are valid for 72 hours; base64 outputs for 60 minutes.

**Human URL:** [https://fashn.ai/products/api](https://fashn.ai/products/api)

**Base URL:** `https://api.fashn.ai/v1`

#### Tags:

- AI, Clothing, Fashion, Virtual Try-On

#### Properties

- [Documentation](https://fashn.ai/products/api)
- [API Documentation](https://docs.fashn.ai/)
- [API Reference](https://docs.fashn.ai/api-overview/api-fundamentals)
- [Developer Portal](https://app.fashn.ai/api)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/fashn/refs/heads/main/openapi/fashn-openapi.yml)

## Common Properties

- [Website](https://fashn.ai/)
- [Documentation](https://fashn.ai/products/api)
- [API Documentation](https://docs.fashn.ai/)
- [Developer Portal](https://app.fashn.ai/api)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
