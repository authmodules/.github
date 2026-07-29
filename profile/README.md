# AuthModules

Composable TypeScript building blocks for authentication and identity.

AuthModules is an open-source ecosystem of small, independent packages with explicit boundaries. Applications keep control of policy, user experience, persistence, HTTP composition, and deployment.

> **Project status:** pre-1.0 development. Package availability is determined by published releases; compatibility may change before 1.0.

## Design principles

- Small packages.
- Clear boundaries.
- Install only what you need.
- No framework or ORM lock-in.
- No hosted-service dependency.
- Explicit secret and transaction boundaries.
- Typed failures instead of expected exceptions.

## What is being built

The ecosystem is being designed around contracts, orchestration, authentication methods, storage, cryptography, session tokens, framework adapters, delivery, guards, compliance tooling, and reliable side-effect processing.

Pre-1.0 contracts may still evolve. Shared reporting and support routes are defined in [SECURITY.md](/authmodules/.github/blob/main/SECURITY.md) and [SUPPORT.md](/authmodules/.github/blob/main/SUPPORT.md).

## Security

Please use private vulnerability reporting. Never disclose credentials, tokens, passwords, one-time codes, personal data, or private provider responses in public discussions.
