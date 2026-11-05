# Remote BLDC Fan 🌀
> **A native, ultra-lightweight, and completely ad-free Android remote control utility for BLDC ceiling fans.**

[![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?logo=android&logoColor=white)](https://android.com)
[![Size](https://img.shields.io/badge/Size-~800_KB-blue)](#-why-remote-bldc-fan)
[![License](https://img.shields.io/badge/License-Free_Utility-green)](#)
[![No Ads](https://img.shields.io/badge/Ads-100%25_Ad--Free-brightgreen)](#-key-features)

---

## 💡 The Problem & Why This App Exists
Most remote control apps available on the Google Play Store suffer from the same issues:
* **Disruptive Full-Screen Ads:** Opening the app or tapping a button often triggers intrusive pop-up advertisements.
* **Bloated Size & Slow Load Times:** Many third-party apps take up 30 MB to 60 MB of storage, run heavy background services, and lag upon launch.
* **Cluttered Interfaces:** Overcomplicated menus with confusing layouts.

**Remote BLDC Fan** was built out of practical necessity to solve these issues. It is an ultra-fast, minimalist remote utility written from scratch in native Android (Jetpack Compose). It loads instantly, respects your battery and storage, and provides a tactile, reliable physical remote experience directly on your smartphone.

---

## ✨ Key Features

* **🚫 100% Ad-Free Experience:** No banners, no interstitial full-screen ads, and zero telemetry tracking. It behaves like a clean utility.
* **⚡ Ultra-Lightweight (~800 KB):** Weighs under 1 MB. It takes seconds to install and uses almost zero RAM or background resources.
* **📱 Luxury Skeuomorphic Design:** Features a dark charcoal glossy finish, beveled physical buttons, subtle glass reflections, and top-mounted transmission LED feedback.
* **🔊 Tactile Feedback:** Integrated with realistic mechanical click sounds and uniform haptic vibrations on touch.
* **⚡ Native IR Optimization:** Custom-tuned NEC pulse bursts (38 kHz) engineered specifically for BLDC motor controllers to prevent missed signals or incomplete state transitions.

---

## 🎯 Supported Fan Brands & Profiles

The app features dedicated, pre-configured remote layouts for major BLDC ceiling fan brands[cite: 3, 5, 7, 11, 12]:

| Brand Profile | Status | Key Mappings Included |
| :--- | :--- | :--- |
| **Walton** | ✅ Fully Tested | Power, LED, Speeds 1–6, Speed 7 / MAX, Timers (2H, 4H, 6H, 8H), REV, ECO[cite: 12] |
| **Innoel** | ✅ Supported | Power, LED, Speeds 1–6, MAX, Timers (2H, 4H, 8H), SMT, REV[cite: 11] |
| **Atomberg** | ✅ Supported | Power, Speed Wheel, Light, Timer, Sleep, Boost[cite: 7, 10] |
| **Orient** | ✅ Supported | On, Off, Speeds 1–5, Timers (2H, 4H, 6H, 8H), LED, Boost[cite: 5, 9] |
| **Activa** | ✅ Supported | Power, Nature, Smart, Speeds 1–6, Boost, Light, Timers, REV[cite: 3, 8] |

> **Universal Compatibility Tip:** Even if your specific ceiling fan brand is not listed above, we recommend testing the available profiles. Many BLDC fan manufacturers share compatible infrared frequency codes and motor drivers.

---

## ⚠️ Hardware Requirements

* **Infrared (IR) Blaster Required:** Your smartphone **must** have a physical, built-in IR Blaster (Infrared emitter hardware) to communicate with the fan. 
  * Common on many Xiaomi, Redmi, Poco, Vivo, and selected OnePlus/Huawei devices.
* **No Network Required:** The app transmits pure infrared light signals. It does **not** rely on Wi-Fi, Bluetooth, local networks, or NFC.
* **Supported OS:** Android 8.0 (Oreo) and above.

---

## 📥 Installation Guide

1. Head over to the **[Releases](../../releases)** tab on the right sidebar of this repository.
2. Download the latest compiled **`Remote_BLDC_Fan.apk`** file.
3. Open the downloaded file on your Android device and confirm installation (allow installation from unknown sources if prompted).
4. Point your phone's top IR sensor directly at your BLDC ceiling fan and start controlling it instantly[cite: 3, 5, 7, 11, 12].

---

## 👨‍💻 Developer & Credits
Developed by **[Farhan Shahariar](https://facebook.com/iamfarhanzx)**[cite: 3, 5, 7, 11, 12].  
*Crafted for everyday reliability and clean digital experiences.*
