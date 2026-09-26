# Geneziz — Downloads

The official download repository for the **Geneziz** desktop app — a local-first AI knowledge
engine that turns your saves and web captures into a private, searchable knowledge base.
Learn more at [geneziz.app](https://geneziz.app).

## Current release — v1.14.27

| Platform | File | SHA-256 |
|---|---|---|
| macOS (Apple Silicon, macOS 12+) | [`Geneziz_1.14.27_aarch64.dmg`](https://github.com/willbnu/geneziz-download/releases/download/v1.14.27/Geneziz_1.14.27_aarch64.dmg) | `0ca62875cc1195010df5fd5bc193f053b47a2f36c5eb684c5714627a843d844e` |
| Windows (10/11 x64) | [`Geneziz_1.14.27_x64-setup.exe`](https://github.com/willbnu/geneziz-download/releases/download/v1.14.27/Geneziz_1.14.27_x64-setup.exe) | `484bd9b1935b3ca8281918d32a648c2499b88b43b740ff94b529bac87561ca16` |

Both installers are signed; the macOS build is notarized with Apple. The in-app updater
delivers new versions automatically — after install, you are always current.

A license key (purchased at [geneziz.app](https://geneziz.app)) is required to use the app.
Your knowledge base lives on your device.

[All releases →](https://github.com/willbnu/geneziz-download/releases)

## Verifying a download

Compare the file's SHA-256 against the table above:

```sh
shasum -a 256 Geneziz_1.14.27_aarch64.dmg   # macOS
certutil -hashfile Geneziz_1.14.27_x64-setup.exe SHA256   # Windows
```

## Security

Found a security issue? Please report it privately via
[GitHub security advisories](https://github.com/willbnu/geneziz-download/security/advisories/new)
— please do not open a public issue for vulnerabilities.
