# Security Policy — LiAura Coin (LIA)

## Reporting a Vulnerability
Please report security issues privately through GitHub Security Advisories on the official repository (`https://github.com/Cesardum/liaura-coin/security/advisories`).

Do **not** open public GitHub issues for unpatched consensus, RPC, or wallet vulnerabilities.

## Security Architecture Notes
- Never expose administrative RPC (`19081`) to the public internet.
- Never share `spend_sec` or 25-word mnemonic seeds.
- Official release binaries are verified via published SHA-256 checksums.
