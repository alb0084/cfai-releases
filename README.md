# CFAI Releases

This repository is used exclusively to host the release artifacts for the **CFAI Electron app**.

It is connected to the app's **auto-update system** via `electron-builder` and `autoUpdater`, and serves update files such as:

- `.yml` configuration files (`latest.yml`, `latest-mac.yml`, etc.)
- application binaries (`.exe`, `.dmg`, `.AppImage`, etc.)
- versioned release assets

---

## 🔄 How it's used

When the app checks for updates, it queries the GitHub releases in this repository to determine if a new version is available.

> ⚠️ This repository **does not** contain any source code.

---

## 🐞 Reporting Update Issues

If you're experiencing any of the following:

- The app doesn't update automatically
- You're stuck on an older version
- The updater throws errors (e.g., 404 on `.yml` or `.exe`)
- A platform-specific release is missing

Feel free to [open an issue](https://github.com/alb0084/cfai-releases/issues) describing the problem.

For all other issues related to CFAI's functionality or features, use this repo [CFAI repository](https://github.com/alb0084/cfai-releases) to report problems.
