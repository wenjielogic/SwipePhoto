# 轻扫相册安卓版 · 0.5.0

[English](https://github.com/wenjielogic/SwipePhoto/blob/main/README.md) · [简体中文](https://github.com/wenjielogic/SwipePhoto/blob/main/docs/README.zh-CN.md) · [Español](https://github.com/wenjielogic/SwipePhoto/blob/main/docs/README.es.md)

轻扫相册 0.5.0（版本代码 6）是适用于 Android 11 及以上的测试版。照片在本机整理，支持简体中文、英语、西班牙语；无需账号，无广告和应用内购买。

**此工具免费公开，限个人非商业使用。禁止未经授权商用、收费分发、转售及删除署名。只公开 APK 和说明，不公开应用源码。**

## 下载

- [GitHub · APK 0.5.0](https://github.com/wenjielogic/SwipePhoto/releases/download/v0.5.0/SwipePhoto-0.5.0.apk)
- [Lanzou · 1234](https://wwall.lanzn.com/b01gibclpg)

国内：蓝奏云，密码 1234，选择 SwipePhoto-0.5.0.apk；可用官方 SHA256SUMS.txt 核对完整性。

## 安装与更新

下载发布附件 SwipePhoto-0.5.0.apk，在浏览器下载列表或文件管理器中打开；系统询问时，允许该来源安装应用。已有旧版官方应用时直接覆盖安装，不要先卸载。GitHub 自动生成的 Source code 压缩包只是分发仓库文档，不是安装包，也不含应用源码。

## 四向滑动

左滑加入待删除，批量确认后进入系统回收站；右滑保留原件；上滑加入本应用收藏，不改变系统相册收藏标记；下滑加入持久待私密队列。仅排队不会加密、隐藏或删除原照片。

## 批量私密处理

点击底部「私密 → 放入」进入待私密队列，再主动选择批量加密并保存，每批最多 100 张。每张成功项目都会生成 App 内加密副本，并在 Download/私密相册 保存经过校验的恢复文件。失败或中断的项目须单独核对；退出重开会保留队列。身份验证过期时重新解锁后继续。

## 另行移除公开原件

加密副本和恢复文件校验成功后，另行确认移除公开原件。Android 会询问是否永久删除选中的公开文件；取消后原件仍可见。云端、回收站及其他位置的副本需另行检查。这里是轻扫相册自己的加密相册，不是 Google Photos 或手机品牌的系统私密相册。

## 撤回与查看

撤回用于最近的本地整理决定，不能撤销已完成的系统永久删除。点击底部「私密 → 打开私密相册 → 解锁私密相册」，完成本机身份验证后查看加密照片。导出到普通相册会在 Pictures/SwipePhoto 保存经过校验的照片，同时保留私密副本。「设置 → 语言」可切换界面语言。

## 卸载前

进入「设置 → 卸载保护与找回」，校验并保存全部私密照片。保留 Download/私密相册 文件夹，并另存一份到电脑等独立设备。已成功保存的共享 .swpv 文件通常会在卸载后保留，App 内部数据不会。卸载不会自动解密或还原照片。

## 重装后找回

进入「设置 → 卸载保护与找回」，通过系统文件选择器选取 .swpv 文件，输入 123456 并验证本机身份，然后进入私密相册查看或导出至普通相册。恢复文件丢失、不完整或损坏时，不能保证找回。

## 密码限制

123456 是固定且容易猜到的恢复文件密码，与手机锁屏密码不同，只适合防止随手查看。文件管理器仍能看到加密文件；取得文件并知道该密码的人可以恢复内容。请勿删除文件。手机丢失、恢复出厂设置或删掉唯一备份仍会造成丢失。

## 反馈问题

联系 ljj781325@gmail.com 或提交 GitHub Issue，请提供 App 版本、手机型号、Android 版本、操作步骤及实际现象。不要发送私密照片、.swpv 文件、密码、签名密钥或未打码的日志。首次测试请使用少量可丢弃照片。

## Links

- [帮助与找回](https://wenjielogic.github.io/SwipePhoto/android/zh-Hans/support.html)
- [隐私政策](https://wenjielogic.github.io/SwipePhoto/android/zh-Hans/privacy.html)
- [SHA-256](https://github.com/wenjielogic/SwipePhoto/releases/download/v0.5.0/SHA256SUMS.txt)
- [Release history](https://github.com/wenjielogic/SwipePhoto/releases)
- [iPhone / iOS information](https://wenjielogic.github.io/SwipePhoto/ios/zh-Hans/index.html)

© 2026 卢文杰. Android APK: `dev.local.swipephoto`, version `0.5.0`, version code `6`.
