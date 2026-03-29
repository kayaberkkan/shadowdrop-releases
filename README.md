<div align="center">

# ShadowDrop

<img width="90" height="90" alt="shadow_drop_logo" src="https://github.com/user-attachments/assets/8e6a8b4a-bfc7-490c-9748-9c638f3d2e6a" />

**Secure & Instant Cross-Platform File Sharing**

[![Go](https://img.shields.io/badge/Go-1.21+-00ADD8?style=for-the-badge&logo=go&logoColor=white)](https://go.dev)
&nbsp;
[![Wails](https://img.shields.io/badge/Wails-V2-red?style=for-the-badge&logo=wails&logoColor=white)](https://wails.io)
&nbsp;
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

<p align="center">
  <img src="https://img.shields.io/badge/Platform-8A8A8A?style=for-the-badge" /><img src="https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=apple&logoColor=white" /><img src="https://img.shields.io/badge/Windows-0078D4?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0wIDMuNDQ5TDkuNzUgMi4xdjkuNDUxSDBWMy40NDl6bTkuNzUgOS4xMzlWMjIuMWwtOS43NS0xLjM1MVYxMi41ODloOS43NXptMS41LTkuNTM5TDI0IDB2MTEuNTVoLTEyLjc1VjMuMDR6bTEyLjc1IDkuNTRWMjRsLTEyLjc1LTMuMTVWMTIuNThIMjR6Ii8+PC9zdmc+&logoColor=white" /><img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
</p>

[![Encryption](https://img.shields.io/badge/Security-AES--256--GCM-green?style=for-the-badge)](/)

---

Experience seamless clipboard and file synchronization across all your devices with end-to-end encryption. Eliminate the complexity of traditional transfer methods.

</div>

---

## 📋 Table of Contents

- [🎯 About the Project](#-about-the-project)
- [✨ Features](#-features)
- [🖥️ Screenshots](#️-screenshots)
- [🛠️ Technologies](#️-technologies)
- [🚀 Installation & Usage](#-installation--usage)
- [🛡️ Security](#️-security)
- [👤 Developer](#-developer)

---

## 🎯 About the Project

**ShadowDrop** is a lightweight, high-security tool that brings the convenience of AirDrop to all operating systems (Windows, macOS, Linux). It allows you to instantly share files, folders, and clipboard content between devices on the same local network (via mDNS) or remote networks (via Tailscale, VPN, or WAN) using manual IP entry. No cloud servers, no complex cables required.

---

## ✨ Features

| Feature | Description |
|---------|----------|
| ⚡ **Smart Discovery** | Instant discovery using mDNS technology. No IP entry needed on local networks. |
| 🌐 **Flexible Connection** | Support for manual IP entry to connect via Tailscale or WAN. |
| 🔒 **E2E Encryption** | All data traffic is secured with AES-256-GCM at a military-grade level. |
| 🔄 **Live Sync** | Real-time clipboard synchronization across all connected devices. |
| 💻 **Cross-Platform** | A fully native experience on Windows (.exe), macOS (.app), and Linux. |

---

## 🖥️ Screenshots

<div align="center">

#### 📊 Main Interface
<p align="center">
  <table>
    <tr>
      <td><img width="562" height="802" alt="Main Screen" src="https://github.com/user-attachments/assets/1c6821fa-2993-4b7e-aa02-5633ebca98b2"/></td>
      <td><img width="562" height="802" alt="Main Screen_2" src="https://github.com/user-attachments/assets/f29f79af-8a5b-4189-aecf-6c87245cdbc3"/></td>
    </tr>
  </table>
</p>

#### ⚙️ Settings & Security Panel
<p align="center">
  <table>
    <tr>
      <td>
        <img width="562" height="802" alt="Settings" src="https://github.com/user-attachments/assets/59d97ce1-2296-46b3-92f0-0e0938a3a0c6" />
      </td>
    </tr>
  </table>
</p>
</div>

---

## 🛠️ Technologies

<div align="center">

| Category | Technology |
|:--------:|:---------:|
| **Backend** | ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![mDNS](https://img.shields.io/badge/mDNS-Discovery-blue?style=flat-square) |
| **Frontend** | ![JS](https://img.shields.io/badge/Vanilla_JS-ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) ![Wails](https://img.shields.io/badge/Wails-V2-red?style=flat-square&logo=wails&logoColor=white) |
| **Security** | ![AES](https://img.shields.io/badge/AES--256--GCM-Encryption-green?style=flat-square) ![Argon2](https://img.shields.io/badge/Argon2-Key_Derivation-orange?style=flat-square) |
| **Platform** | ![macOS](https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white) ![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) |

</div>

---

## 🚀 Installation & Usage

### 1. Download & Installation
Download the latest version for your OS from the [Releases](https://github.com/kayaberkkan/shadowdrop-releases/releases) page.

- **Windows:** Run `ShadowDrop.exe`.
- **macOS:** Move `ShadowDrop.app` to your Applications folder and launch it.
- **Linux:** Make the binary executable and launch it.

### 2. Usage Steps
1. Launch ShadowDrop on both devices.
2. Set the same **Sync Secret** (password) on both devices in the Settings.
3. Devices will find each other automatically on local networks; for different networks, enter the Hub's IP address manually.
4. Drag & Drop files or just copy text to sync instantly.

---

## 🛡️ Security

ShadowDrop is built on industry-leading encryption standards:
- **End-to-End Encryption (E2EE):** Your data can only be decrypted by the shared secret you set. Data is never transmitted as plain text.
- **Key Derivation (Argon2id):** A 32-byte key is derived from your password using **Argon2id**, the modern state-of-the-art algorithm resistant to brute-force attacks.
- **Data Integrity (AES-256-GCM):** Using AES-GCM mode ensures both the confidentiality and integrity of every transmitted packet, guaranteeing it hasn't been tampered with.
- **Zero-Cloud Architecture:** Data never leaves your controlled network environment; all traffic stays within encrypted tunnels without any third-party cloud intermediaries.

---

## 👤 Developer

<div align="left">

**Berkkan KAYA**

[![GitHub](https://img.shields.io/badge/GitHub-kayaberkkan-181717?style=for-the-badge&logo=github)](https://github.com/kayaberkkan)

</div>

---
