# Convex (convex)
Convex is a serverless backend platform that provides a real-time database, cloud functions, and infrastructure for building modern web and mobile applications. It offers a TypeScript-first developer experience with reactive queries, transactional mutations, and integrated file storage, all accessible through a suite of HTTP, management, and deployment APIs alongside JavaScript and server SDKs for full-stack application development. The platform is SOC 2 Type II, HIPAA, and GDPR compliant.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/convex/refs/heads/main/apis.yml)

## Type

- **x-type:** company

## Tags:

 - Backend, Database, Functions, Real-Time, Reactive, Serverless, TypeScript

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-04-28

## APIs

### Convex HTTP API
The Convex HTTP API is a REST interface for executing backend functions deployed on a Convex backend. It provides endpoints for invoking query, mutation, and action functions using POST requests to paths such as /api/query, /api/mutation, /api/action, and the unified /api/run/{functionIdentifier} endpoint. Each deployment has its own base URL found in the Convex dashboard settings, typically in the format https://{deployment-name}.convex.cloud.

**Human URL:** [https://docs.convex.dev/http-api/](https://docs.convex.dev/http-api/)

#### Tags:

 - Backend, Functions, Real-Time, Serverless

#### Properties

- [Documentation](https://docs.convex.dev/http-api/)
- [OpenAPI](openapi/convex-http-api-openapi.yml)

#### Features

- POST /api/query for reactive read-only function execution
- POST /api/mutation for transactional database writes
- POST /api/action for general-purpose server-side operations
- POST /api/run/{functionIdentifier} unified function invocation
- Optional bearer token auth for end users, Convex scheme for admin

#### Use Cases

- Calling Convex functions from non-JavaScript backends
- Server-to-server orchestration of Convex queries and mutations
- Webhook handlers that trigger Convex actions
- Lightweight scripts that execute one-off function calls
- Testing deployed Convex functions from curl or HTTPie

### Convex Management API
The Convex Management API is a REST API for provisioning and managing Convex projects and deployments programmatically. It enables developers and platform integrations to create projects, list deployments, manage deploy keys, configure custom domains, and perform team-level operations without using the Convex dashboard. The API uses Bearer token authentication, supporting both Team Access Tokens and OAuth Application Tokens for third-party integrations.

**Human URL:** [https://docs.convex.dev/management-api](https://docs.convex.dev/management-api)

#### Tags:

 - Administration, Deployments, Management, Projects

#### Properties

- [Documentation](https://docs.convex.dev/management-api)
- [OpenAPI](https://api.convex.dev/v1/openapi.json)
- [OpenAPI](openapi/convex-management-api-openapi.yml)

#### Features

- Projects and deployments lifecycle management
- Deploy key and preview deploy key issuance
- Personal access tokens and team access tokens
- Custom domain attachment for production deployments
- Default environment variables and team membership management
- Published OpenAPI spec at https://api.convex.dev/v1/openapi.json

#### Use Cases

- Building Convex platform integrations and CI/CD pipelines
- Provisioning preview deployments per pull request
- Automating environment variable configuration for new projects
- Inviting team members and rotating credentials programmatically
- Listing all deployments for governance and inventory tooling

### Convex Deployment Platform API
The Convex Deployment Platform API is a deployment-scoped administrative API for configuring individual Convex deployments. It exposes private endpoints accessible only to deployment administrators, supporting operations such as managing environment variables and other deployment configuration settings. Each deployment has its own endpoint in the format https://{deployment-name}.convex.cloud/api/v1/.

**Human URL:** [https://docs.convex.dev/deployment-platform-api](https://docs.convex.dev/deployment-platform-api)

#### Tags:

 - Administration, Configuration, Deployment, Environment Variables

#### Properties

- [Documentation](https://docs.convex.dev/deployment-platform-api)
- [OpenAPI](openapi/convex-deployment-platform-api-openapi.yml)

#### Features

- Deployment-scoped administrative access
- Environment variable configuration management
- Bearer token Authorization with the Convex scheme
- Beta API surface intended for platform integrations

#### Use Cases

- Pushing environment variable updates from CI/CD pipelines
- Reading deployment configuration for IaC drift detection
- Building admin tooling that targets a specific deployment
- Synchronizing config across multiple Convex deployments

### Convex JavaScript SDK
The Convex JavaScript SDK is a collection of TypeScript/JavaScript packages for building applications on the Convex backend platform. It includes convex/server for defining backend functions and database schemas, convex/react for React hooks and the ConvexReactClient, convex/browser for the ConvexHttpClient in non-React browser environments, convex/values for working with Convex-stored data types, and framework integrations for Next.js, React Native, and other environments.

**Human URL:** [https://docs.convex.dev/api/](https://docs.convex.dev/api/)

#### Tags:

 - Client Library, JavaScript, SDK, TypeScript

#### Properties

- [Documentation](https://docs.convex.dev/api/)
- [Package](https://www.npmjs.com/package/convex)

#### Features

- ConvexReactClient with reactive useQuery, useMutation hooks
- ConvexHttpClient for non-React JavaScript runtimes
- Strongly typed client generated from project schema
- Authentication helpers for Clerk, Auth0, and custom providers
- Framework integrations for Next.js, React Native, and Svelte

#### Use Cases

- Building real-time React applications backed by Convex
- Embedding Convex queries in Next.js server components
- Server-rendered apps that read Convex data on the server
- Cross-platform mobile apps using React Native and Convex

### Convex Server SDK
The Convex Server SDK (convex/server) is the TypeScript library for defining backend logic deployed on Convex. It provides primitives for writing query functions for read-only database access, mutation functions for transactional writes, and action functions for general-purpose server-side operations including calling external services. The SDK supports schema definition, full-text search indexes, vector search indexes, file storage, scheduled functions, cron jobs, and HTTP routing via the HttpRouter class.

**Human URL:** [https://docs.convex.dev/functions](https://docs.convex.dev/functions)

#### Tags:

 - Backend, Database, Serverless Functions, TypeScript

#### Properties

- [Documentation](https://docs.convex.dev/functions)
- [Documentation](https://docs.convex.dev/database/schemas)

#### Features

- query, mutation, and action function primitives
- defineSchema and defineTable for typed database modeling
- Full-text and vector search indexes
- Cron jobs and scheduled function execution
- HttpRouter for custom HTTP endpoints
- File storage with signed URL generation

#### Use Cases

- Authoring Convex backend functions in TypeScript
- Modeling reactive database schemas with type safety
- Implementing AI workflows with vector search
- Scheduling recurring background work with cron jobs
- Building HTTP webhook handlers inside Convex deployments

## Common Properties

- [Portal](https://www.convex.dev/developers)
- [Documentation](https://docs.convex.dev/)
- [Website](https://www.convex.dev)
- [Login](https://dashboard.convex.dev/)
- [Blog](https://stack.convex.dev/)
- [GitHub](https://github.com/get-convex)
- [Discord](https://convex.dev/community)
- [TermsOfService](https://www.convex.dev/legal/terms)
- [PrivacyPolicy](https://www.convex.dev/legal/privacy)
- [JSONSchema](json-schema/convex-function-schema.json)
- [JSONSchema](json-schema/convex-deployment-schema.json)
- [JSON-LD](json-ld/convex-context.jsonld)
- [Vocabulary](vocabulary/convex-vocabulary.yml)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
