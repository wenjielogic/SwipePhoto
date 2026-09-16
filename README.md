# SwipePhoto · 轻扫相册

[English](README.md) · [简体中文](docs/README.zh-CN.md) · [Español](docs/README.es.md)

An offline photo organizer for **Android 11 or later**, created by **卢文杰**. Review one photo at a time with four swipe directions. The app supports Simplified Chinese, English and Spanish.

**Free for personal, non-commercial use. No account, ads, in-app purchases or internet permission.** This repository distributes the APK and documentation only. The application source code is not published; this is not an open-source release.

## Download and install

**[Download SwipePhoto 0.4.0 APK](https://github.com/wenjielogic/SwipePhoto/releases/download/v0.4.0/SwipePhoto-0.4.0.apk)** · [Release page](https://github.com/wenjielogic/SwipePhoto/releases/tag/v0.4.0)

1. Open the download link on your Android phone and save `SwipePhoto-0.4.0.apk` (about 3.4 MB).
2. Open the APK in your browser's downloads or file manager. If Android asks, allow that browser or file manager to install apps from this source.
3. If an older official version is installed, install this update over it. **Do not uninstall the old version first.**
4. Open SwipePhoto and allow access to your photos. Android 14+ can grant access to selected photos instead of the entire library.

Download the `.apk` file. GitHub's automatically generated “Source code” archives contain this repository's documentation, not the app's source code or an installer. This is a **test release**, not a Play Store listing. Start with a few non-important test photos.

## Four swipe directions

| Direction | Result |
| --- | --- |
| **Left** | Add to **To delete**. Photos enter the system trash only after you confirm the batch. |
| **Right** | Keep the original photo unchanged. |
| **Up** | Add to the app's **Favorites**. This does not change your system gallery's favorite flag. |
| **Down** | Authenticate, save and verify encrypted copies, then ask you to confirm removal of the public original. |

The four buttons do the same actions. Tap the photo to view it larger; pinch to zoom. Use **Undo** to reverse recent local decisions. The small confirmation beside **All photos** does not cover the Undo button. Already trashed or privately transferred photos have separate recovery/export flows.

Use **Find new photos** to add newly available photos. Review progress is saved automatically.

## Language

Open **Settings → Language** and select **简体中文**, **English** or **Español**. The first launch is in Simplified Chinese: tap **设置 → 语言 → English** to switch. Your choice is kept after restarting. Android's own dialogs may follow your phone's language.

## Private album and uninstall recovery

- View private photos in **Settings → Private album**. Authenticate with your phone's screen-lock credential or supported fingerprint. The album locks when you leave the app or after about four minutes.
- Recoverable encrypted files are saved in **Phone storage → Download → 私密相册**, with the `.swpv` extension. The folder name stays in Chinese in all languages.
- The encrypted-file password is **`123456`**, fixed in this version. This is separate from your phone's screen-lock credential. It is easy to guess and only deters casual viewing.
- The public original remains visible until you approve its removal. That removal uses Android's **permanent deletion** confirmation. Cloud copies, trash and copies elsewhere are not automatically removed.
- To put a private photo back in your gallery, choose **Export to gallery**. The photo appears in `Pictures/SwipePhoto`; the private copy is kept.

**Before uninstalling, open Settings → Uninstall protection and recovery → Verify and save all private photos. Confirm that nothing remains incomplete.** This is especially important for photos imported using older versions. Keep the app in the foreground during processing.

Successfully saved shared encrypted files normally remain after uninstalling, but **they do not decrypt automatically**. To recover:

1. Reinstall the official APK and open **Settings → Uninstall protection and recovery → Select encrypted files to recover**.
2. Select `.swpv` files in `Download/私密相册`. Long-press for multiple selection, or use the file picker's Select all command.
3. Enter **`123456`** and authenticate on your phone.
4. View the recovered photos in **Private album**, or export them to your gallery.

Uninstalling removes internal app data and any internal private copies that were not successfully saved to the shared folder. Deleting the shared files, losing the phone or resetting it can still cause loss. Copy the encrypted folder to another device as a backup. Your normal gallery does not display the encrypted photos; a file manager can still see the encrypted files.

## Free-use and non-commercial notice

**Creator: 卢文杰. This tool is publicly available free of charge. Commercial use, paid distribution, resale, monetization and removal or replacement of the creator's attribution are prohibited without the creator's prior written permission.**

You may download, install and share the unmodified official APK free of charge for personal, non-commercial use, keeping the attribution and notices. See the three-language [license and notice](LICENSE.md). Third-party components retain their own license terms.

## Authenticity and testing

- Version: **0.4.0**, package: `dev.local.swipephoto`, minimum: Android 11.
- APK SHA-256: `e6567b5d1e41b938226f4a127a125c25c5599cd9eb6eb5a600f6d6b75323e22d`.
- Signing-certificate SHA-256: `818b0c29f9fa5338f8e6228d5491a6ef8802c0602aa94cfa35836d3b4afdf560`.
- Keeps the previous official test certificate for in-place upgrades. The distributed build has debugging disabled and code obfuscation enabled.
- Includes creator markers and signature/attribution checks. These help detect ordinary modifications but cannot guarantee that determined attackers will never remove checks or repackage the app.
- Passed 30 JVM tests, plus language, undo and private-photo upgrade checks on Android 11/14 emulators. Tests also detected re-signed and watermark-modified APK copies. These results do not guarantee compatibility with every phone or replace your own backup.

You can report a reproducible problem in [Issues](https://github.com/wenjielogic/SwipePhoto/issues). Include your Android version, phone model and steps; do not upload private photos, encrypted albums or passwords.
