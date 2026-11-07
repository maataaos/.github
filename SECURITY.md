# Security policy

This policy covers every repository in the [maataaos](https://github.com/maataaos) organization, unless a repository has its own `SECURITY.md`.

## Reporting a vulnerability

Email **[security@allb.xyz](mailto:security@allb.xyz)** with "security" in the subject. Please do not open a public issue, pull request or discussion for a security problem.

Please include:

- the release or commit you tested (for example `v0.1.0-alpha.9`)
- the board or QEMU, and the build features
- what you did, what you expected, and what you saw
- a proof of concept or log, if you have one

We will reply to say we have your report, keep you told what we find, and credit you in the release notes if you wish. Please give us time to fix the problem before you publish it. MAATAA OS is built by a small team, so we will agree a date with you rather than promise a fixed one.

## Supported versions

MAATAA OS is an alpha. Only the latest release and the `main` branch get fixes.

| Version | Supported |
| --- | --- |
| Latest `v0.1.0-alpha.*` release | Yes |
| `main` | Yes |
| Older alpha releases | No |

## Known limits

These are known and documented, so they do not need a report. A way to get around a protection that we say works is in scope.

- Store data is not confidential: today's builds use a public development key.
- Development boards have an open debug port and no secure boot.
- Host reads over the serial channel are unsigned, by design.
- Timing and power side channels, fault injection (glitching) and a compromised build machine are out of scope.
- MAATAA OS is not certified for safety functions and must not be used for them.

The full list is in the [threat model](https://github.com/wortforfilms/os/blob/main/docs/SECURITY_THREAT_MODEL.md).

## Also see

- [security.txt](https://maataa-os.allb.xyz/.well-known/security.txt)
- [Security page](https://maataa-os.allb.xyz/security)
