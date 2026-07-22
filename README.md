<div align="center">

  <!-- Hero Badges -->
  <p>
    <img src="https://img.shields.io/badge/Chrome-Extension-4285F4?logo=googlechrome&logoColor=white&style=for-the-badge" alt="Chrome Extension">
    <img src="https://img.shields.io/badge/Edge-Extension-0078D7?logo=microsoftedge&logoColor=white&style=for-the-badge" alt="Edge Extension">
    <img src="https://img.shields.io/badge/Brave-Extension-FB542B?logo=brave&logoColor=white&style=for-the-badge" alt="Brave Extension">
    <img src="https://img.shields.io/badge/License-MIT-22c55e?style=for-the-badge" alt="License: MIT">
  </p>

  <!-- Title -->
  <h1>🛡️ NOTHING</h1>
  <p><b>Advanced Browser Privacy & Digital Fingerprint Management</b></p>
  <p><i>Take full control of your digital footprint, network traffic, and online identity.</i></p>

  <!-- Quick Links -->
  <p>
    <a href="#-features">Features</a> •
    <a href="#-installation">Installation</a> •
    <a href="#-project-structure">Structure</a> •
    <a href="#-settings-reference">Settings</a> •
    <a href="#-license">License</a>
  </p>

</div>

---

## ⚠️ Disclaimer

> [!WARNING]
> This extension is built **exclusively** for privacy protection, digital fingerprint management, and network traffic analysis.  
> **Always use official builds from this repository.** Third-party builds may compromise your security.

---

## 🔒 Full Control & Customization

> [!IMPORTANT]
> You decide how protection works:
> - **One-click toggle** to completely disable the extension.
> - **Per-site exceptions** for domains that need unrestricted access.
> - **Granular spoofing** of OS (Windows, macOS, Linux), timezone, and WebRTC settings.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| **🎛️ Master Toggle** | Instantly enable or disable the entire extension with a single click. |
| **📋 Site Exceptions** | Disable protection for specific pages or domains to prevent breakage on trusted sites. |
| **📊 Traffic Monitor** | Real-time stats on active domains, requests, packet loss, data volume, and blocked trackers — right in the popup. |
| **🖥️ System Spoofing** | Choose OS profiles (Windows, Linux, macOS) paired with browser signatures to mask your real device. |
| **🎨 Fingerprint Protection** | Canvas & Audio noise injection, adaptive noise aggression, real-time WebGL spoofing, and anti-fraud/geo-tracker blocking — each with its own toggle. |
| **🌐 WebRTC Control** | Robust IP-leak prevention with a per-site whitelist (e.g., `meet.google.com`). |
| **🕐 Timezone Spoofing** | Spoof your timezone to match any location, or disable it entirely. |
| **⚡ Lightweight** | Zero bloat architecture designed for stability and minimal browser overhead. |

---

## 🚀 Installation

Get up and running in under 60 seconds:

| Step | Action |
|------|--------|
| **1** | Click **Code** → **Download ZIP** at the top of this repository. |
| **2** | Extract the ZIP to a dedicated folder on your machine. |
| **3** | Open your browser (Chrome, Edge, or Brave) and navigate to `chrome://extensions/`. |
| **4** | Enable **Developer mode** using the toggle in the top-right corner. |
| **5** | Click **Load unpacked** and select the extracted project folder. |

> 💡 **Pro tip:** Pin the extension icon to your toolbar for instant access to settings and traffic stats.

---

## 📁 Project Structure

```text
📁 nothing/
├── 📁 assets/            # UI styles and interface resources
├── 📁 icons/             # Extension icons
├── 📄 background.js      # Background service worker
├── 📄 content-loader.js  # Script injection loader
├── 📄 inject.js          # Injected content script
├── 📄 manifest.json      # Extension manifest
├── 📄 popup.html         # Popup UI markup
└── 📄 popup.js           # Popup logic and state management
