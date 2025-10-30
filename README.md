# 💖 Sweet-Whisper

**专为 ASMR 打造的跨平台播放器**

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![Language: Dart](https://img.shields.io/badge/Language-Dart-blue?logo=dart)](https://dart.dev)
[![Platform](https://img.shields.io/badge/Platform-Win%20%7C%20Mac%20%7C%20iOS%20%7C%20Android%20%7C%20Web-brightgreen)](https://flutter.dev)
[![Build Status](https://img.shields.io/github/actions/workflow/status/[YOUR_USERNAME]/Sweet-Whisper/YOUR_WORKFLOW_FILE.yml?branch=main)](https://github.com/[YOUR_USERNAME]/Sweet-Whisper/actions)

---

Sweet-Whisper 不仅仅是一个音频播放器。它是为那些寻求深度情感联系和沉浸式ASMR体验的用户而设计的。

市面上大多数播放器都专注于功能，而 Sweet-Whisper **专注于体验**。我们专为ASMR音频播放进行优化，创造一种近在耳边（Mimi Moto）的私密听感。

提供更多沉浸式 or 多样模式体验（例如Galgame模式）

## ✨ 预览

开发中

## 🚀 核心功能

* **专为ASMR优化：** 针对ASMR进行优化的音频渲染，追求极致的“近耳感”。
* **五端统一体验：** 基于 Flutter，一套代码库覆盖 **Windows, macOS, Android, iOS** 和 **Web**。
* **高保真流媒体：** 支持 `FLAC` 无损格式流式传输（基于 `HLS/DASH`），为你提供母带级的音质。 （有待决定）
* **沉浸式UI：** 无干扰、情感化的用户界面设计，帮助你专注于内容本身。
* **专为ASMR的功能：** 睡眠模式、定时、自定义播放列表、翻译字幕显示等功能
* **低延迟播放：** 快速的音频加载和无缝的流媒体切换。
* **真正的开源：** 采用 AGPLv3 许可，确保项目和所有基于它的网络服务永久自由和开放。

## 🧭 项目状态

🚧 **项目处于早期开发阶段 (Alpha)** 🚧

我们正在积极构建核心功能。

## 🛠️ 技术栈

* **框架 (Framework):** [Flutter 3.x](https://flutter.dev)
* **语言 (Language):** [Dart](https://dart.dev)
* **核心音频 (Audio Engine):** [just_audio](https://pub.dev/packages/just_audio)
* **流媒体协议 (Streaming):** HLS / DASH （有待决定）
* **后端 (Backend):** (TBD - 计划支持标准流媒体API) （有待决定）

## 🏁 开始使用

在开始之前，请确保你已经安装并配置了 [Flutter SDK](https://flutter.dev/docs/get-started/install)。

1.  **克隆仓库**
    ```bash
    git clone [https://github.com/](https://github.com/)[YOUR_USERNAME]/Sweet-Whisper.git
    cd Sweet-Whisper
    ```

2.  **安装依赖**
    ```bash
    flutter pub get
    ```

3.  **运行应用**
    * **Web:** `flutter run -d chrome`
    * **桌面端 (Windows/macOS):** `flutter run -d windows` 或 `flutter run -d macos`
    * **移动端:** 连接你的设备或模拟器后，运行 `flutter run`

## 🤝 如何贡献

我们非常欢迎你的贡献！无论是提交 Issue、改进代码还是优化文档。

1.  Fork 本仓库
2.  创建你的特性分支 (`git checkout -b feature/AmazingFeature`)
3.  提交你的更改 (`git commit -m 'Add some AmazingFeature'`)
4.  推送到分支 (`git push origin feature/AmazingFeature`)
5.  打开一个 Pull Request

请注意：**所有贡献都将被视为同意并遵守 AGPLv3 许可证。**

## 📜 许可证

`Sweet-Whisper`
Copyright (C) 2025 [ArisuMika]

本项目基于 **GNU Affero General Public License v3.0 (AGPLv3)** 开源。

这是一款自由软件：你可以自由地重新分发它，和/或在 GNU 宽通用公共许可证（由自由软件基金会发布）的条款下修改它，无论是该许可证的第 3 版，还是（由你选择）任何更高版本。

我们选择 AGPLv3 的核心原因在于：
**即使你是通过网络（例如部署一个Web服务）来让用户与修改后的版本进行交互，你也必须将修改后的源代码开放。**

我们希望确保 Sweet-Whisper 及其所有衍生版本，无论以何种形式提供服务，都能永远保持对社区的开放和自由。

你可以在 [LICENSE](LICENSE) 文件中查看完整的许可证文本。
