<!--
SPDX-FileCopyrightText: 2026 Mattia Egloff <mattia.egloff@pm.me>

SPDX-License-Identifier: GPL-3.0-or-later
-->
<h1 align="center">
  <code>vauchi</code>
</h1>

<h3 align="center">Privacy-focused contact sharing</h3>

<p align="center">
  Exchange contact cards in person. Update your info anytime.<br>
  End-to-end encrypted. No accounts. No tracking.
</p>

<p align="center">
  <a href="https://github.com/vauchi/.github"><img src="https://img.shields.io/github/stars/vauchi/.github?style=flat&color=89b4fa&labelColor=1e1e2e" alt="Stars"></a>
  <a href="https://github.com/vauchi/.github/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-%20%20GNU%20GPLv3%20-green" alt="License"></a>
  <a href="https://github.com/sponsors/vauchi"><img src="https://img.shields.io/badge/sponsor-💜-cba6f7?style=flat&labelColor=1e1e2e" alt="GitHub Sponsors"></a>
  <a href="https://liberapay.com/Vauchi/donate"><img src="https://img.shields.io/badge/donate-💛-f9e2af?style=flat&labelColor=1e1e2e" alt="Liberapay"></a>
</p>

<p align="center">
  📦 Canonical source: <a href="https://gitlab.com/vauchi">GitLab</a> — GitHub is a read-only mirror
</p>

---

### How it works

1. **Meet someone** → Scan their QR code
2. **Stay connected** → Update your card anytime, they see the changes
3. **Stay private** → End-to-end encrypted, oblivious privacy-preserving relay

### Why Vauchi?

- **No accounts** — Your device is your identity
- **No tracking** — No analytics, no telemetry, no ads
- **No trust required** — We can't read your data, even if we wanted to
- **Open source** — Verify our claims yourself

### Tech stack

| Component | Technology |
|-----------|------------|
| Core | Rust, Signal Protocol (X3DH + Double Ratchet) |
| iOS / macOS | SwiftUI |
| Android | Kotlin / Compose |
| Windows | WinUI 3 |
| Linux | GTK4, Qt6 |
| Crypto | RustCrypto (`ed25519-dalek`, `x25519-dalek`, `sha2`, `hmac`, `hkdf`, `chacha20poly1305`) |
| TLS | `aws-lc-rs` (via rustls) |

### Repositories

#### Core & Infrastructure

| Repo | Description |
|------|-------------|
| [core](https://github.com/vauchi/core) | Crypto, protocols, data models (Rust) |
| [relay](https://github.com/vauchi/relay) | Oblivious privacy-preserving WebSocket relay server |
| [ohttp-relay](https://github.com/vauchi/ohttp-relay) | Oblivious HTTP relay |
| [e2e](https://github.com/vauchi/e2e) | End-to-end integration tests |

#### Apps

| Repo | Description |
|------|-------------|
| [cli](https://github.com/vauchi/cli) | Command-line interface |
| [tui](https://github.com/vauchi/tui) | Terminal user interface |
| [android](https://github.com/vauchi/android) | Native Android app |
| [ios](https://github.com/vauchi/ios) | Native iOS app |
| [macos](https://github.com/vauchi/macos) | Native macOS desktop app |
| [windows](https://github.com/vauchi/windows) | Native Windows desktop app |
| [linux-gtk](https://github.com/vauchi/linux-gtk) | Native Linux desktop app (GTK) |
| [linux-qt](https://github.com/vauchi/linux-qt) | Native Linux desktop app (Qt) |
| [web-demo](https://github.com/vauchi/web-demo) | Browser-based WASM demo |

#### Platform Bindings

| Repo | Description |
|------|-------------|
| [vauchi-platform-swift](https://github.com/vauchi/vauchi-platform-swift) | Swift Package (iOS/macOS) |

#### Content & Docs

| Repo | Description |
|------|-------------|
| [docs](https://github.com/vauchi/docs) | Public documentation (docs.vauchi.app) |
| [website](https://github.com/vauchi/website) | Landing page (vauchi.app) |
| [features](https://github.com/vauchi/features) | Gherkin BDD scenarios |
| [locales](https://github.com/vauchi/locales) | Translations (i18n) |
| [themes](https://github.com/vauchi/themes) | UI theme definitions |
| [assets](https://github.com/vauchi/assets) | Brand assets and logos |
| [scripts](https://github.com/vauchi/scripts) | Shared CI templates and dev tools |

### Support the project

Vauchi is community-funded. No VC money, no data harvesting.

<a href="https://github.com/sponsors/vauchi">
  <img src="https://img.shields.io/badge/GitHub_Sponsors-💜_Become_a_sponsor-cba6f7?style=for-the-badge&labelColor=1e1e2e" alt="GitHub Sponsors">
</a>
&nbsp;
<a href="https://liberapay.com/Vauchi/donate">
  <img src="https://img.shields.io/badge/Liberapay-💛_Donate-f9e2af?style=for-the-badge&labelColor=1e1e2e" alt="Liberapay">
</a>

---

<p align="center">
  <a href="https://vauchi.app">Website</a> •
  <a href="https://docs.vauchi.app/about/principles/">Principles</a> •
  <a href="https://docs.vauchi.app/developers/contributing/">Contributing</a>
</p>
