# Voxear releases

Releases of the Voxear game engine and the Voxear Launcher.

The Voxear Launcher installs engine versions from here. It checks each download's signature before unpacking
anything, and it updates itself from here too. Nothing has been released yet.

## What's here

- **Releases** hold the files: engine archives under `engine-v<version>` tags, and launcher builds under
  `launcher-v<version>` tags. Each file has a `.minisig` signature beside it.
- **The `gh-pages` branch** holds the lists the launcher reads, served at
  <https://cookiejartools.github.io/VoxearReleases/>:
  - `engine/releases.toml`: every engine release, signed by `engine/releases.toml.minisig`
  - `launcher/stable.json` and `launcher/beta.json`: launcher updates

## Licence

Voxear and the Voxear Launcher are licensed under the [PolyForm Shield License 1.0.0](LICENSE.md).

Required Notice: Copyright 2026 Joseph Cook
