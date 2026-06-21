# BuddyGecko — Releases (OTA)

Public OTA channel for [BuddyGecko](https://github.com/alkevintan/BuddyGecko) (private source).

- **`version.json`** (this branch) — the update manifest the app polls
  (`latestVersionCode`, `latestVersionName`, `apkUrl`, `changelog`). Update it on every release.
- **APKs** — attached to each [GitHub Release](../../releases) (e.g. `buddygecko.apk`).

The app checks `version.json` on launch and from Settings → Check for updates, and installs the
APK at `apkUrl` when `latestVersionCode` is newer. For private use only.
