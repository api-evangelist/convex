# Convex (convex)
Convex is a serverless backend platform that provides real-time database, cloud functions, and infrastructure for building modern web and mobile applications. It offers a TypeScript-first developer experience with reactive queries, transactional mutations, and integrated file storage, all accessible through a suite of APIs and SDKs. The Convex developer platform includes HTTP, management, and deployment APIs alongside JavaScript and server SDKs for full-stack application development.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/convex/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Serverless, Real-Time, Backend, Database, Functions

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-03-21

## APIs

### Convex HTTP API
The Convex HTTP API is a REST interface for executing backend functions deployed on a Convex backend. It provides endpoints for invoking query, mutation, and action functions using POST requests to paths such as /api/query, /api/mutation, /api/action, and the unified /api/run/{functionIdentifier} endpoint. Each deployment has its own base URL found in the Convex dashboard settings, typically in the format https://{deployment-name}.convex.cloud. Requests accept a function path and named argument object as JSON, and responses include the function return value along with execution log lines.

**Human URL:** [https://docs.convex.dev/http-api/](https://docs.convex.dev/http-api/)


#### Tags:

 - Serverless, Real-Time, Backend, Functions

#### Properties

- [Documentation](https://docs.convex.dev/http-api/)
- [OpenAPI](openapi/convex-http-api-openapi.yml)

### Convex Management API
The Convex Management API is a REST API for provisioning and managing Convex projects and deployments programmatically. It enables developers and platform integrations to create projects, list deployments, and perform team-level operations without using the Convex dashboard. The API uses Bearer token authentication, supporting both Team Access Tokens and OAuth Application Tokens for third-party integrations. A JavaScript client wrapper is available through the @convex-dev/platform npm package, and an OpenAPI specification is published at https://api.convex.dev/v1/openapi.json.

**Human URL:** [https://docs.convex.dev/management-api](https://docs.convex.dev/management-api)


#### Tags:

 - Management, Deployments, Projects, Administration

#### Properties

- [Documentation](https://docs.convex.dev/management-api)
- [OpenAPI](https://api.convex.dev/v1/openapi.json)
- [OpenAPI](openapi/convex-management-api-openapi.yml)

### Convex Deployment Platform API
The Convex Deployment Platform API is a deployment-scoped administrative API for configuring individual Convex deployments. It exposes private endpoints accessible only to deployment administrators, supporting operations such as managing environment variables and other deployment configuration settings. Each deployment has its own endpoint in the format https://{deployment-name}.convex.cloud/api/v1/. Authentication requires an Authorization header using deployment keys, Team Access Tokens, or OAuth Application Tokens formatted as "Convex {token}". This API is currently in beta and intended for platform integrations and infrastructure automation workflows.

**Human URL:** [https://docs.convex.dev/deployment-platform-api](https://docs.convex.dev/deployment-platform-api)


#### Tags:

 - Deployment, Administration, Configuration, Environment Variables

#### Properties

- [Documentation](https://docs.convex.dev/deployment-platform-api)
- [OpenAPI](openapi/convex-deployment-platform-api-openapi.yml)

### Convex JavaScript SDK
The Convex JavaScript SDK is a collection of TypeScript/JavaScript packages for building applications on the Convex backend platform. It includes convex/server for defining backend functions and database schemas, convex/react for React hooks and the ConvexReactClient, convex/browser for the ConvexHttpClient in non-React browser environments, convex/values for working with Convex-stored data types, and framework integrations for Next.js, React Native, and other environments. The SDK provides real-time reactive queries that automatically update when underlying data changes, as well as strongly typed database access generated from the project schema.

**Human URL:** [https://docs.convex.dev/api/](https://docs.convex.dev/api/)


#### Tags:

 - JavaScript, TypeScript, SDK, Client Library

#### Properties

- [Documentation](https://docs.convex.dev/api/)

### Convex Server SDK
The Convex Server SDK (convex/server) is the TypeScript library for defining backend logic deployed on Convex. It provides primitives for writing query functions for read-only database access, mutation functions for transactional writes, and action functions for general-purpose server-side operations including calling external services. The SDK supports schema definition, full-text search indexes, vector search indexes, file storage, scheduled functions, cron jobs, and HTTP routing via the HttpRouter class. Running npx convex dev generates strongly typed database access code tailored to the project schema.

**Human URL:** [https://docs.convex.dev/functions](https://docs.convex.dev/functions)


#### Tags:

 - TypeScript, Serverless Functions, Database, Backend

#### Properties

- [Documentation](https://docs.convex.dev/functions)

## Common Properties

- [Portal](https://www.convex.dev/developers)
- [Documentation](https://docs.convex.dev/)
- [Website](https://www.convex.dev)
- [Login](https://dashboard.convex.dev/)
- [Blog](https://stack.convex.dev/)
- [TermsOfService](https://www.convex.dev/legal/terms)
- [PrivacyPolicy](https://www.convex.dev/legal/privacy)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
