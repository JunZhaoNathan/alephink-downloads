# Alephink Downloads

Alephink 是 Vellumloop 旗下的 macOS 长篇小说工作空间，围绕手稿、记忆、研究和可审阅的 AI 写作协作。

本仓库仅保留历史发布记录；当前安装包由 Cloudflare R2 分发，应用源码仍在私有仓库。旧 GitHub Releases 中的 4.8.x 文件是历史包，不代表当前版本。

This repository preserves historical release records. Current downloads are distributed through Cloudflare R2; the application source remains private. The older 4.8.x GitHub assets are historical, not the current release.

## 下载

当前版本：**Alephink 1.6.16（build 40996）**，Apple Silicon，macOS 15 或更新版本。

官方下载：[Alephink 1.6.16 公证版 DMG](https://downloads.vellumloop.com/alephink/Alephink-1.6.16-macOS-arm64.dmg)

自动更新与最新版信息：[发布清单](https://downloads.vellumloop.com/alephink/latest/release.json) · [Alephink 官网](https://alephink.vellumloop.com)

SHA-256：`a83ea2ee7146fe94165987d4304e6f54dcabf2cbe93e3f2025063d94b6beb605`

本版恢复顶部全局导航，左栏专注 Binder，并修复从 AI 返回资料库时右侧资料面板未打开的问题。DMG 已经 Apple 公证。

## 安装

1. 下载最新版 `.dmg` 文件。
2. 双击打开 DMG。
3. 把 `Alephink.app` 拖到 `Applications / 应用程序` 文件夹。
4. 从 `Applications / 应用程序` 打开 Alephink。

如果 macOS 提示无法打开：

1. 打开 `系统设置 -> 隐私与安全性`。
2. 在安全提示处选择“仍要打开”。
3. 或右键点击 `Alephink.app`，选择“打开”。

## 试用与激活

Alephink 的本地写作、项目整理、备份和导出能力可以直接使用。AI 功能需要试用激活码或正式激活码。

申请试用：

1. 打开 Alephink。
2. 进入 `设置 -> AI 服务 -> Alephink AI 授权`。
3. 复制页面里的“本机机器码”。
4. 到 Alephink 官网提交试用申请：

```text
https://alephink.vellumloop.com
```

5. 收到邮件中的激活码后，回到授权页面粘贴激活码并点击激活。

激活码会绑定本机机器码。换电脑后机器码会改变，需要重新申请或联系 Vellumloop 重新发码。

## 更新

新版本以 [R2 发布清单](https://downloads.vellumloop.com/alephink/latest/release.json) 为准，不再向 GitHub Releases 上传 DMG。下载新版 DMG 后，重新把新的 `Alephink.app` 拖入 `Applications / 应用程序` 替换旧版本即可。

原来的激活码通常可以继续使用，只要它没有过期，并且仍在同一台机器上使用。

## English

Alephink is a long-form fiction workspace for macOS. It is designed for manuscript structure, chapters, story bible work, research material, memory updates, backups, export, and reviewable AI draft candidates.

Current release: **Alephink 1.6.16 (build 40996)** for Apple Silicon and macOS 15 or later. Download the notarized DMG from:

https://downloads.vellumloop.com/alephink/Alephink-1.6.16-macOS-arm64.dmg

To install, open the DMG, drag `Alephink.app` into `Applications`, and launch it from there. If macOS blocks the first launch, open `System Settings -> Privacy & Security` and allow the app, or right-click the app and choose `Open`.

AI features require a trial or activation code. Copy the machine code from `Settings -> AI Service -> Alephink AI License`, submit a trial request at `https://alephink.vellumloop.com`, then paste the activation code you receive by email into the license page.
