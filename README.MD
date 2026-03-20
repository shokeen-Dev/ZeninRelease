# 🌌 Zenin v1.0

<div align="center">

[![Downloads](https://img.shields.io/github/downloads/shokeen-Dev/ZeninRelease/total?style=for-the-badge&color=7928CA&logo=github)](https://github.com/shokeen-Dev/ZeninRelease/releases)
[![Latest Release](https://img.shields.io/github/v/release/shokeen-Dev/ZeninRelease?style=for-the-badge&color=0070f3)](https://github.com/vishu/ZeninApp/releases)
[![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?style=for-the-badge&logo=android)](https://github.com/shokeen-Dev/ZeninRelease/releases)
[![License](https://img.shields.io/badge/License-GPL%20v3.0-green?style=for-the-badge)](LICENSE)

**A high-performance, minimalist anime streaming experience built with native dual-thread architecture.**

[Explore Releases](https://github.com/shokeen-Dev/ZeninRelease/releases) · [Report Bug](https://github.com/shokeen-Dev/ZeninRelease/issues) · [Request Feature](https://github.com/shokeen-Dev/ZeninRelease/issues)

</div>

---

## 📱 Visual Experience
<div align="center">
  <table style="width:100%">
    <tr>
      <td width="33%"><img src="[https://private-user-images.githubusercontent.com/192494597/566884568-8eac04b0-861d-41c0-9f35-9f3ff9db39cd.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzQwMTc1OTMsIm5iZiI6MTc3NDAxNzI5MywicGF0aCI6Ii8xOTI0OTQ1OTcvNTY2ODg0NTY4LThlYWMwNGIwLTg2MWQtNDFjMC05ZjM1LTlmM2ZmOWRiMzljZC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwMzIwJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDMyMFQxNDM0NTNaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1kNzM2YzU2MzhiZTM2NzcyZjA5ZmVhMWViOWUyNzY2ZDBmODJlODg5NjcwYmVlZmE2MTMxNWVkYzdhZDM3NWIwJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.QarwouCy8jvX2-Pe8nygem4KiVNZ4eKqlk_1FglzpKA]" alt="Home Screen" /></td>
      <td width="33%"><img src="[https://private-user-images.githubusercontent.com/192494597/566884569-e5df996b-13f5-4512-bf07-f24a9574c515.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzQwMTc1OTMsIm5iZiI6MTc3NDAxNzI5MywicGF0aCI6Ii8xOTI0OTQ1OTcvNTY2ODg0NTY5LWU1ZGY5OTZiLTEzZjUtNDUxMi1iZjA3LWYyNGE5NTc0YzUxNS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwMzIwJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDMyMFQxNDM0NTNaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT05ZWYzYTc1NmMyMzhiODYxOWVkNDlhMzM0ZTJhYWJmOWVjOGNjYjZiYTZmNjI2NGM1MmZjNmNmOWY5ZWVlYzc5JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.ghqGWnKA2iQjEu99RpBqixdfjBbzUkRBeNp5HkAgk4w]" alt="Player View" /></td>
      <td width="33%"><img src="[https://private-user-images.githubusercontent.com/192494597/566884571-744c963f-6548-4e4d-9a0e-71832cbd8ec5.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzQwMTc1OTMsIm5iZiI6MTc3NDAxNzI5MywicGF0aCI6Ii8xOTI0OTQ1OTcvNTY2ODg0NTcxLTc0NGM5NjNmLTY1NDgtNGU0ZC05YTBlLTcxODMyY2JkOGVjNS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwMzIwJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDMyMFQxNDM0NTNaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1jMDI2OGNjN2MwYzcxZDVlMzMzNjg0NjQ4YjFhZDUzZDcyMWE5YTZkYTBlN2ZiYjA1ZWQ5OTJjZDg4NWZjN2M5JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.nboUfN4nPaWNZeKWSwUdteXhTpF3MyvIzxYA0GiL0GY]" alt="Search & Caching" /></td>
    </tr>
    <tr>
      <td align="center"><b>Minimalist Home</b></td>
      <td align="center"><b>Native Player</b></td>
      <td align="center"><b>Smart Search</b></td>
    </tr>
  </table>
</div>

---

## 🚀 Key Features

* ✨ **Premium Minimalist UI:** A sleek interface designed for clarity and ease of navigation.
* ⚡ **Instant Rendering:** Leveraging Lynx’s dual-thread model for smooth 60FPS interactions.
* 🛡️ **Local-First Privacy:** Your viewing history and preferences stay strictly on your device.
* 🎬 **Dynamic Native Streaming:** High-efficiency video rendering for stable, high-quality playback.
* 🧠 **Smart Caching:** Optimized data management that stores essential info locally while fetching fresh links on-demand.

---

## 🛠️ Technical Architecture

Zenin is built using a modern mobile stack designed for maximum efficiency and "web-native" hybrid performance.

* **Core Logic:** [ReactLynx](https://lynxjs.org/) (React-based Background Scripting)
* **Native Bridge:** Kotlin (Android Native Modules)
* **Styling:** Pure CSS (Transitions, Flexbox, & Gradients)
* **State Management:** [Zustand](https://github.com/pmndrs/zustand) (Lightweight, persistent state)
* **Performance:** Lynx Main-Thread Scripting (MTS) for silky-smooth gestures.

---

## 📥 Installation

1.  **Download:** Grab the latest `Zenin.apk` from the [Official Releases](https://github.com/shokeen-Dev/ZeninRelease/releases).
2.  **Permissions:** Enable "Install from Unknown Sources" in your Android settings.
3.  **Install:** Open the file and follow the prompts.
4.  **Security:** The app includes built-in signature integrity checks to ensure authenticity.

---

## 💎 v1.0.0 Release Notes
* Initial stable release of the **Zenin Core**.
* Implemented **Zustand store** for persistent local caching.
* Integrated **Native Video Modules** for hardware-accelerated playback.
* Added **Trending Content** algorithm for real-time discovery.
* Optimized APK size for faster distribution.

---

## ⚖️ License & Privacy
This project is licensed under the **GNU GPL v3.0**. 

**Educational Purpose:** Zenin is a technical exploration into cross-platform frameworks and native rendering. Users are responsible for ensuring their usage complies with local streaming regulations.

---
**Developer:** [Shokeen] 👨‍💻  
*Built with passion for the anime community.*
