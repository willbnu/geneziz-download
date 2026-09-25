# Geneziz — Downloads

The official download repository for the **Geneziz** desktop app — a local-first AI knowledge
engine that turns your saves and web captures into a private, searchable knowledge base.
Learn more at [geneziz.app](https://geneziz.app).

## Current release — v1.14.24

| Platform | File | SHA-256 |
|---|---|---|
| macOS (Apple Silicon, macOS 12+) | [`Geneziz_1.14.24_aarch64.dmg`](https://github.com/willbnu/geneziz-download/releases/download/v1.14.24/Geneziz_1.14.24_aarch64.dmg) | `93f95ee4df8a405e89311dedd3214e7ed1d3331597f1a57a2578c5f12520bbab` |
| Windows (10/11 x64) | [`Geneziz_1.14.24_x64-setup.exe`](https://github.com/willbnu/geneziz-download/releases/download/v1.14.24/Geneziz_1.14.24_x64-setup.exe) | _pending — added automatically when the Windows build publishes_ |

Both installers are signed; the macOS build is notarized with Apple. The in-app updater
delivers new versions automatically — after install, you are always current.

A license key (purchased at [geneziz.app](https://geneziz.app)) is required to use the app.
Your knowledge base lives on your device.

[All releases →](https://github.com/willbnu/geneziz-download/releases)

## Verifying a download

Compare the file's SHA-256 against the table above:

```sh
shasum -a 256 Geneziz_1.14.24_aarch64.dmg   # macOS
certutil -hashfile Geneziz_1.14.24_x64-setup.exe SHA256   # Windows
```

## Security

Found a security issue? Please report it privately via
[GitHub security advisories](https://github.com/willbnu/geneziz-download/security/advisories/new)
— please do not open a public issue for vulnerabilities.
