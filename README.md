# Dispatch Crew downloads

[Download Dispatch Crew 0.2.2 for Android](https://github.com/onpremdev/dispatch-crew-downloads/releases/download/v0.2.2/dispatch-crew-0.2.2-android.apk) · [Release details](https://github.com/onpremdev/dispatch-crew-downloads/releases/tag/v0.2.2)

Company pilot: Android 9 or later. This is a company-signed release APK; initial installation can be completed by your administrator over USB. The application source stays private. This repository publishes only APKs and public version information, never accounts, customer work or private signing keys.

## Sign in

Server: `https://dispatch.onpremservices.com:8443`

Use your own administrator-created Dispatch account with the crew role and assigned crew. No username, password or access to Dispatch data comes with this download. Download work while connected, fill downloaded forms offline, then sync. A server receipt confirms submission; manager approval and downstream processing are separate.

## Updates before Play Store

The company flavor checks the public GitHub channel and automatically downloads verified updates when connected. Finish your form, open **App updates**, choose **Install update**, and confirm in Android. On the first update, Android may ask you to allow updates from Dispatch Crew. Installation requires your confirmation; it is not unattended. Background checks run on Android's schedule and may be delayed by battery or network restrictions. A manual **Check for updates** is also available.

The updater validates the actual APK package, increasing version, SHA256 and company signing certificate. Existing forms, photos and queued work remain in the same app storage. Never uninstall or clear app data to repair an update problem.

Older 0.1.x prototype installations use a different signing identity and need the administrator's one-time USB bootstrap before receiving company-signed updates. Do not install a differently signed APK over unsynced work or uninstall to bypass a signature error. The reviewed bootstrap preserved a queued fictional form/photo on a Galaxy Tab A9; other devices need their own acceptance check.

Public release/feed and full download checksum are verified. Version0.2.2 changes only the version number for remote-update acceptance; app code and dependencies match the USB-tested0.2.1 build. The new tablet retains0.2.1 so it can receive0.2.2 remotely after joining Wi-Fi. Physical remote-update acceptance is still pending that connection. Existing form, provider and billing acceptance holds remain separate from distribution.

## Release identity

Version: **0.2.2 (22)**  
Size: **61,054,018 bytes**  
APK SHA256: `2e8f18177f2e6f319de511910090fdd2fea8f8a718dd4465b12d98378d757567`  
Company signer SHA256: `a5b2aab2320d02faeb24dd2e3eca28cfd56d5f96dd39d8c03910dcde68d7f783`  
Source revision: `8907921e6ffdcc7a7ce6a01a0e88c3c7a2c2201a`

[Company update feed](https://raw.githubusercontent.com/onpremdev/dispatch-crew-downloads/main/channels/company-pilot.json). Historic 0.1.7/0.1.8 prototype releases are retained for reference.
