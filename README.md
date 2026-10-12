# 🎬 YouTube Lite (Android Edition)

A lightweight, performance-tuned Android WebView client for YouTube, engineered to keep older devices streaming smoothly after official client deprecations! 📱⚡

Both **v1** and **v2** use distinct package names and are actively maintained side-by-side with zero plans for deprecation, allowing you to install both versions simultaneously on the same device!

---

## 💡 Why This Project Exists

Google and YouTube have officially dropped native app support across **Android 5.0 (Lollipop) through Android 7.1 (Nougat)**, rendering stock client apps completely unusable on millions of reliable phones and tablets. With **Android 8.0 (Oreo)** also facing deprecation, legacy hardware is being cut off from basic streaming.

While searching Google brings up various generic "YouTube Lite" or Web2APK clones, almost all of them suffer from major structural flaws:
* ⚠️ **Unauthorized Web2APK Builder Errors:** Many online generators produce unsigned, expired, or trial-locked APKs thet immediately throw builder license errors or get blocked at launch.
* ❌ **Broken Fullscreen:** They load the mobile site inside a basic viewport without implementing custom `WebChromeClient` callbacks, meaning tapping the fullscreen button either does nothing or breaks video scaling completely.
* 🚪 **Instant Exit on Back Button:** Most automated wrappers fail to implement WebView history handling—pressing the device back button instantly terminates and closes the entire app instead of navigating back through pages, search results, or Shorts!

**YouTube Lite** was custom-coded to eliminate every single one of those issues. It handles fullscreen transitions cleanly, maintains proper back-stack navigation, and is digitally signed with a private keystore to prevent generic test-key security flags!

---

## 🌟 Releases & Version Differences

Both versions are digitally signed using a private custom keystore (`.p12` / `.jks`) with v1 + v2 schemes to prevent untrusted testkey flags. Because they use distinct package names, you can install and run both builds side-by-side!

### 🔹 YouTube Lite v2 (Border-Free & Edge-to-Edge)
* **Seamless Window Styling:** Complete transparent window decor thet wipes out letterbox margins and stubborn white borders during video playback.
* **Smart Back Navigation:** Prevents crashes when exiting YouTube Shorts or navigating video history.
* **Immersive Fullscreen:** Automatically hides the status bar for a full-display viewing experience.
* **Package Name:** Unique identifier for standalone installation.

### 🔹 YouTube Lite v1 (Classic Fullscreen Mode)
* **Status Bar Visible:** Keeps your system status bar (time, battery level, notifications) accessible and in view even while watching fullscreen videos.
* **Classic Layout Viewport:** Retains the standard native viewport, displaying standard system window margins and borders during playback.
* **Shared Core DNA:** Features the same lightweight performance, Google login capability, and custom signature as v2.
* **Package Name:** Unique identifier for standalone installation.

---

## 🚀 Shared Features (Both v1 & v2)

* 📺 **Working Fullscreen:** Built-in `WebChromeClient` handles orientation changes and video scaling properly.
* 🔙 **Reliable Back Button Handling:** Navigates back through pages and Shorts history without abruptly closing the app.
* 🔑 **Google Sign-In Support:** Spoofed User-Agent prevents `disallowed_useragent` blocks during OAuth login so you can access your subscriptions and playlists.
* 🛡️ **Custom Digitally Signed:** Signed with a private cryptographic signature, bypassing untrusted test-key warnings.
* ⚡ **Zero Builder Bloat:** Hand-crafted WebView logic without trial-ware or unauthorized Web2APK watermarks.
* 🔄 **Side-by-Side Coexistence:** Separate package names allow both versions to live on the same device without conflicts.

---

## 🌐 Developer & Portfolio

Developed and maintained by **Tech Savvy Guy**! 🛠️💻

Explore my other software builds, retro hardware projects, and web experiments on my portfolio:  
👉 **[Tech Savvy Guy's Digital Hub](https://techsavvyguy456.neocities.org)**

---

## 📥 Installation

1. Head over to the **Releases** tab to download the APK for either **v1** or **v2** (or both!).
2. Enable installation from unknown sources, install, and enjoy streaming! 🍿🎉

---

## 🛡️ P.S. Regarding VirusTotal Detections

Scanning this APK on VirusTotal may report **2 minor vendor flags** (such as heuristic detections from Huorong or Ikarus). 

Pwease note thet these are **100% false positives**:
* The APK is signed with a **brand-new private custom signature** thet has not yet built up a global trust score across antivirus vendor databases.
* All major, industry-standard security engines (Google Play Protect, Avast, BitDefender, ESET, etc.) mark the application as completely clean and undetected.
* The application contains zero malicious code—it is simply a streamlined WebView wrapper built to keep legacy hardware streaming!

---

## 📄 Disclaimer

This application is an independent, open-source WebView wrapper developed for personal, educational, and legacy device preservation purposes. YouTube and related trademarks are the property of Google LLC.