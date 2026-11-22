# Sic4rioDragon All-in-One — APK Releases

This PUBLIC repository is **only for downloadable Android releases and update metadata**. The Android application source code, build scripts, and signing configuration are maintained separately in a **PRIVATE** development repository.

## Download

Go to **[Releases](https://github.com/Sic4rioDragon/Sic4rioDragon-All-in-One-Releases/releases)** and choose the latest published version. Download `Sic4rioDragon-All-in-One-vX.Y.Z.apk` (not the automatically generated GitHub Source code ZIP), then open it on your Android phone and follow Android's install prompt.

*The first stable release is pending setup of the permanent APK signing key and publishing credentials. There is no APK available here until a Release appears.*

## In-app updates

When a stable release is published, the app can check `releases/latest`, compare the version number, download the new APK, verify its SHA-256 checksum and signing certificate, and request installation with your confirmation.

Every published version contains:
- **Signed APK:** `Sic4rioDragon-All-in-One-vX.Y.Z.apk`
- **Update metadata:** `update.json`
- **Checksum:** `SHA256SUMS.txt`
- **Release notes:** on the GitHub Release page

The APK package ID is `uk.drache.allinone`. Downloads are public, without a GitHub login.

## Current hardware test target

moto g (2025), Android 16, TOZO HT2 Bluetooth headphones. The experimental audio engine's ability to reduce music below the normal minimum volume has **not yet been verified on this hardware**.

This distribution repository intentionally contains no Android source code, signing secrets, telemetry, or user data.
