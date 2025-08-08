<!-- Badges -->
[![Android CI](https://github.com/st3rs/ForceWipeApp/actions/workflows/android.yml/badge.svg)](https://github.com/st3rs/ForceWipeApp/actions)
[![Latest Release](https://img.shields.io/github/v/release/st3rs/ForceWipeApp?display_name=tag&sort=semver)](https://github.com/st3rs/ForceWipeApp/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/st3rs/ForceWipeApp/total)](https://github.com/st3rs/ForceWipeApp/releases)

<p align="center">
  <a href="https://github.com/st3rs/ForceWipeApp/releases/latest/download/app-release.apk">
    <img src="https://img.shields.io/badge/Download-APK-blue?style=for-the-badge" alt="Download APK">
  </a>
</p>


# ForceWipeApp 🚀

> A silent panic wipe and shutdown tool built for GrapheneOS users and security professionals.

## 🔐 Overview
**ForceWipeApp** is a lightweight Android app that performs a full data wipe (including external storage) and powers off your device instantly.  
Designed for scenarios where you need fast, silent, and secure shutdown on demand.

- ✅ GrapheneOS Compatible
- ✅ MDM Device Owner Mode
- ✅ Factory Reset + External Wipe
- ✅ No UI — Executes immediately
- ✅ Emergency Kill-Switch Ready

---

## 📦 Installation

Install APK via ADB:

```bash
adb install ForceWipeApp.apk
adb shell dpm set-device-owner com.bomb.forcewipeapp/.MyDeviceAdminReceiver
```

> Note: Must be installed **before** setting up a user profile or adding a Google account.

---

## 🌐 GitHub Pages Demo

Try the landing page at:  
**[https://st3rs.github.io/ForceWipeApp](https://st3rs.github.io/ForceWipeApp)**

---

## 📄 License

MIT License. Use at your own risk.

---

## 🙌 Contributing

Pull requests and issues are welcome.

---

## 🧠 Author

Built with ❤️ by [@st3rs](https://github.com/st3rs)
