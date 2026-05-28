# AuthModules

AuthModules is a modular identity and authentication toolkit for TypeScript apps.

It provides headless building blocks for users, identities, credentials, verifications,
sessions, account linking, passwordless flows, OAuth/OIDC provider adapters, and
framework integrations.

AuthModules is not a hosted auth service. It does not own your UI, database runtime,
HTTP framework, provider SDKs, or deployment infrastructure.

## Packages

Planned public packages:

- `@authmodules/core` — headless identity orchestration core
- `@authmodules/express` — Express transport adapter
- `@authmodules/drizzle` — Drizzle/PostgreSQL storage adapter
- `@authmodules/nuxt` — Nuxt frontend/SSR integration
- `@authmodules/passwordless` — passwordless route/runtime helpers
- `@authmodules/provider-oauth-oidc` — OAuth/OIDC external provider adapter

## Status

AuthModules is in early public development.

The first milestone is a clean `0.1.0` release line with public packages,
package boundary documentation, CI, release workflows, and migration notes.
