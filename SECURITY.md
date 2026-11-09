# DriverOS security policy

DriverOS ONE is a prototype. It has no user accounts, remote sync, payment collection, or Tesla Fleet API integration.

## Data handling
Trip and maintenance records are stored in the browser's localStorage. This is not suitable for secrets or sensitive financial records. Export a backup regularly; clearing browser data can erase records. Do not use a shared vehicle browser for private data.

## Reporting vulnerabilities
Do not disclose security issues in public GitHub issues. Contact the repository owner privately through GitHub profile contact options. Do not post access tokens, passwords, vehicle identifiers, or personal information.

## Planned production hardening
- OAuth PKCE and server-side token storage
- Least-privilege permissions, encrypted secrets, rate limiting
- Server-side validation, audit logging, backups and restore testing
- Automated unit/integration tests and dependency scanning
- Privacy policy and data deletion/export controls

Never use DriverOS controls while driving.
