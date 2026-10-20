# Security Policy

## Supported Versions

The following versions currently receive security updates:

| Version | Supported |
| --- | --- |
| latest | ✅ |
| < 1.0 | ❌ |

> Update this table to reflect your actual release history.

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues.**

To report a vulnerability, please use one of the following channels:

- **GitHub Security Advisories**: [Report a vulnerability](../../security/advisories/new) *(preferred — keeps the report private until a fix is released)*
- **Email**: `security@[YOUR-DOMAIN]` *(replace with actual contact)*

### What to include

- A clear description of the vulnerability.
- Steps to reproduce or a proof-of-concept.
- Affected version(s) and environment details.
- Any known mitigations or workarounds.

### What to expect

| Timeframe | Action |
| --- | --- |
| 48 hours | Initial acknowledgement |
| 7 days | Preliminary assessment and severity rating |
| 90 days | Target remediation window (coordinated disclosure) |

We follow [responsible disclosure](https://en.wikipedia.org/wiki/Responsible_disclosure).
You will be credited in the security advisory unless you request anonymity.

## Security Best Practices for Contributors

- Never commit secrets, tokens, or credentials — use `.env` files (see `.env.example`).
- Keep dependencies up to date and review dependency changes in PRs.
- Prefer principle of least privilege in any permission or access control code.
