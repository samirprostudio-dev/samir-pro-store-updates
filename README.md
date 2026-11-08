# Samir Pro Store — Updates

Public update channel for the Samir Pro Store Android app. This repo holds
only the files the app fetches to check for updates — no source code.

- `version.json` — latest `versionCode` / `version` / `apkUrl` / `changelog`.
  The app checks it on launch and shows the update popup only when the
  released `versionCode` is higher than the installed one.
- `SamirProStore-vX.Y.apk` — the latest APK, downloaded by the app with
  `DownloadManager` and installed via the system installer.

Source code lives in the private repo `samir-pro-store`. This repo is public
on purpose: the phone fetches these files without any GitHub sign-in.
