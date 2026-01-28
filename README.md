<div align="center">

<img src="assets/readme/fm-logo.png" width="300" alt="Fluux Messenger Logo"/>

# Fluux Messenger

[![Release](https://img.shields.io/github/v/release/processone/fluux-messenger)](https://github.com/processone/fluux-messenger/releases)
[![Downloads](https://img.shields.io/github/downloads/processone/fluux-messenger/total)](https://github.com/processone/fluux-messenger/releases)
[![Repo Size](https://img.shields.io/github/repo-size/processone/ejabberd)](https://github.com/processone/fluux-messenger/releases)
[![Build Status](https://github.com/processone/fluux-messenger/workflows/CI/badge.svg)](https://github.com/processone/fluux-messenger/actions)
[![License: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

*A modern, cross-platform XMPP client for communities and organizations*

</div>

## 📑 Table of Contents

- [🎨 Screenshots](#-screenshots)
- [✨ Features](#-features)
- [🚀 Quick Start](#-quick-start)
- [📚 Technology Stack](#-technology-stack)
- [🆘 Support & Community](#-support-and-community)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [⭐ Star History](#-star-history)

## 🎨 Screenshots

<div align="center">

*Click on any screenshot to view full size*

| Chat Room | XMPP Console |
|-----------|--------------|
| <a href="assets/readme/chatroom.png"><img src="assets/readme/chatroom.png" width="250" style="border-radius: 8px;" alt="Chat Room"/></a> | <a href="assets/readme/console.png"><img src="assets/readme/console.png" width="250" style="border-radius: 8px;" alt="XMPP Console"/></a> |
| *Multi-user Chat* | *XMPP Debug Interface* |

| Language Settings | Login Screen | Theme System |
|-------------------|---|-------------|
| <a href="assets/readme/languages.png"><img src="assets/readme/languages.png" width="250" style="border-radius: 8px;" alt="Language Settings"/></a> | <a href="assets/readme/login.png"><img src="assets/readme/login.png" width="250" style="border-radius: 8px;" alt="Login Screen"/></a> | <a href="assets/readme/split.png"><img src="assets/readme/split.png" width="250" style="border-radius: 8px;" alt="Theme System"/></a> |
| *Currently supporting 8 languages* | *Simple Login Interface* | *Light and dark themes, more to come* |

| Admin Server Commands | Chat Rooms Management | Users Management |
|----------------------|-----------------------|------------------|
| <a href="assets/readme/admin-other.png"><img src="assets/readme/admin-other.png" width="250" style="border-radius: 8px;" alt="Admin Server Commands"/></a> | <a href="assets/readme/admin-chatrooms.png"><img src="assets/readme/admin-chatrooms.png" width="250" style="border-radius: 8px;" alt="Chat Rooms Management"/></a> | <a href="assets/readme/admin-users.png"><img src="assets/readme/admin-users.png" width="250" style="border-radius: 8px;" alt="Users Management"/></a> |
| *Manage your server right from your client* | *Moderate your rooms easily* | *User management in your client* |

</div>

## ✨ Features

- **Modern XMPP Client** - React-based UI with TypeScript
- **Cross-platform** - Available on web and desktop (Tauri-based)
- **Extensive XMPP Protocol Support** - 40+ XEPs implemented, including MAM, MUC, HTTP File Upload, message carbons, and reactions (and more to come)
- **Built-in XMPP Console** - Debug interface for developers and power users
- **Multi-user Chat** - Complete MUC support with roles, affiliations, @mentions, and bookmarks
- **File Sharing** - HTTP uploads with thumbnails, progress indicators, and previews
- **Real-time Messaging** - Typing indicators, message corrections, and delivery features
- **Offline Support** - IndexedDB storage with automatic sync on reconnect
- **Theme System** - Light/dark themes synchronized across devices
- **Self-hostable** - Connect to any XMPP server, no vendor lock-in
- **Open Source** - AGPL-3.0 licensed

## 🚀 Quick Start

### 📥 Download & Install

Download the latest release for your platform:

| Platform | Download |
|----------|----------|
| Windows (x64) | [Installer (.exe)](https://github.com/processone/fluux-messenger/releases/latest/download/Fluux.Messenger_x64-setup.exe) / [MSI (.msi)](https://github.com/processone/fluux-messenger/releases/latest/download/Fluux.Messenger_x64_en-US.msi) |
| macOS | [Intel (.dmg)](https://github.com/processone/fluux-messenger/releases/latest/download/Fluux.Messenger_x64.dmg) / [Apple Silicon (.dmg)](https://github.com/processone/fluux-messenger/releases/latest/download/Fluux.Messenger_0.11.0_aarch64.dmg) |
| Linux (x64) | [AppImage (.AppImage)](https://github.com/processone/fluux-messenger/releases/latest/download/Fluux.Messenger_amd64.AppImage) / [DEB (.deb)](https://github.com/processone/fluux-messenger/releases/latest/download/Fluux.Messenger_amd64.deb) / [RPM (.rpm)](https://github.com/processone/fluux-messenger/releases/latest/download/Fluux.Messenger-0.11.0-1.x86_64.rpm) |

*Links always point to the latest release version.*

## 📚 Technology Stack

- **Frontend**: React 18 + TypeScript
- **Desktop**: Tauri 2.x (Rust-based, lightweight)
- **Styling**: Tailwind CSS
- **State Management**: Zustand + XState
- **Build System**: Vite + Vitest
- **XMPP**: @xmpp/client + @fluux/sdk
- **Storage**: IndexedDB with idb

## 🆘 Support and Community

We welcome all questions, feedback, and bug reports!  

- **GitHub Issues** - Use [Issues](https://github.com/processone/fluux-messenger/issues) to report bugs, request features, or track tasks. Issues are preferred for anything that needs action or official tracking. We also use Issues as a lightweight roadmap for upcoming improvements.  
- **GitHub Discussions** - Use [Discussions](https://github.com/processone/fluux-messenger/discussions) for questions, ideas, or general conversations that don’t require formal tracking. Great for brainstorming or getting help without opening an Issue.  
- **XMPP Chatroom** - Join [fluux-messenger@conference.process-one.net](xmpp:fluux-messenger@conference.process-one.net?join) for live chat with the community and maintainers.

## 🤝 Contributing

Contributions are welcome! See [CONTRIBUTING](CONTRIBUTING.md) for detailed guidelines.

## 📄 License

Fluux Messenger is licensed under the **GNU Affero General Public License v3.0 or later**. See [LICENSE](LICENSE)

## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=processone/fluux-messenger&type=Date&theme=dark&legend=bottom-right)](https://star-history.com/#processone/fluux-messenger&Date&legend=bottom-right)

---

<div align="center">

**Built with ❤️ by [ProcessOne](https://github.com/processone).**

</div>
