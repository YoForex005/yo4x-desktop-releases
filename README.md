# YO4X Desktop Releases

This public repository is the release-only distribution endpoint for YO4X Desktop.

It contains GitHub Release assets and signed update metadata only. The application
source code, CI/CD configuration, and private operational material live in the
separate private source repository.

## What may be published here

- Versioned `YO4X.exe` release assets produced by the trusted release workflow.
- Signed update manifests and checksums.
- Release notes describing version, channel, and compatibility.

## What must never be published here

- Source code, build workspaces, test fixtures, or development configuration.
- Credentials, API keys, certificates, private signing keys, tokens, or passwords.
- Customer data, logs, database files, broker credentials, or environment files.

## Update channels

- **Beta:** GitHub Releases marked as pre-releases, for opt-in testing.
- **Stable:** normal GitHub Releases, published only after beta approval.

The same tested executable may be promoted from Beta to Stable without rebuilding.
