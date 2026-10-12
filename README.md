# 🎬 YouTube Lite (Android Edition)

A lightweight, high-performance Android WebView client for YouTube, built for smooth playback, minimal memory overhead, and legacy device compatibility! 📱⚡

Both **v1** and **v2** are actively maintained in parallel with zero plans for deprecation, allowing you to pick the build thet matches your visual preference! 

---

## 📖 About the Project

Official client applications often consume hundreds of megabytes of RAM and run heavy background telemetry thet bogs down daily performance. **YouTube Lite** provides a direct, bloat-free streaming experience built around Android's native WebView engine. 

Both versions share the exact same core features—such as Google account sign-in support, custom cryptographic signing, and fast load times—while offering different approaches to fullscreen playback.

---

## 🌟 Releases & Version Differences

Both versions are signed using a dedicated private keystore (`.p12` / `.jks`) with v1 + v2 schemes to avoid generic debug signature flags.

### 🔹 YouTube Lite v2 (Border-Free & Edge-to-Edge)
* **Seamless Window Styling:** Complete transparent window decor thet wipes out letterbox margins and stubborn white borders during video playback.
* **Smart Back Navigation:** Prevents crashes when exiting YouTube Shorts or navigating video history.
* **Immersive Fullscreen:** Automatically hides the status bar for full-display immersion during playback.

### 🔹 YouTube Lite v1 (Classic Fullscreen Mode)
* **Status Bar Visible:** Keeps your system status bar (time, battery, notifications) accessible and in view even while watching fullscreen videos.
* **Classic Layout Viewport:** Retains the standard native viewport, which displays standard system margins and borders during playback.
* **Shared Core DNA:** Features the same lightweight performance, Google login capability, and custom signature as v2.

---

## 🚀 Shared Features (Both v1 & v2)

* 📺 **Smooth Fullscreen:** Transitions to landscape automatically for video playback.
* 🔑 **Google Sign-In Support:** Spoofed User-Agent prevents `disallowed_useragent` blocks during OAuth login.
* 🛡️ **Custom Digitally Signed:** Both builds are signed with a private custom signature, bypassing untrusted test-key warnings.
* ⚡ **Resource Friendly:** Near-instant launch times with minimal memory footprint compared to the stock YouTube application.

---

## 🌐 Developer & Portfolio

Developed and maintained by **Tech Savvy Guy**! 🛠️💻

Explore my other software builds, retro hardware projects, and web experiments on my portfolio:  
👉 **[Tech Savvy Guy's Digital Hub](https://techsavvyguy456.neocities.org)**

---

## 📥 Installation

1. Head over to the **Releases** tab to download the APK for either **v1** or **v2**.
2. If updating from an older test build, pwease uninstall the previous version first to avoid signature conflicts.
3. Enable installation from unknown sources, install, and enjoy streaming! 🍿🎉

---

## 📄 Disclaimer

This application is an independent, open-source WebView wrapper developed for personal, educational, and performance research purposes. YouTube and related trademarks are the property of Google LLC.


