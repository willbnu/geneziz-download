# Geneziz — Downloads

The official download repository for the **Geneziz** desktop app — a local-first AI knowledge
engine that turns your saves and web captures into a private, searchable knowledge base.
Learn more at [geneziz.app](https://geneziz.app).

## Current release — v1.14.21

| Platform | File | SHA-256 |
|---|---|---|
| macOS (Apple Silicon, macOS 12+) | [`Geneziz_1.14.21_aarch64.dmg`](https://github.com/willbnu/geneziz-download/releases/download/v1.14.21/Geneziz_1.14.21_aarch64.dmg) | `4d35d8e7f4ab6a96c1bea5608ef310bf8c5cff1930d085e3019bc09e81bc6030` |
| Windows (10/11 x64) | [`Geneziz_1.14.21_x64-setup.exe`](https://github.com/willbnu/geneziz-download/releases/download/v1.14.21/Geneziz_1.14.21_x64-setup.exe) | `f6a0e05798584e887df959e70ac20d01dc1e8ff04f5a8b064f6fe2ce5fe26240` |

Both installers are signed; the macOS build is notarized with Apple. The in-app updater
delivers new versions automatically — after install, you are always current.

A license key (purchased at [geneziz.app](https://geneziz.app)) is required to use the app.
Your knowledge base lives on your device.

[All releases →](https://github.com/willbnu/geneziz-download/releases)

## Verifying a download

Compare the file's SHA-256 against the table above:

```sh
shasum -a 256 Geneziz_1.14.21_aarch64.dmg   # macOS
certutil -hashfile Geneziz_1.14.21_x64-setup.exe SHA256   # Windows
```

## Security

Found a security issue? Please report it privately via
[GitHub security advisories](https://github.com/willbnu/geneziz-download/security/advisories/new)
— please do not open a public issue for vulnerabilities.
