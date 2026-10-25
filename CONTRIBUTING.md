# Contributing to Animus

Thank you for your interest in Animus engineering projects.

This file is the **organization-wide fallback** for public repositories without their own contribution guide. Repository-specific contribution policies, development instructions, license terms and release boundaries always take precedence.

## Before you contribute

1. Read the target repository's README, LICENSE, SECURITY and maturity/release notes.
2. Check existing issues and pull requests before proposing a change.
3. For nontrivial changes, open an issue describing the problem, proposed approach and compatibility impact, if issues are enabled.
4. Keep pull requests focused, with tests and documentation appropriate to the affected interface.
5. Explain what you verified, what remains untested, and any expected migration or security implications.

## Engineering expectations

- Prefer small, reviewable patches with explicit scope and rollback considerations.
- Keep contracts, API behavior, dependency changes and compatibility claims documented.
- Never commit secrets, access tokens, personal data or internal deployment configuration.
- Do not represent experimental code or unverified behavior as production-ready.
- Follow the repository's automated checks and maintainer guidance.

## Security findings

Do not put suspected vulnerabilities or sensitive proof-of-concepts in public issues or pull requests. See [SECURITY.md](SECURITY.md) and the affected repository's security policy for private reporting paths.

Public availability does not override the license and contribution terms of any individual repository.