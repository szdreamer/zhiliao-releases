<div align="center">
  <img src="https://www.szdreamer.com/assets/img/app-icon.png" alt="知了笔记 Zhiliao Notes" width="96" height="96">
  <h1>知了笔记 Zhiliao Notes</h1>
  <p><strong>本地优先、开放格式、AI 友好的免费个人知识库 · Local-First Markdown Notes with Native MCP & E2EE Sync</strong></p>
  <p>
    <a href="https://www.szdreamer.com/">官网 Website</a> ·
    <a href="https://www.szdreamer.com/features.html">功能一览 Features</a> ·
    <a href="https://www.szdreamer.com/support.html">帮助中心 Help</a> ·
    <a href="https://www.szdreamer.com/changelog.html">更新日志 Changelog</a> ·
    <a href="https://apps.apple.com/cn/app/id6785562695">App Store (中国区)</a> ·
    <a href="https://apps.apple.com/us/app/id6785562695">App Store (Global)</a>
  </p>
  <p>
    <a href="https://dl.szdreamer.com/zhiliao/zhiliao-notes.dmg">下载 Mac 版 (.dmg)</a> ·
    <a href="https://dl.szdreamer.com/zhiliao/zhiliao-notes-setup.exe">下载 Windows 版 (.exe)</a> ·
    <a href="https://dl.szdreamer.com/zhiliao/zhiliao-notes.apk">下载 Android 版 (.apk)</a>
  </p>
</div>

---

## 简介（中文）

**知了笔记（Zhiliao Notes）** 是一款**本地优先、注重隐私、开放 Markdown 格式、AI 友好**的免费跨平台个人知识管理与笔记应用，支持 **macOS、iOS、Windows 与 Android** 四端。无需注册账号，下载即用，零插件折腾即可完成记录、网页与 AI 对话剪藏、跨设备端到端加密同步，以及安全的本地 MCP 与模型 API 协同。

本仓库（`szdreamer/zhiliao-releases`）用于分发知了笔记的安装包、签名校验与自动更新清单（当前正式版 **v1.8.8**）。

### 核心特性

- **本地优先 · 离线可用**：笔记默认保存在设备本地，无需注册账号、手机号或邮箱，无广告、无跨应用追踪，断网也能完整阅读、编辑与全文检索。
- **开放 Markdown 格式 · 拒绝平台锁定**：正文采用开放 Markdown 格式，支持从 **Markdown / HTML / PDF / Notion / wolai / Evernote / Obsidian** 批量导入，并支持 Markdown 导出、桌面版导出 PDF / 打印，以及整库完整备份与恢复。
- **高保真剪藏（网页 / App / AI 对话）**：支持剪藏普通网页、公众号、知乎、微博、B站专栏、豆瓣、小红书分享链接、PDF 链接以及主流 AI 对话分享页，保留正文、图片与来源出处。
- **免费端到端加密多端同步（可选）**：电脑与手机完成二维码配对后即可免费全量同步笔记、附件与已配置的远端 AI 模型/API Key；端到端加密密钥仅存于用户设备，中转服务器仅转运密文、取件即删，默认关闭。
- **AI 友好：本机 MCP 协议 + 全端模型 API 助手**：
  - **桌面端原生 MCP Server**：在用户设备本机运行，默认关闭、默认只读，可安全连接支持 Model Context Protocol (MCP) 的第三方 AI 客户端（如 Claude Desktop、Cursor、WorkBuddy 等），授权范围内检索、分析或经用户确认后整理笔记。
  - **全端内置 AI 助手（v1.8.8 新增）**：桌面端（`⌘J`）与手机端均可接入用户自己的模型 API（桌面端另支持本地 Ollama），知了笔记自身不内置绑定云端模型，也不用用户笔记训练模型。
- **隐私与安全锁（v1.8.8 新增）**：支持全端本机应用锁与单篇笔记锁（Mac 触控 ID / iPhone 面容 ID 解锁），已加锁笔记全程隔离，AI 助手与 MCP 均不可访问。
- **Mac 本地离线 OCR（v1.8.8 新增）**：基于原生 Apple Vision 与 PDFKit，图片与扫描件 PDF（单份上限 30 页）完全离线识别文字并纳入全文搜索，内容不上传云端。

### 支持平台与官方下载

| 平台 | 最新版本 | 官方下载 | 校验与说明 |
|---|---|---|---|
| **macOS 12+**（Apple Silicon & Intel） | v1.8.8 | [zhiliao-notes.dmg](https://dl.szdreamer.com/zhiliao/zhiliao-notes.dmg) | Apple 公证 + Ed25519 签名 |
| **Windows 10 / 11**（64 位） | v1.8.8 | [zhiliao-notes-setup.exe](https://dl.szdreamer.com/zhiliao/zhiliao-notes-setup.exe) | Ed25519 更新签名 |
| **iOS**（iPhone） | App Store | [中国区](https://apps.apple.com/cn/app/id6785562695) / [Global](https://apps.apple.com/us/app/id6785562695) | 1.8.8 审核中（商店当前在架 1.8.7） |
| **Android 10+**（ARM64） | v1.8.8 | [zhiliao-notes.apk](https://dl.szdreamer.com/zhiliao/zhiliao-notes.apk) | 官网/本仓库直装 APK |

---

## Overview (English)

**Zhiliao Notes (知了笔记)** is a **free, local-first, privacy-focused, AI-friendly Markdown note-taking and personal knowledge management (PKM) app** for **macOS, Windows, iOS, and Android**. No account required and zero plugin configuration needed — just open and start writing, clipping, encrypting, syncing, and connecting your knowledge base to AI via native **Model Context Protocol (MCP)**.

This repository (`szdreamer/zhiliao-releases`) hosts official release binaries, checksums, and auto-update manifests (latest desktop/Android release: **v1.8.8**).

### Key Capabilities

- **Local-First & Offline by Default**: Notes stay on your device first. No account, no email/phone sign-up, no ads, and no cross-app tracking.
- **Open Markdown & Easy Migration**: Standard Markdown storage with batch import from **Markdown, HTML, PDF, Notion, wolai, Evernote, and Obsidian**, plus Markdown/PDF export and full local backup & restore.
- **High-Fidelity Web & AI Chat Clipper**: Save web articles, social posts, PDF links, and AI conversation links with clean formatting, images, and source attribution.
- **Free End-to-End Encrypted (E2EE) Sync**: Optional device-paired sync across desktop and mobile. Encryption keys never leave your devices; the relay only forwards ciphertext and deletes it upon pickup.
- **Native Local MCP Server & Bring-Your-Own-Key AI Assistant**:
  - **Built-in Local MCP**: Runs locally on desktop (off by default, read-only by default). Connect Claude Desktop, Cursor, or any MCP-compatible AI client with granular scope control and explicit confirmation for edits.
  - **Cross-Platform Model API Assistant**: Connect your own model API (or local Ollama on desktop) across desktop and mobile without vendor lock-in. Zhiliao Notes never trains models on your data.
- **App Lock & Per-Note Lock**: Native Touch ID (Mac) and Face ID (iPhone) locks. Locked notes are strictly isolated from search, export, AI assistant, and MCP access.
- **Offline OCR on macOS**: Powered by native Apple Vision & PDFKit for images and scanned PDFs (up to 30 pages per PDF), making scanned text fully searchable without cloud uploads.

### Quick Comparison: Where Zhiliao Notes Fits

| Dimension | Zhiliao Notes (知了笔记) | Traditional Cloud Notes | Plugin-Heavy Local Vaults |
|---|---|---|---|
| Data ownership | Local-first Markdown, no account | Cloud account required | Local Markdown |
| Setup friction | Ready out of the box | Ready out of the box | Requires plugin tuning |
| Cross-device sync | Free, optional E2EE | Paid / cloud-dependent | Paid official or manual setup |
| AI & MCP integration | Native local MCP + BYOK API / Ollama | Built-in paid cloud AI | Community plugins |
| Web & AI chat clipping | Built-in multi-site clipper | Varies | Extension / plugin needed |

### Platforms & Downloads

| Platform | Latest | Download |
|---|---|---|
| **macOS 12+** (Universal) | v1.8.8 | [zhiliao-notes.dmg](https://dl.szdreamer.com/zhiliao/zhiliao-notes.dmg) |
| **Windows 10 / 11** (x64) | v1.8.8 | [zhiliao-notes-setup.exe](https://dl.szdreamer.com/zhiliao/zhiliao-notes-setup.exe) |
| **iOS** | App Store | [App Store (Global)](https://apps.apple.com/us/app/id6785562695) · [App Store (CN)](https://apps.apple.com/cn/app/id6785562695) |
| **Android 10+** (ARM64) | v1.8.8 | [zhiliao-notes.apk](https://dl.szdreamer.com/zhiliao/zhiliao-notes.apk) |

---

## 自动更新与仓库说明 Downloads & Auto-Update

- 桌面版通过「设置 → 软件更新」自动检查更新源（`latest.json`），所有桌面更新包均经过 Ed25519 签名校验。
- 国内加速镜像：<https://dl.szdreamer.com>；国际兜底镜像：本仓库 [Releases](../../releases)。
- 本仓库仅存放官方发布包与更新源，应用源码私有维护。This repo hosts release artifacts and update feeds only; source code is maintained privately.

## 官方文档与链接 Official Links

- 官网 Website：<https://www.szdreamer.com/>
- 功能一览 Features：<https://www.szdreamer.com/features.html>
- 使用帮助 Help Center：<https://www.szdreamer.com/support.html>
- 长期指南 Guides：<https://www.szdreamer.com/guides/>
- AI 连接与 MCP 文档：<https://www.szdreamer.com/help/ai-access.html>
- 隐私政策 Privacy Policy：<https://www.szdreamer.com/privacy.html>
- 更新日志 Changelog：<https://www.szdreamer.com/changelog.html>
- 机器可读产品事实（AI / LLM）：<https://www.szdreamer.com/llms.txt>
- 技术支持 Contact：`szdreamer@qq.com`
