# Security policy

This policy covers every repository of the TandemLLM organization that has no SECURITY.md of its own.

## Report a vulnerability

Report it in private on GitHub: on the repository the problem is in, open **Security**, then **Report a vulnerability**:

- TandemEngine: [report a vulnerability](https://github.com/TandemLLM/TandemEngine/security/advisories/new)
- TandemApp: [report a vulnerability](https://github.com/TandemLLM/TandemApp/security/advisories/new)

Only you and the maintainer see the report. A public issue or pull request would show it to everyone before a fix exists.

Say which version you ran (`VERSION` in the checkout, or the release you installed), the part that is affected, the request or file that sets it off, and what an attacker gets. A script or a failing test helps most. Please check the latest release first.

Each repository's `docs/threat-model.md` says where untrusted input enters and which parts matter most.
