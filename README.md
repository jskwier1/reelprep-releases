# ReelPrep — Public Release Mirror

This repository exists solely to host signed release artifacts for the [ReelPrep](https://github.com/jskwier1/ReelPrep) desktop app so the in-app auto-updater can fetch them without GitHub authentication.

## Releases

See the [Releases](https://github.com/jskwier1/reelprep-releases/releases) page.

Each release contains:
- `ReelPrep_<version>_aarch64.dmg` — Apple Silicon installer
- `ReelPrep_<version>_x64.dmg` — Intel installer
- `ReelPrep_<arch>.app.tar.gz` + `.sig` — Tauri updater payload + minisign signature
- `latest.json` — updater manifest

## Installation

End users: see [INSTALL.md](https://github.com/jskwier1/ReelPrep/blob/main/INSTALL.md) in the source repo.

## Source

Application source lives in the private [jskwier1/ReelPrep](https://github.com/jskwier1/ReelPrep) repo.
