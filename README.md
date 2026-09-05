# VexaCode Desktop Releases

VexaCode is a cross-platform desktop AI agent for chat, coding, and workspace
automation. It combines an AI chat interface with a local coding workspace,
Monaco Editor, language intelligence, terminal sessions, controlled tools, and
permission-aware workspace access.

Official website: [ai.vexacode.id](https://ai.vexacode.id)

Product documentation: [ai.vexacode.id/docs](https://ai.vexacode.id/docs)

## Download

Download the newest files from the [latest release](https://github.com/Hanafi-tech/vexa-desktop-releases/releases/latest).

| Platform              | File                       |
| --------------------- | -------------------------- |
| Windows 10/11, 64-bit | `VexaCode-*-win-x64.exe`   |
| macOS Apple Silicon   | `VexaCode-*-mac-arm64.dmg` |
| macOS Intel           | `VexaCode-*-mac-x64.dmg`   |

The Windows `.exe` is a normal installer. The macOS `.dmg` opens an installer
window where `VexaCode.app` can be dragged to Applications.

Before installing, download `SHA256SUMS.txt` from the same release and verify
the checksum when possible. Detailed platform instructions are available in
[`INSTALLATION.md`](./INSTALLATION.md).

## Important security notice

Current public builds are free and unsigned. This means macOS Gatekeeper or
Windows SmartScreen may display a warning on first launch. Follow the
instructions in `INSTALLATION.md` and only continue when the installer was
downloaded from this repository.

## Features

- Chat-first AI assistant with provider routing.
- Coding Mode with Monaco Editor, Tree-sitter, and managed language servers.
- Workspace browsing, editing, Git information, search, diagnostics, and terminal sessions.
- Permission-aware filesystem, terminal, browser, and workspace tools.
- DOCX, PPTX, image, and other bounded artifact workflows.
- Data-only themes, icon themes, snippets, grammars, and sandboxed plugins.
- Optional browser automation, local memory, tunnels, and voice features.

Executable VS Code extensions and embedded VS Code extension hosts are not
supported. Marketplace content is restricted to validated data-only packages.

## Release process

Builds are produced automatically from the
[`agent-ai-ide`](https://github.com/Hanafi-tech/agent-ai-ide) source repository
on native macOS and Windows GitHub Actions runners. Versioned releases and the
`latest` release contain the installer assets; this repository stores the
installation guidance and release metadata.

## Official links

- Website: [ai.vexacode.id](https://ai.vexacode.id)
- Documentation: [ai.vexacode.id/docs](https://ai.vexacode.id/docs)
- About Vexa: [ai.vexacode.id/about](https://ai.vexacode.id/about)
- Privacy: [ai.vexacode.id/privacy](https://ai.vexacode.id/privacy)
- Terms: [ai.vexacode.id/terms](https://ai.vexacode.id/terms)
- Security guidance: [ai.vexacode.id/docs#desktop-security](https://ai.vexacode.id/docs#desktop-security)

This repository is a distribution channel for VexaCode installers. It is not
intended for third-party code contributions or custom package uploads.

## License

VexaCode is proprietary software. See [LICENSE](./LICENSE) for the
distribution terms.
