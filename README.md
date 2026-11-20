# IoA Tracker Desktop — releases

Public auto-update artifacts for the IoA Tracker desktop app (Tauri v2, macOS).
The source code lives in the private repo `ioa-8lab/ioa-tracker-desktop`.

Each release carries:
- `IoA-Tracker-<version>-macos.dmg` — install once, drag to Applications
- `IoA-Tracker-macos.app.tar.gz` + `.sig` — signed update package
- `latest.json` — update manifest the installed app checks in the background

Updates are signed with the team update key; the app verifies every package
before installing. Sign-in and local data survive updates.
