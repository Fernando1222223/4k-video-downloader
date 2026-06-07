# Security Policy — 4K Video Downloader

## Supported Versions

We actively maintain security updates for the following versions:

| Version | Supported |
|---|---|
| 3.0.x (Latest) | ✅ Active |
| 2.5.x | ✅ Security fixes only |
| 2.0.x | ❌ End of life |
| < 2.0 | ❌ End of life |

## Reporting a Vulnerability

If you discover a security vulnerability, please **do not** open a public GitHub issue.

Instead, report it privately via:
- **GitHub Security Advisories:** [Report a Vulnerability](https://github.com/fiagotvfnl/4k-video-downloader/security/advisories/new)
- **Email:** security@your-domain.com

Please include:
1. Description of the vulnerability
2. Steps to reproduce
3. Potential impact assessment
4. Your suggested fix (optional)

## Response Timeline

| Step | Timeline |
|---|---|
| Acknowledgement | Within 48 hours |
| Initial assessment | Within 5 business days |
| Fix development | Within 14 days (critical), 30 days (moderate) |
| Public disclosure | After fix is released |

## Scope

**In scope:**
- The desktop application (EXE)
- The download engine
- Data handling and privacy

**Out of scope:**
- Third-party websites the downloader connects to
- User's own network infrastructure
- Content of downloaded videos

## Security Features

- No network connections except to download target URLs
- No telemetry, analytics, or tracking
- No account system or authentication
- All processing is local to your machine
- Installer is code-signed with a valid certificate
- SHA256 checksums published for every release
