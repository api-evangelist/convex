# Convex (convex)

Convex is a serverless backend platform that provides a real-time database, cloud functions, and infrastructure for building modern web and mobile applications. It offers a TypeScript-first developer experience with reactive queries, transactional mutations, and integrated file storage, all accessible through a suite of HTTP, management, and deployment APIs alongside JavaScript and server SDKs for full-stack application development. The platform is SOC 2 Type II, HIPAA, and GDPR compliant.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/convex/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/convex/refs/heads/main/apis.yml)

## Tags

- Backend
- Database
- Functions
- Real-Time
- Reactive
- Serverless
- TypeScript

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-05-29

## APIs

### Convex HTTP API

The Convex HTTP API is a REST interface for executing backend functions deployed on a Convex backend. It provides endpoints for invoking query, mutation, and action functions using POST requests to paths such as /api/query, /api/mutation, /api/action, and the unified /api/run/{functionIdentifier} endpoint. Each deployment has its own base URL found in the Convex dashboard settings, typically in the format https://{deployment-name}.convex.cloud.

- **Human URL:** [https://docs.convex.dev/http-api/](https://docs.convex.dev/http-api/)
- **Base URL:** `https://{deployment-name}.convex.cloud`

#### Tags

- Backend
- Functions
- Real-Time
- Serverless

#### Properties

- [Documentation](https://docs.convex.dev/http-api/)
- [OpenAPI](openapi/convex-http-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/convex-http-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/convex-http-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Convex Management API

The Convex Management API is a REST API for provisioning and managing Convex projects and deployments programmatically. It enables developers and platform integrations to create projects, list deployments, manage deploy keys, configure custom domains, and perform team-level operations without using the Convex dashboard. The API uses Bearer token authentication, supporting both Team Access Tokens and OAuth Application Tokens for third-party integrations.

- **Human URL:** [https://docs.convex.dev/management-api](https://docs.convex.dev/management-api)
- **Base URL:** `https://api.convex.dev/v1`

#### Tags

- Administration
- Deployments
- Management
- Projects

#### Properties

- [Documentation](https://docs.convex.dev/management-api)
- [OpenAPI](https://api.convex.dev/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/convex-management-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/convex-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/convex-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Convex Deployment Platform API

The Convex Deployment Platform API is a deployment-scoped administrative API for configuring individual Convex deployments. It exposes private endpoints accessible only to deployment administrators, supporting operations such as managing environment variables and other deployment configuration settings. Each deployment has its own endpoint in the format https://{deployment-name}.convex.cloud/api/v1/.

- **Human URL:** [https://docs.convex.dev/deployment-platform-api](https://docs.convex.dev/deployment-platform-api)
- **Base URL:** `https://{deployment-name}.convex.cloud/api/v1`

#### Tags

- Administration
- Configuration
- Deployment
- Environment Variables

#### Properties

- [Documentation](https://docs.convex.dev/deployment-platform-api)
- [OpenAPI](openapi/convex-deployment-platform-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/convex-deployment-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/convex-deployment-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Convex Sync Protocol

The Convex Sync Protocol is the bidirectional WebSocket protocol spoken between Convex client SDKs and the sync worker of a Convex deployment. Clients open a single WebSocket connection to wss://{deployment-name}.convex.cloud/api/{clientVersion}/sync and exchange JSON envelopes (discriminated by a `type` field) to authenticate, subscribe to reactive query sets, invoke mutations and actions, and receive query transitions, function responses, auth errors, fatal errors, and pings. The protocol is implemented in the open source convex-js client (`src/browser/sync/protocol.ts`).

- **Human URL:** [https://docs.convex.dev/understanding/](https://docs.convex.dev/understanding/)
- **Base URL:** `wss://{deployment-name}.convex.cloud/api/{clientVersion}/sync`

#### Tags

- Real-Time
- Reactive
- Sync
- WebSocket

#### Properties

- [Documentation](https://docs.convex.dev/understanding/)
- [Source Code](https://github.com/get-convex/convex-js/blob/main/src/browser/sync/protocol.ts)
- [AsyncAPI](asyncapi/convex-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/convex-deployment-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/convex-deployment-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/convex-http-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/convex-http-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/convex-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/convex-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Convex JavaScript SDK

The Convex JavaScript SDK is a collection of TypeScript/JavaScript packages for building applications on the Convex backend platform. It includes convex/server for defining backend functions and database schemas, convex/react for React hooks and the ConvexReactClient, convex/browser for the ConvexHttpClient in non-React browser environments, convex/values for working with Convex-stored data types, and framework integrations for Next.js, React Native, and other environments.

- **Human URL:** [https://docs.convex.dev/api/](https://docs.convex.dev/api/)

#### Tags

- Client Library
- JavaScript
- SDK
- TypeScript

#### Properties

- [Documentation](https://docs.convex.dev/api/)
- [Package](https://www.npmjs.com/package/convex)
- [Postman Collection](collections/convex-deployment-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/convex-deployment-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/convex-http-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/convex-http-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/convex-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/convex-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Convex Server SDK

The Convex Server SDK (convex/server) is the TypeScript library for defining backend logic deployed on Convex. It provides primitives for writing query functions for read-only database access, mutation functions for transactional writes, and action functions for general-purpose server-side operations including calling external services. The SDK supports schema definition, full-text search indexes, vector search indexes, file storage, scheduled functions, cron jobs, and HTTP routing via the HttpRouter class.

- **Human URL:** [https://docs.convex.dev/functions](https://docs.convex.dev/functions)

#### Tags

- Backend
- Database
- Serverless Functions
- TypeScript

#### Properties

- [Documentation](https://docs.convex.dev/functions)
- [Documentation](https://docs.convex.dev/database/schemas)
- [Postman Collection](collections/convex-deployment-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/convex-deployment-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/convex-http-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/convex-http-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/convex-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/convex-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/convex-dev)
- [Portal](https://www.convex.dev/developers)
- [Documentation](https://docs.convex.dev/)
- [Website](https://www.convex.dev)
- [Login](https://dashboard.convex.dev/)
- [Blog](https://stack.convex.dev/)
- [Git Hub](https://github.com/get-convex)
- [Discord](https://convex.dev/community)
- [Terms of Service](https://www.convex.dev/legal/terms)
- [Privacy Policy](https://www.convex.dev/legal/privacy)
- [JSON Schema](json-schema/convex-function-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/convex-deployment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/convex-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/convex-vocabulary.yml)
- [Integrations](https://www.convex.dev/partners)
- [M C P Server](https://stack.convex.dev/convex-mcp-server)
- [L L Ms Txt](https://docs.convex.dev/llms.txt)

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
