# Contributing

AuthModules is a collection of focused packages developed in one public monorepo. Each workspace owns one package responsibility and keeps an explicit public boundary.

Open implementation changes in the `authmodules` development monorepo. Keep package-specific changes inside the workspace that owns the affected behavior. Use this `.github` repository only for the organization profile and shared community health files.

## Before opening a pull request

1. Check for an existing issue or discussion when the change affects public behavior or more than one package.
2. Keep the change within the affected workspace responsibilities. Coordinate contract changes through explicit package dependencies rather than introducing hidden cross-package coupling.
3. Keep repository-facing code, documentation, tests, commits, and pull requests in English.
4. Add focused regression tests for behavior changes and security fixes.
5. Run the monorepo's root `npm run check` command. When a package's exported entrypoints or declarations intentionally change, run `npm run api:update` and review its `api-surface.json`.
6. Do not include credentials, raw tokens, passwords, OTP values, personal data, private provider responses, or generated build artifacts.
7. Keep public APIs minimal and backward-compatible. Explain any unavoidable contract change and its ecosystem impact in the pull request. Under the conservative compatibility policy, any public API snapshot change requires at least the next minor version before `1.0.0` and the next major version after `1.0.0`.

Pull requests also run dependency review and CodeQL. Dependency automation does not replace review: confirm package compatibility, release notes, lockfile scope, and the complete repository check before merging an update.

Report suspected vulnerabilities through the private security-reporting route described in `SECURITY.md`, not through a public issue.
