# Security Policy

VexaCode installers in this repository are official but currently unsigned.
Always download them from the [latest release](https://github.com/Hanafi-tech/vexa-desktop-releases/releases/latest), verify `SHA256SUMS.txt`, and follow the [installation guide](./INSTALLATION.md).

## Reporting a vulnerability

Please do not publish credentials, API keys, private workspace data, or
exploitable vulnerability details in a public issue. Report security concerns
privately through the Vexa website at [ai.vexacode.id](https://ai.vexacode.id)
or through the private security reporting channel available in the GitHub
repository when enabled.

Include:

- A clear description of the issue and its impact.
- The affected installer version and operating system.
- Reproduction steps or a minimal proof of concept.
- Any mitigation you have already applied.

Please allow reasonable time for triage and remediation before public
disclosure. Do not test against accounts, workspaces, or systems that you do
not own or have explicit permission to assess.

## Security guidance

- Verify installer checksums before launching unsigned builds.
- Never share Vexa API keys or provider credentials in issues or release comments.
- Review file, terminal, browser, remote, and tunnel permissions inside the app.
- Keep your operating system and project dependencies up to date.
