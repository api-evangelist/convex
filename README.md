# Convex

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

Convex is a serverless backend platform that provides a real-time database, cloud functions, and infrastructure for building modern web and mobile applications. It offers a TypeScript-first developer experience with reactive queries, transactional mutations, and integrated file storage, all accessible through a suite of HTTP, management, and deployment APIs alongside JavaScript and server SDKs for full-stack application development. The platform is SOC 2 Type II, HIPAA, and GDPR compliant.

**Areas:** Backend · Database · Functions · Real-Time · Reactive · Serverless · TypeScript

## Convex on APIs.io

Everything profiled for Convex is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/convex/](https://apis.io/providers/convex/)** — or go straight to one of the APIs or properties below.

### APIs (14)

- [Convex Sync Protocol](https://apis.io/apis/convex/sync-protocol/) — The Convex Sync Protocol is the bidirectional WebSocket protocol spoken between Convex client SDKs and the sync worker of a Convex deployment. Clients open…
- [Convex JavaScript SDK](https://apis.io/apis/convex/javascript-sdk/) — The Convex JavaScript SDK is a collection of TypeScript/JavaScript packages for building applications on the Convex backend platform. It includes…
- [Convex Server SDK](https://apis.io/apis/convex/server-sdk/) — The Convex Server SDK (convex/server) is the TypeScript library for defining backend logic deployed on Convex. It provides primitives for writing query…
- [Convex Actions API](https://apis.io/apis/convex/convex-actions-api/) — Execute action functions for general-purpose server-side operations, including calling external services, performing non-transactional work, and…
- [Convex DeployKeys API](https://apis.io/apis/convex/convex-deploykeys-api/) — Create and manage deploy keys for CLI operations and CI/CD pipelines. Deploy keys authenticate the Convex CLI when pushing function code to a deployment.
- [Convex Deployments API](https://apis.io/apis/convex/convex-deployments-api/) — Create, list, retrieve, update, and delete Convex cloud and local deployments. Deployments are the runtime environments where Convex backend functions execute.
- [Convex Functions API](https://apis.io/apis/convex/convex-functions-api/) — Execute any deployed function by its identifier using the unified run endpoint, which accepts the function type implicitly based on the deployed function…
- [Convex Mutations API](https://apis.io/apis/convex/convex-mutations-api/) — Execute mutation functions that perform transactional writes to the Convex database. Mutations are strongly consistent and run with ACID guarantees.
- [Convex Projects API](https://apis.io/apis/convex/convex-projects-api/) — Create, list, retrieve, and delete Convex projects within a team. Projects group deployments and serve as the top-level organizational unit for Convex…
- [Convex Queries API](https://apis.io/apis/convex/convex-queries-api/) — Execute read-only query functions deployed on the Convex backend. Queries run in a transactional, reactive context and return data from the Convex database.
- [Convex Teams API](https://apis.io/apis/convex/convex-teams-api/) — Manage Convex teams, team members, and team-level access tokens. Teams are the billing and administrative unit that owns projects.
- [Convex Access Tokens API](https://apis.io/apis/convex/convex-access-tokens-api/) — Create and manage Team Access Tokens used for authenticating Management API requests on behalf of a team.
- [Convex Custom Domains API](https://apis.io/apis/convex/convex-custom-domains-api/) — Configure custom domain names for Convex deployments. Supports both convexCloud (function API) and convexSite (HTTP actions) request destinations.
- [Convex Environment Variables API](https://apis.io/apis/convex/convex-environment-variables-api/) — Manage environment variables for a Convex deployment. Environment variables are key-value pairs accessible to backend functions at runtime via process.env.…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Convex Sync Protocol](https://apis.io/asyncapis/convex/convex-asyncapi/)

#### Event channels (1)

Individual events and webhooks the provider emits.

- [/api/{clientVersion}/sync](https://apis.io/channels/convex/api-clientversion-sync/)

#### MCP servers (2)

Model Context Protocol servers that expose the API to agents.

- [convex](https://apis.io/servers/convex/convex/)
- [MCP Server](https://apis.io/servers/convex/mcp-server/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Convex Agentic Access](https://apis.io/agentic-access/convex/convex-agentic-access/)

#### JSON Schema (17)

The data models the API reads and writes.

- [AccessToken](https://apis.io/schemas/convex/convex-accesstoken/)
- [CreateAccessTokenRequest](https://apis.io/schemas/convex/convex-createaccesstokenrequest/)
- [CreateCloudDeploymentRequest](https://apis.io/schemas/convex/convex-createclouddeploymentrequest/)
- [CreateCustomDomainRequest](https://apis.io/schemas/convex/convex-createcustomdomainrequest/)
- [CreateDeployKeyRequest](https://apis.io/schemas/convex/convex-createdeploykeyrequest/)
- [CreateProjectRequest](https://apis.io/schemas/convex/convex-createprojectrequest/)
- [CustomDomain](https://apis.io/schemas/convex/convex-customdomain/)
- [DeployKey](https://apis.io/schemas/convex/convex-deploykey/)
- [Convex Deployment](https://apis.io/schemas/convex/convex-deployment/)
- [EnvironmentVariable](https://apis.io/schemas/convex/convex-environmentvariable/)
- [Convex Function](https://apis.io/schemas/convex/convex-function/)
- [FunctionErrorResponse](https://apis.io/schemas/convex/convex-functionerrorresponse/)
- [FunctionRequest](https://apis.io/schemas/convex/convex-functionrequest/)
- [FunctionSuccessResponse](https://apis.io/schemas/convex/convex-functionsuccessresponse/)
- [Project](https://apis.io/schemas/convex/convex-project/)
- [RunFunctionRequest](https://apis.io/schemas/convex/convex-runfunctionrequest/)
- [TeamMember](https://apis.io/schemas/convex/convex-teammember/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Convex Structure](https://apis.io/json-structure/convex/convex-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Convex Context](https://apis.io/jsonld/convex/convex-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Convex Backend Platform Vocabulary](https://apis.io/vocabularies/convex/convex-vocabulary/)

#### Collections (25)

Postman and Open Collection request collections.

- [Convex Deployment Platform AccessTokens API](https://apis.io/collections/convex/open-convex-accesstokens-api/)
- [Convex Deployment Platform AccessTokens Actions API](https://apis.io/collections/convex/open-convex-actions-api/)
- [Convex Deployment Platform AccessTokens CustomDomains API](https://apis.io/collections/convex/open-convex-customdomains-api/)
- [Convex Deployment Platform AccessTokens DeployKeys API](https://apis.io/collections/convex/open-convex-deploykeys-api/)
- [Convex Deployment Platform API](https://apis.io/collections/convex/open-convex-deployment-platform-api/)
- [Convex Deployment Platform AccessTokens Deployments API](https://apis.io/collections/convex/open-convex-deployments-api/)
- [Convex Deployment Platform AccessTokens EnvironmentVariables API](https://apis.io/collections/convex/open-convex-environmentvariables-api/)
- [Convex Deployment Platform AccessTokens Functions API](https://apis.io/collections/convex/open-convex-functions-api/)
- [Convex HTTP API](https://apis.io/collections/convex/open-convex-http-api/)
- [Convex Management API](https://apis.io/collections/convex/open-convex-management-api/)
- [Convex Deployment Platform AccessTokens Mutations API](https://apis.io/collections/convex/open-convex-mutations-api/)
- [Convex Deployment Platform AccessTokens Projects API](https://apis.io/collections/convex/open-convex-projects-api/)
- [Convex Deployment Platform AccessTokens Queries API](https://apis.io/collections/convex/open-convex-queries-api/)
- [Convex Deployment Platform AccessTokens Teams API](https://apis.io/collections/convex/open-convex-teams-api/)
- [Convex Deployment Platform AccessTokens API](https://apis.io/collections/convex/postman-convex-accesstokens-api/)
- [Convex Deployment Platform AccessTokens Actions API](https://apis.io/collections/convex/postman-convex-actions-api/)
- [Convex Deployment Platform AccessTokens CustomDomains API](https://apis.io/collections/convex/postman-convex-customdomains-api/)
- [Convex Deployment Platform AccessTokens DeployKeys API](https://apis.io/collections/convex/postman-convex-deploykeys-api/)
- [Convex Deployment Platform AccessTokens Deployments API](https://apis.io/collections/convex/postman-convex-deployments-api/)
- [Convex Deployment Platform AccessTokens EnvironmentVariables API](https://apis.io/collections/convex/postman-convex-environmentvariables-api/)
- [Convex Deployment Platform AccessTokens Functions API](https://apis.io/collections/convex/postman-convex-functions-api/)
- [Convex Deployment Platform AccessTokens Mutations API](https://apis.io/collections/convex/postman-convex-mutations-api/)
- [Convex Deployment Platform AccessTokens Projects API](https://apis.io/collections/convex/postman-convex-projects-api/)
- [Convex Deployment Platform AccessTokens Queries API](https://apis.io/collections/convex/postman-convex-queries-api/)
- [Convex Deployment Platform AccessTokens Teams API](https://apis.io/collections/convex/postman-convex-teams-api/)

#### Governance rules (5)

Spectral rulesets for the provider's contracts.

- [Convex — asyncapi rules](https://apis.io/rules/convex/convex-asyncapi-spectral-rules/)
- [Convex — deployment platform api rules](https://apis.io/rules/convex/convex-deployment-platform-api-rules/)
- [Convex — http api rules](https://apis.io/rules/convex/convex-http-api-rules/)
- [Convex — jsonschema rules](https://apis.io/rules/convex/convex-jsonschema-spectral-rules/)
- [Convex — management api rules](https://apis.io/rules/convex/convex-management-api-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Convex Authentication](https://apis.io/security/convex/convex-authentication/)
- [Convex Domain Security](https://apis.io/security/convex/convex-domain-security/)
- [Convex Trust Center](https://apis.io/security/convex/convex-trust-center/)
- [Convex Vulnerability Disclosure](https://apis.io/security/convex/convex-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Convex Plans Pricing](https://apis.io/plans/convex/convex-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Convex Rate Limits](https://apis.io/rate-limits/convex/convex-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Convex Finops](https://apis.io/finops/convex/convex-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.convex.dev)
- [Documentation](https://docs.convex.dev/)
- [Blog](https://stack.convex.dev/)
- [Terms of service](https://www.convex.dev/legal/terms)
- [Privacy policy](https://www.convex.dev/legal/privacy)

## API Evangelist rating

**Kin Score 44.8** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.7 |
| Contract quality | 60.3 |
| Contract governance | 27.3 |
| Operational transparency | 23.7 |
| Developer ergonomics | 39.3 |
| Access clarity | 32.9 |

**Agent readiness 33.6** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 31.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/convex/](https://apis.io/providers/convex/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Convex: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/convex/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
