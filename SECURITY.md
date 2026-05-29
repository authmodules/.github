# Security Policy

AuthModules is in early public development. Security reports are welcome, but the project does not
currently offer a formal response or remediation SLA.

## Supported scope

Security reports should be limited to maintained AuthModules repositories and packages.

The current baseline package is:

- `@authmodules/core`

Planned packages or adapters are not considered supported until their repositories and releases
exist.

## Reporting a vulnerability

Please report suspected vulnerabilities privately through GitHub private vulnerability reporting
when it is available for the affected repository. If private vulnerability reporting is not
available, open a minimal public issue that requests a security contact without including exploit
details, secrets, tokens, private infrastructure details, or sensitive user data.

Include enough non-sensitive context to reproduce or understand the issue:

- affected repository and package;
- affected version, commit, or branch;
- short impact summary;
- safe reproduction steps or a proof of concept;
- relevant environment details that do not expose private infrastructure.

## Public disclosure

Please avoid public disclosure until the issue has been reviewed and a fix or mitigation path is
available. AuthModules will coordinate disclosure through the relevant repository issue, advisory,
or release notes when appropriate.

## Out of scope

The following reports are out of scope unless they demonstrate a concrete vulnerability in
maintained AuthModules code:

- vulnerabilities in unsupported planned packages;
- generic dependency advisories without an AuthModules impact path;
- reports that require access to private infrastructure;
- social engineering, spam, or denial-of-service testing;
- reports that include secrets, credentials, or private operational data.
