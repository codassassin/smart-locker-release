# Smart Locker

![GitHub release (latest by date)](https://img.shields.io/github/v/release/codassassin/smart-locker-release)
![GitHub last commit](https://img.shields.io/github/last-commit/codassassin/smart-locker-release)
![GitHub stars](https://img.shields.io/github/stars/codassassin/smart-locker-release?style=social)
![GitHub license](https://img.shields.io/github/license/codassassin/smart-locker-release)

**Smart Locker** is a secure Windows folder locker application that supports fingerprint authentication with a fallback password mechanism. It's designed for users who want a privacy-first, local-only solution for sensitive folders.

## 🔐 Features

- ✅ Fingerprint authentication (via `FingerprintAuthApp.exe`)
- 🔁 Fallback password-based access
- 🕒 Auto-hide/lock folder after short delay (e.g., 20 seconds)
- 💡 Minimal, fast, and local-only (no internet required)
- 📦 Packaged as a single `.exe` with embedded logic

## 📁 Repository Contents

```
📦 SmartLocker
├── SmartLocker.exe            # Main application (compiled from batch script)
└── FingerprintAuth/           # Required fingerprint libraries and DLLs
```

> ⚠️ Do not remove or rename the `FingerprintAuth` folder. It must stay in the same directory as the `SmartLocker.exe`.

## 🚀 How to Use

1. **Download and extract** the latest release.
2. **Double-click `SmartLocker.exe`** to run the app.
3. Authenticate using your fingerprint (or enter your fallback password if fingerprint fails).
4. The secure folder will unlock and open.
5. After 20 seconds, it will automatically lock and hide again.

## 📌 Notes

- Fingerprint authentication relies on your Windows Hello biometric system.
- All logic is self-contained—no external network communication.
- Works best on Windows 10 and 11 with administrative privileges.

## 📃 License

MIT License © 2025 Souvik Chatterjee
