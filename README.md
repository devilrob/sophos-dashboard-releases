# Sophos Dashboard — releases

Signed Windows builds of the Security Dashboard. This repository contains **only release files** (no source code).

Each release has:
- `SecurityDashboard.exe`
- `SecurityDashboard.exe.sig` — Ed25519 signature; the app refuses any update that is not signed by the maintainer's key
- `SHA256SUMS.txt`

The app checks this page for new versions and installs them only after you press *Install and restart* (or if you turned on auto-update).
