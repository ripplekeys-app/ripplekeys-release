# RippleKeys Release

Signed & notarized RippleKeys releases — release binaries only; no source code lives here.

RippleKeys is an independent fork of [Keyty](https://github.com/keytyapp/Keyty)
(BSD 3-Clause, © 2026 Serhii Bykov), a keyboard and mouse input visualizer for
macOS. See the RippleKeys source repository for source, build docs, and license.

Downloads live on the [Releases](https://github.com/ripplekeys-app/ripplekeys-release/releases) page.
Each release attaches a stable artifact pair to a `v<version>` tag:

```
https://github.com/ripplekeys-app/ripplekeys-release/releases/download/v<version>/RippleKeys.zip
https://github.com/ripplekeys-app/ripplekeys-release/releases/download/v<version>/RippleKeys.dmg
```

- `RippleKeys.zip` — Sparkle update archive (auto-update enclosure).
- `RippleKeys.dmg` — first-install drag-to-Applications disk image.

This repository is currently **private**: downloads require GitHub authentication
and the Sparkle feed's update downloads resolve only for authorized clients. It
will be made public when RippleKeys launches.

The Sparkle update feed is served from `https://ripplekeys-landing.pages.dev/appcast.xml`
(hosted from the RippleKeys source repository's landing microsite).
