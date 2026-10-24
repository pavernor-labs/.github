# Security Policy

## Reporting a vulnerability

Email **security@pavernor.tech**. Do not open a public issue.

Include the affected repository and commit, reproduction steps, and the impact
you believe it has. If you need to send secrets or captured page content, say so
first and we will arrange an encrypted channel.

We acknowledge within **3 business days** and aim to ship a fix or mitigation
plan within **30 days**. We credit reporters in the release notes unless asked
otherwise.

## Scope

Our tooling drives real browsers and handles credentials and personal data, so
these classes of bug are in scope across all repositories:

- Credential or session leakage, in logs, artifacts, telemetry, or errors.
- Personal data captured in run artifacts (screenshots, HAR files, DOM dumps).
- Prompt injection that lets page content hijack a planner.
- Actions executed on the wrong element, especially destructive ones.
- Sandbox or permission escapes in an MCP server.
- Supply-chain issues in published packages.

## Out of scope

- Findings requiring a compromised machine or an already-leaked key.
- Anti-bot behaviour or rate limits on third-party sites.
- Vulnerabilities in Playwright, a model provider, or a target website.
- Automated scanner output with no demonstrated impact.

## Our commitments

- No legal action against good-faith research that follows this policy.
- No bug bounty at this time. We will announce publicly before starting one.
- Run artifacts containing personal data are never committed to our
  repositories. If you find one that is, treat it as a vulnerability.
