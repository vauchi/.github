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

---

### How it works

1. **Meet someone** → Scan their QR code
2. **Stay connected** → Update your card anytime, they see the changes
3. **Stay private** → End-to-end encrypted, zero-knowledge relay

### Why Vauchi?

- **No accounts** — Your device is your identity
- **No tracking** — No analytics, no telemetry, no ads
- **No trust required** — We can't read your data, even if we wanted to
- **Open source** — Verify our claims yourself

### Tech stack

| Component | Technology |
|-----------|------------|
| Core | Rust, Signal Protocol (X3DH + Double Ratchet) |
| iOS | SwiftUI |
| Android | Kotlin/Compose |
| Desktop | Tauri + SolidJS |
| Crypto | `ring` (audited, no OpenSSL) |

### Repositories

| Repo | Description |
|------|-------------|
| [vauchi](https://github.com/vauchi/vauchi) | Meta-repo, documentation, roadmap |
| [core](https://github.com/vauchi/core) | Core library + mobile bindings |
| [relay](https://github.com/vauchi/relay) | Zero-knowledge WebSocket relay |
| [cli](https://github.com/vauchi/cli) | Command-line interface |
| [desktop](https://github.com/vauchi/desktop) | Desktop app (Tauri) |
| [android](https://github.com/vauchi/android) | Android app |
| [ios](https://github.com/vauchi/ios) | iOS app |

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
  <a href="https://github.com/vauchi/vauchi/blob/main/PRINCIPLES.md">Principles</a> •
  <a href="https://github.com/vauchi/vauchi/blob/main/ROADMAP.md">Roadmap</a> •
  <a href="https://github.com/vauchi/vauchi/blob/main/CONTRIBUTING.md">Contributing</a>
</p>