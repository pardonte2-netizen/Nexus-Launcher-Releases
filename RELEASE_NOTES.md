# Nexus Launcher 2.2.0 — The Workshop Update

Nexus Launcher 2.2.0 adds a guided Workshop for preparing Minecraft instances, bounded Snapshots, privacy-filtered Nexus Share packages, Companion Health, and Task Center history.

## Download

Download `NexusSetup.exe` from the [v2.2.0 GitHub release](https://github.com/pardonte2-netizen/-Nexus-Launcher/releases/tag/v2.2.0). The release includes the installer, its JSON manifest, and a SHA-256 file.

SHA-256:

```text
b9b92c665fa34143c9eb5569a2537abf3313968e4099f07fe586c526b9b87949  NexusSetup.exe
```

The installer is not Authenticode-signed. Its hash is an integrity check, not an author signature. Windows SmartScreen may show an unknown-publisher warning.

## Verification scope

Release evidence records isolated Windows checks for the Setup install/update/recovery flows, Nexus Share package integrity and privacy filtering, Workshop/Snapshot IPC, and selected game launch scenarios. Vanilla, Fabric, Quilt, and Forge each have a narrow launch and saved-world acceptance case. NeoForge has client-initialization evidence only; no world load was verified.

These checks do not establish broad compatibility across Windows devices, Minecraft versions, mod combinations, or long-running performance. A first launch under the production application identity was not included in the local acceptance scope. See the [loader verification table](README.md#loader-support-and-verification-scope) for the tested configuration details.

## Install and update

Run `NexusSetup.exe`, select an installation folder, and follow Setup. For later versions, download the new installer from GitHub Releases and run it manually; an automatic launcher updater is not claimed.

## Privacy and diagnostics

Before sharing logs or screenshots, remove account names, email addresses, authentication tokens, private paths, and other personal information. Do not attach credentials or unredacted account settings to a public issue.
