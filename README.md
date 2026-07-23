# Avamar

Avamar is enterprise backup and recovery software built on client-side global data deduplication. Founded in Irvine, California and backed by Lightspeed Venture Partners, it was acquired by EMC in November 2006 for approximately $165 million and now ships as **Dell Avamar**, part of the Dell Technologies data protection portfolio.

Avamar is **customer-hosted** — an appliance, a Data Store grid, or a virtual edition — so its REST API runs on the customer's own server rather than on a Dell-operated multi-tenant host. That shapes every artifact in this repo.

## API surface

- **Base path** — `https://<AvamarServer>/api/v1`
- **Description** — Swagger UI served from the appliance at `https://<AvamarServer>/api/swagger-ui.html`. Dell publishes no downloadable OpenAPI document.
- **Auth** — OAuth 2.0. Register a client (`POST /api/v1/oauth2/clients`, HTTP Basic admin), then obtain a bearer token (`POST /api/oauth/token`, grant_type=password). RS256 JWTs, 1800s access / 43200s refresh. OIDC SSO for the Avamar Web UI, validated against Keycloak.
- **Scopes** — `read`, `write`, `all`, plus OIDC `openid` and `profile`. Effective permissions also depend on the Avamar role and domain bound to the token.
- **Async** — long-running operations return a `task` resource polled through QUEUED → RUNNING → SUCCESS / ERROR / CANCELED / ABORTED.
- **CLI** — `mccli` (Management Console CLI) plus `avtar`, `avmaint`, `avmgr`, `dpnctl`, `avinstaller`.
- **Current release** — 19.12.

## Artifacts

`authentication/` `scopes/` `conventions/` `errors/` `lifecycle/` `changelog/` `cli/` `data-model/` `conformance/` `packages/` `security/` `well-known/` `llms/`

## Not published

Searched for and genuinely absent: public OpenAPI file, AsyncAPI or webhook surface, official MCP server, SDK in any package registry, sandbox or test credentials, status page or uptime SLA, embeddable UI components, gRPC/Protobuf, and a Dell-published Postman workspace.

Backed by: lightspeed-venture-partners
