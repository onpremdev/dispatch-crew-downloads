# Dispatch Crew downloads

[Download Dispatch Crew 0.2.1 for Android](https://github.com/onpremdev/dispatch-crew-downloads/releases/download/v0.2.1/dispatch-crew-0.2.1-android.apk) · [Release details](https://github.com/onpremdev/dispatch-crew-downloads/releases/tag/v0.2.1)

Company pilot: Android 9 or later. This is a company-signed release APK; initial installation can be completed by your administrator over USB. The application source stays private. This repository publishes only APKs and public version information, never accounts, customer work or private signing keys.

## Sign in

Server: `https://dispatch.onpremservices.com:8443`

Use your own administrator-created Dispatch account with the crew role and assigned crew. No username, password or access to Dispatch data comes with this download. Download work while connected, fill downloaded forms offline, then sync. A server receipt confirms submission; manager approval and downstream processing are separate.

## Updates before Play Store

The company flavor checks the public GitHub channel and automatically downloads verified updates when connected. Finish your form, open **App updates**, choose **Install update**, and confirm in Android. On the first update, Android may ask you to allow updates from Dispatch Crew. Installation requires your confirmation; it is not unattended. Background checks run on Android's schedule and may be delayed by battery or network restrictions. A manual **Check for updates** is also available.

The updater validates the actual APK package, increasing version, SHA256 and company signing certificate. Existing forms, photos and queued work remain in the same app storage. Never uninstall or clear app data to repair an update problem.

Older 0.1.x prototype installations use a different signing identity and need the administrator's one-time USB bootstrap before receiving company-signed updates. Do not install a differently signed APK over unsynced work or uninstall to bypass a signature error. The reviewed bootstrap preserved a queued fictional form/photo on a Galaxy Tab A9; other devices need their own acceptance check.

Public release/feed and full download checksum are verified. Physical remote-update acceptance on the new tablet is still pending its Wi-Fi connection. Existing form, provider and billing acceptance holds remain separate from distribution.

## Release identity

Version: **0.2.1 (21)**  
Size: **61,054,026 bytes**  
APK SHA256: `f63b2b68e87a3ff0514f1a3416b1704beedf00745432442e83125c21c335a17d`  
Company signer SHA256: `a5b2aab2320d02faeb24dd2e3eca28cfd56d5f96dd39d8c03910dcde68d7f783`  
Source revision: `0f263ac37585194535a42fc32f142f3945f63ccc`

[Company update feed](https://raw.githubusercontent.com/onpremdev/dispatch-crew-downloads/main/channels/company-pilot.json). Historic 0.1.7/0.1.8 prototype releases are retained for reference.
