# Contributing

Thank you for your interest in AuthModules.

AuthModules is a modular identity and authentication toolkit for TypeScript applications. It is not
a hosted auth service and does not own application UI, database runtime, HTTP framework, provider
SDKs, or deployment infrastructure.

## Project workflow

All implementation work starts from a scoped GitHub issue tracked in the AuthModules Roadmap
project. One issue should produce one focused pull request.

Before opening a pull request:

- confirm the issue matches the intended scope;
- keep changes inside the affected repository;
- avoid adjacent roadmap items;
- keep repository content, documentation, comments, commits, issues, and pull requests in English;
- avoid secrets, credentials, private hostnames, local machine paths, deployment secrets, or private
  operational notes.

## Package boundaries

`@authmodules/core` is headless. It must not include runtime adapters, storage adapters, HTTP
framework integrations, provider SDKs, cookies, UI, deployment logic, or infrastructure logic.

Adapters, providers, UI, examples, and deployment-specific code belong outside core and require
their own scoped issue before implementation begins.

## Development baseline

Node.js and TypeScript package repositories must use:

- Node.js 24 or newer;
- npm;
- CI before domain or runtime implementation work;
- package names under the `@authmodules/*` namespace.

Do not create package repositories for visibility alone. A repository should exist only when a
tracked project item and scoped issue require real implementation or documentation.

## Pull requests

Pull requests should include:

- a linked issue;
- a summary of the change;
- a clear scope and out-of-scope section;
- relevant local checks;
- GitHub checks or CI status when available.

Before merge, pull request comments and review threads must be inspected. Do not merge while
unresolved non-outdated review threads remain. Comments from ChatGPT or Codex must be reviewed and
handled as review input before merge.

## Community standards

Participation in AuthModules repositories is covered by the Code of Conduct in
[CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).

Security reports should follow [SECURITY.md](SECURITY.md).
