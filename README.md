# antaraFlow

A small, native app for Mac and Windows that puts all your messaging services (WhatsApp, Telegram, Mail, Outlook and more) in one window. Each service keeps its own login, and unread counts show on the Dock or taskbar and in the menu bar or system tray.

This repository only hosts the downloads. The Mac app is notarized by Apple. The Windows installer is not signed yet, so Windows SmartScreen may warn: choose More info, then Run anyway.

## Install

The easiest way is the download page: https://flow.antara.ooo/ (it always shows the newest version).

**Mac:** get `antaraFlow-<version>.dmg` from the [latest release](../../releases/latest), open it and drag antaraFlow to Applications.

**Windows:** get `antaraFlow-<version>-windows-x64-setup.exe` from the [latest release](../../releases/latest) and run it. It installs for you alone and needs no administrator rights.

**Homebrew (Mac):**

```sh
brew tap ayeh/antaraflow
brew trust ayeh/antaraflow
brew install --cask antaraflow
```

Newer Homebrew versions ask you to trust a tap before using it; `brew trust` does that for this one only.

## Requirements

macOS 13 (Ventura) or later, or Windows 10 or later (64-bit).

## Updates

antaraFlow checks for new versions itself: Settings › About › Check for updates. Homebrew users on a Mac can also run `brew upgrade --cask antaraflow`.

---

**Bahasa Melayu:** muat turun fail `.dmg` dari [release terbaru](../../releases/latest), buka, dan seret antaraFlow ke folder Applications.
