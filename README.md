# Deepnote (deepnote)

Deepnote is a collaborative data-science notebook and analytics/app platform. Its Public API v2 (preview) lets you programmatically run notebooks, poll execution runs, and manage projects, notebooks, files, and integrations, with notebooks also embeddable as data apps. Authentication is a workspace API key sent as a Bearer token.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/deepnote/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/deepnote/refs/heads/main/apis.yml)

## Tags

- Data Science
- Notebooks
- Analytics
- Collaboration
- Data Apps

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Deepnote Execution API (Notebooks/Projects)

Programmatically run an existing notebook and poll its execution run. POST /runs starts a run (optionally detached, with selected blocks, dependent blocks, and input values); GET /runs/{runId} returns run status and results. Legacy v1 execute endpoint triggers a notebook's machine. Auth is a workspace API key as a Bearer token.

- **Human URL:** [https://deepnote.com/docs/deepnote-api](https://deepnote.com/docs/deepnote-api)
- **Base URL:** `https://api.deepnote.com/v2`

#### Tags

- Execution
- Runs
- Notebooks

#### Properties

- [Documentation](https://deepnote.com/docs/deepnote-api)
- [API Reference](https://deepnote.com/docs/api-reference)
- [OpenAPI](openapi/deepnote-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/deepnote.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/deepnote.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Deepnote Projects API

List, create, get, and delete projects, plus create/get/delete notebooks within a project, list a notebook's historical runs, and introspect the calling API key, user, workspace, and access level via /me.

- **Human URL:** [https://deepnote.com/docs/api-reference](https://deepnote.com/docs/api-reference)
- **Base URL:** `https://api.deepnote.com/v2`

#### Tags

- Projects
- Notebooks
- Management

#### Properties

- [API Reference](https://deepnote.com/docs/api-reference)
- [OpenAPI](openapi/deepnote-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/deepnote.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/deepnote.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Deepnote Embed

Publish and embed Deepnote notebooks and data apps in external sites and dashboards via shareable embed/app URLs. This is a publishing/embedding surface rather than a JSON REST API.

- **Human URL:** [https://deepnote.com/docs](https://deepnote.com/docs)
- **Base URL:** `https://deepnote.com`

#### Tags

- Embed
- Data Apps
- Sharing

#### Properties

- [Documentation](https://deepnote.com/docs)

## Common Properties

- [GitHub Organization](https://github.com/deepnote)
- [LinkedIn](https://www.linkedin.com/company/deepnote)
- [Website](https://deepnote.com)
- [Documentation](https://deepnote.com/docs)
- [Plans](plans/deepnote-plans-pricing.yml)
- [Rate Limits](rate-limits/deepnote-rate-limits.yml)
- [Fin Ops](finops/deepnote-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
