# Security Policy

## Supported Versions

| Version | Supported |
|---|---|
| latest | â |
| < latest | â |

## Reporting a Vulnerability

If you discover a security vulnerability, please report it to **security@hikari-group.tech**.

**Do NOT open a public issue for security vulnerabilities.**

We will:
1. Acknowledge receipt within 48 hours
2. Investigate and assess severity
3. Provide a fix timeline
4. Credit you in the fix release (if desired)

## Scope

- All public repositories under [HIKARI-GROUP](https://github.com/HIKARI-GROUP)
- No proprietary code, private data, or production systems
- No automated scanning without prior agreement

## Out of Scope

- Social engineering
- Physical attacks
- Denial of service
- Automated vulnerability scanners
- Vulnerabilities in third-party dependencies (report to upstream)

## Security Practices

- Secrets via environment variables (never in code)
- Input validation on all external data
- Authentication required for sensitive actions
- Regular dependency audits
- OAuth scopes minimized to what's needed
