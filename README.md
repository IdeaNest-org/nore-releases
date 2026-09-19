# Nore

Nore is a native network proxy utility for macOS and Windows. It provides
rule-based traffic routing, subscription-managed endpoints, automatic
latency-based endpoint selection with failover, and live traffic and
connection monitoring — in a clean, native interface.

This repository is the distribution channel for Nore. It hosts build
artifacts along with the automatic-update feed, and contains no source code.

## Download

Get the latest version from the
[Releases](https://github.com/IdeaNest-org/nore-releases/releases) page.

| Platform | Package | Notes |
| --- | --- | --- |
| macOS (Apple Silicon) | `Nore-x.y.z-arm64.dmg` | Signed and notarized |
| macOS (Intel) | `Nore-x.y.z.dmg` | Signed and notarized |
| Windows 10/11 (x64) | `Nore-Setup-x.y.z.exe` | Unsigned; SmartScreen may warn — choose "Run anyway" |

## Features

- Rule-based routing with per-destination policies
- Subscription import and endpoint management
- Automatic, latency-based endpoint selection and failover
- Local network sharing between devices on the same network (macOS)
- Live traffic charts and detailed connection logs
- Self-updating on both platforms

## Requirements

- macOS on Apple Silicon or Intel
- Windows 10 or 11 (64-bit)

## Updates

The app checks this repository and updates itself automatically.
Update integrity is verified against the SHA-512 checksums published in
the update feed (`latest-mac.yml` / `latest.yml`).

## Contact

Please use
[GitHub Issues](https://github.com/IdeaNest-org/nore-releases/issues)
for questions and bug reports. We do not publish a contact email.
