# SwipePhoto for Android · 0.5.0

[English](https://github.com/wenjielogic/SwipePhoto/blob/main/README.md) · [简体中文](https://github.com/wenjielogic/SwipePhoto/blob/main/docs/README.zh-CN.md) · [Español](https://github.com/wenjielogic/SwipePhoto/blob/main/docs/README.es.md)

SwipePhoto 0.5.0 (version code 6) is a test release for Android 11 or later. Sort photos locally in English, Simplified Chinese or Spanish. No account, advertising or in-app purchases.

**Free for personal, non-commercial use. APK and documentation only; application source code is not published.**

## Download

- [GitHub · APK 0.5.0](https://github.com/wenjielogic/SwipePhoto/releases/download/v0.5.0/SwipePhoto-0.5.0.apk)
- [Lanzou · 1234](https://wwall.lanzn.com/b01gibclpg)

China: Lanzou sharing folder, access code 1234. Upload and checksum verification of version 0.5.0 in this folder are not yet confirmed. Check the filename and SHA-256 before installing; use GitHub when you need the verified release asset.

## Install or update

Download SwipePhoto-0.5.0.apk from the release assets. Open it in your browser downloads or file manager and allow installation from that source if Android asks. Install over the previous official version; do not uninstall it first. GitHub’s Source code archives contain distribution documents, not an installer or the application source.

## Four directions

Left: queue for deletion; confirm the batch to send photos to the system trash. Right: keep the original. Up: mark an in-app favorite, without changing the system gallery favorite. Down: add to the persistent private queue. Queuing does not encrypt, hide or delete the original.

## Batch private processing

Tap Private in the bottom navigation → Add photos to open the pending private queue, then explicitly choose batch encryption and saving, up to 100 photos. Each successful item gets an encrypted app copy and a verified recovery file in Download/私密相册. Failed or interrupted items must be reviewed; queued items remain after restarting. If authentication expires, unlock and continue.

## Remove public originals separately

After encrypted copies and recovery files are verified, separately confirm removal of public originals. Android asks for permanent deletion of the selected public files. Cancelling leaves those originals visible. Cloud copies, trash and duplicates elsewhere require separate checking. This is SwipePhoto’s encrypted album, not Google Photos Locked Folder or an OEM system private album.

## Undo and recovery

Undo reverses recent local sorting decisions; it does not reverse a completed system deletion. Tap Private in the bottom navigation → Open private album → Unlock private album, then authenticate on the phone to view encrypted photos. Export to gallery writes a verified photo to Pictures/SwipePhoto while keeping the private copy. Settings → Language changes the interface language.

## Before uninstalling

Open Settings → Uninstall protection and recovery and verify/save all private photos. Keep Download/私密相册 and make an independent copy on another device. Successful .swpv files in this shared folder normally survive uninstalling; internal app data does not. Uninstalling never decrypts or restores photos automatically.

## After reinstalling

In Settings → Uninstall protection and recovery, select the .swpv files through the system file picker, enter 123456 and authenticate on the phone. Then view them in the private album or export to the gallery. Missing, incomplete or damaged recovery files cannot be assumed recoverable.

## Password limitation

123456 is a fixed, easy-to-guess recovery-file password, separate from your phone screen lock. It only deters casual viewing. A file manager can see the encrypted files; anyone who obtains them and knows the password can recover their contents. Do not delete the files. Phone loss, factory reset or deletion of the only backup can still cause loss.

## Report a problem

Email ljj781325@gmail.com or open a GitHub issue. Include app version, phone model, Android version, steps and actual result. Do not send private photos, .swpv files, passwords, signing keys or unredacted logs. Start testing with a few disposable photos.

## Links

- [Help and recovery](https://wenjielogic.github.io/SwipePhoto/android/en/support.html)
- [Privacy policy](https://wenjielogic.github.io/SwipePhoto/android/en/privacy.html)
- [SHA-256](https://github.com/wenjielogic/SwipePhoto/releases/download/v0.5.0/SHA256SUMS.txt)
- [Release history](https://github.com/wenjielogic/SwipePhoto/releases)
- [iPhone / iOS information](https://wenjielogic.github.io/SwipePhoto/ios/en/index.html)

© 2026 Wenjie Lu. Android APK: `dev.local.swipephoto`, version `0.5.0`, version code `6`.
