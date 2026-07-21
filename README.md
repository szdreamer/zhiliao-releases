<div align="center">
  <img src="https://www.szdreamer.com/assets/img/app-icon.png" alt="知了笔记 Zhiliao Notes" width="96" height="96">
  <h1>知了笔记 Zhiliao Notes</h1>
  <p><strong>我的笔记，我做主 · My notes, my rules</strong></p>
  <p>
    <a href="https://www.szdreamer.com">官网 Website</a> ·
    <a href="https://apps.apple.com/app/id6785562695">App Store</a> ·
    <a href="https://dl.szdreamer.com/zhiliao/zhiliao-notes.dmg">下载 Mac 版</a> ·
    <a href="https://dl.szdreamer.com/zhiliao/zhiliao-notes-setup.exe">下载 Windows 版</a> ·
    <a href="https://dl.szdreamer.com/zhiliao/zhiliao-notes.apk">下载 Android 版</a>
  </p>
</div>

---

## 简介（中文）

**知了笔记（Zhiliao Notes）是一款本地优先、开放格式、简洁高效的个人笔记应用，支持 macOS、iOS、Windows 与 Android 四端。** 它面向认真记录和思考的知识工作者：笔记默认只保存在你自己的设备上，无需注册账号，不上传云端，不用你的内容训练任何模型。

本仓库（`szdreamer/zhiliao-releases`）用于分发知了笔记的桌面版与 Android 版安装包及自动更新源。

### 核心特点

- **本地优先**：笔记默认保存在设备本地，不依赖云端账号，离线可完整查看、编辑、整理全部笔记。
- **开放格式**：正文采用 Markdown，导入导出自由，迁移备份不被平台绑定。
- **无需账号 · 隐私优先**：下载即用，不收集姓名/手机号/邮箱，无广告 SDK、无跨应用追踪 SDK。
- **端到端加密同步（可选）**：在你的设备之间（Mac / iPhone / Windows / Android）点对点加密同步，密钥只在你的设备上；中转服务器只传密文、取件即删，默认关闭。
- **功能齐全**：富文本编辑（表格/待办/颜色字体）、图片与任意附件、笔记本/多级目录/标签/收藏、全文搜索、全局废纸篓、网页与公众号剪藏、一键分享长图、Markdown 导出、多来源导入（Markdown / HTML / PDF / wolai / Notion / Evernote）、三套皮肤与深浅色。

### 支持平台与下载

| 平台 | 状态 | 下载 |
|---|---|---|
| macOS 12+（Apple Silicon 与 Intel） | 已上线 | [Mac 版 .dmg](https://dl.szdreamer.com/zhiliao/zhiliao-notes.dmg) |
| iOS | 已上线 | [App Store](https://apps.apple.com/app/id6785562695) |
| Windows 10 / 11（64 位） | 已上线 | [Windows 版 .exe](https://dl.szdreamer.com/zhiliao/zhiliao-notes-setup.exe) |
| Android 10+（arm64） | 已上线 | [Android 版 .apk](https://dl.szdreamer.com/zhiliao/zhiliao-notes.apk) |

> Android 版暂未上架各应用商店（软件著作权审批中），当前通过官网/本仓库 APK 直接安装，安装步骤见[帮助页](https://www.szdreamer.com/support.html)。

---

## Overview (English)

**Zhiliao Notes (知了笔记) is a local-first, open-format, distraction-free personal note-taking app for macOS, iOS, Windows and Android.** Your notes are stored on your own device by default — no account required, nothing uploaded to the cloud, and your content is never used to train any AI model.

This repository (`szdreamer/zhiliao-releases`) distributes the desktop and Android installers and hosts the auto-update feed for Zhiliao Notes.

### Highlights

- **Local-first** — notes live on your device by default; fully usable offline, no cloud account.
- **Open format** — body text is Markdown; import and export freely, never locked to a platform.
- **No account, privacy-first** — download and use immediately; no ad SDKs, no cross-app tracking.
- **Optional end-to-end encrypted sync** — peer-to-peer sync across your devices (Mac / iPhone / Windows / Android); keys stay on your devices, the relay only forwards ciphertext and deletes it on pickup. Off by default.
- **Full-featured** — rich-text editing (tables, to-dos, colors/fonts), images & arbitrary attachments, notebooks/nested folders/tags/favorites, full-text search, global trash, web & article clipping, one-tap long-image sharing, Markdown export, multi-source import (Markdown / HTML / PDF / wolai / Notion / Evernote).

### Platforms & Downloads

| Platform | Status | Download |
|---|---|---|
| macOS 12+ (Apple Silicon & Intel) | Available | [.dmg](https://dl.szdreamer.com/zhiliao/zhiliao-notes.dmg) |
| iOS | Available | [App Store](https://apps.apple.com/app/id6785562695) |
| Windows 10 / 11 (64-bit) | Available | [.exe](https://dl.szdreamer.com/zhiliao/zhiliao-notes-setup.exe) |
| Android 10+ (arm64) | Available | [.apk](https://dl.szdreamer.com/zhiliao/zhiliao-notes.apk) |

> The Android build is currently distributed as a direct APK (sideload) and is not yet listed on app stores (software copyright registration in progress).

---

## 下载与自动更新 Downloads & Updates

- **下载 Download**：桌面版与 Android 版从[官网](https://www.szdreamer.com)或本仓库 [Releases](../../releases) 获取（macOS `.dmg` / Windows `.exe` / Android `.apk`）；iOS 在 [App Store](https://apps.apple.com/app/id6785562695)。国内加速镜像 China mirror：<https://dl.szdreamer.com>。
- **自动更新 Auto-update**：桌面版应用内「设置 → 软件更新」自动检查新版本（更新源 `latest.json`）；Android 版在「设置 → 检查更新」检测后跳转浏览器下载新 APK。The desktop app checks this repo's Releases for updates via `latest.json`; the Android app checks the same feed and opens the browser to download new APKs.
- 本仓库仅存放构建产物与更新源，源代码私有维护。This repo hosts build artifacts and the update feed only; source code is maintained privately.

---

## 隐私 Privacy

知了笔记不收集账号、不上传笔记内容、不含广告或追踪 SDK。可选的多设备同步为端到端加密。完整隐私政策见 <https://www.szdreamer.com/privacy.html>。

Zhiliao Notes collects no account, uploads no note content, and ships no ad/tracking SDKs. Optional multi-device sync is end-to-end encrypted. Full policy: <https://www.szdreamer.com/privacy.html>.

## 链接 Links

- 官网 Website：<https://www.szdreamer.com>
- 帮助 Support：<https://www.szdreamer.com/support.html>
- 邮箱 Contact：1842807666@qq.com

<!-- 备案（页脚可选加）：粤ICP备2026046460号-2 -->
