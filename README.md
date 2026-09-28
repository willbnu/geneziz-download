# Geneziz — Downloads

The official download repository for the **Geneziz** desktop app — a local-first AI knowledge
engine that turns your saves and web captures into a private, searchable knowledge base.
Learn more at [geneziz.app](https://geneziz.app).

## Current release — v1.14.30

| Platform | File | SHA-256 |
|---|---|---|
| macOS (Apple Silicon, macOS 12+) | [`Geneziz_1.14.30_aarch64.dmg`](https://github.com/willbnu/geneziz-download/releases/download/v1.14.30/Geneziz_1.14.30_aarch64.dmg) | `06c2a563574b41bc7b683b2e13a47ed2475a17ec1522d865eeca327d04d0a7ba` |
| Windows (10/11 x64) | [`Geneziz_1.14.30_x64-setup.exe`](https://github.com/willbnu/geneziz-download/releases/download/v1.14.30/Geneziz_1.14.30_x64-setup.exe) | _pending — added automatically when the Windows build publishes_ |

Both installers are signed; the macOS build is notarized with Apple. The in-app updater
delivers new versions automatically — after install, you are always current.

A license key (purchased at [geneziz.app](https://geneziz.app)) is required to use the app.
Your knowledge base lives on your device.

[All releases →](https://github.com/willbnu/geneziz-download/releases)

## Verifying a download

Compare the file's SHA-256 against the table above:

```sh
shasum -a 256 Geneziz_1.14.30_aarch64.dmg   # macOS
certutil -hashfile Geneziz_1.14.30_x64-setup.exe SHA256   # Windows
```

## Security

Found a security issue? Please report it privately via
[GitHub security advisories](https://github.com/willbnu/geneziz-download/security/advisories/new)
— please do not open a public issue for vulnerabilities.
