# Organization Security Guidance

This is the **default security guidance** for Animus public repositories that do not publish a more specific SECURITY.md. A repository-specific security policy takes precedence.

## Report suspected vulnerabilities privately

**Do not disclose a potentially exploitable issue in a public GitHub issue, discussion or pull request.**

Use the affected repository's **Security > Report a vulnerability** / GitHub Private Vulnerability Reporting flow when available. If that flow is unavailable, follow the private contact path stated in the repository or on the official Animus website. Do not send secrets or exploit details to an unverified public address.

A useful report includes:

- repository and affected versions or commit IDs;
- clear reproduction steps and observed versus expected behavior;
- security impact, prerequisites and affected trust boundary;
- minimal proof of concept without production credentials or private data;
- any known mitigation or workaround.

## Scope and supported versions

Support windows and remediation commitments are specified by each repository, not inferred from organization membership or the existence of public source code. Research prototypes and pre-release systems must not be assumed production-supported.

We encourage coordinated disclosure after an appropriate private review and remediation process. Do not assume a response-time or fix-time guarantee unless the relevant repository explicitly publishes one.