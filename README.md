# 🏗️ Telos Messenger

### **Minimalist • Private • P2P-First**

Telos is a next-generation desktop messaging application built with **Rust**, **Tauri**, and **WebRTC**. It is designed for users who prioritize privacy and want a focused, distraction-free communication experience. Unlike traditional messengers, Telos does not store your messages on a server; it connects you directly to your peers.

[Download (Windows/macOS/Linux)](#-installation) • [Key Features](#-key-features) • [Privacy Policy](#-privacy--security)

---

## 📸 Screenshots

|                          Buddy List & Main UI                           |                       Group Video Broadcasting (Stage)                        |
| :---------------------------------------------------------------------: | :---------------------------------------------------------------------------: |
| <img src="screenshots/main_list.png" width="400" alt="Telos Main UI" /> | <img src="screenshots/video_stage.png" width="400" alt="Telos Video Stage" /> |

|                  Advanced Settings & Device Management                  |                         File Sharing (WebTorrent)                         |
| :---------------------------------------------------------------------: | :-----------------------------------------------------------------------: |
| <img src="screenshots/settings.png" width="400" alt="Telos Settings" /> | <img src="screenshots/transfers.png" width="400" alt="Telos Transfers" /> |

---

## ✨ Key Features

- 🛡️ **Pure P2P Communication:** Your messages never touch our server. We use WebRTC technology to establish a direct, encrypted tunnel between you and your friends.
- 📺 **Stage Model for Groups:** High-performance group video calls using a "1 Broadcaster - Many Viewers" architecture. Efficient, fast, and light on system resources.
- 📦 **Massive File Sharing:** Integrated **WebTorrent** support allows you to share large files within groups with the speed and reliability of the BitTorrent protocol.
- 🔒 **Military-Grade Local Encryption:** Your local chat history is encrypted using the **XChaCha20-Poly1305** algorithm. Even if your device is stolen, your data remains unreadable.
- 💻 **Device Binding:** Enhanced security ensures that only authorized devices verified via Email OTP can access your account.
- 🎨 **Minimalist UX:** A clean, focused interface inspired by the simplicity of classic messengers like Google Talk, but powered by modern technology.

---

## 🚀 Installation

Download the latest version from the [Releases](https://github.com/dogankarakoyun/telos/releases) page.

### 🪟 Windows

- Download the `.exe` or `.msi` installer and run it.
- _Note: Since the app is not yet signed by a major authority, you may see a "SmartScreen" warning. Click "More Info" -> "Run Anyway"._

### 🍎 macOS

- Download the `.dmg` file and drag Telos to your Applications folder.
- If you see a security warning on the first launch: _System Settings -> Privacy & Security -> Open Anyway._

### 🐧 Linux

- Download the `.AppImage` file.
- Right-click the file, grant **"Executable"** permissions, and run.

---

## 🔐 Privacy & Security

Telos is built on the principle of **Data Sovereignty**.

- **Where are my messages?** They exist strictly on your device and the recipient's device.
- **What does the server do?** The signaling server only facilitates the initial "handshake" to help peers find each other. It never sees, stores, or relays your message content.
- **Where are the keys?** Your encryption keys are stored in your operating system's native secure vault (Windows Credential Manager / macOS Keychain).

---

## 🛠️ Tech Stack

- **Languages:** [Rust](https://www.rust-lang.org/) & [TypeScript](https://www.typescriptlang.org/)
- **Frontend Framework:** [React](https://reactjs.org/) + [Tauri](https://tauri.app/)
- **Protocols:** WebRTC (P2P), WebSockets (Signaling), BitTorrent (WebTorrent)
- **Databases:** Local SQLite (Encrypted) + Remote PostgreSQL (Signaling metadata only)

---

## 📞 Support & Feedback

If you encounter any bugs or have feature suggestions, please open an [Issue](https://github.com/dogankarakoyun/telos-releases/issues) in this repository.

---

_Telos - Pure Communication, Protected._
