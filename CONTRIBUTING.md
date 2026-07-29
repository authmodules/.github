# Contributing

AuthModules is a collection of focused public repositories. Each repository owns one package or one ecosystem responsibility.

Open implementation changes in the repository that owns the affected package. Use the central `authmodules` repository for architecture, cross-package contracts, integration behavior, and design discussions. This `.github` repository owns only the organization profile and shared community health files.

## Before opening a pull request

1. Check for an existing issue or discussion when the change affects public behavior or more than one package.
2. Keep the change within one repository responsibility. Coordinate contract changes with every affected package rather than introducing hidden cross-package coupling.
3. Keep repository-facing code, documentation, tests, commits, and pull requests in English.
4. Add focused regression tests for behavior changes and security fixes.
5. Run the repository's `npm run check` command and include any additional adapter-specific integration check documented by that repository.
6. Do not include credentials, raw tokens, passwords, OTP values, personal data, private provider responses, or generated build artifacts.
7. Keep public APIs minimal and backward-compatible. Explain any unavoidable contract change and its ecosystem impact in the pull request.

Report suspected vulnerabilities through the private security-reporting route described in `SECURITY.md`, not through a public issue.
