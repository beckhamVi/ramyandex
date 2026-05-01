# Ramyandex

Custom Linux desktop environment built on Wayland with Hyprland and Qt.

A personal project to build a full desktop ecosystem from scratch:
launcher, widgets, themes, animations, and system integration.

---

## 🚀 Current Status

Early development (foundation stage)

Working:
- Hyprland setup
- Qt6 + QML launcher base
- GitHub integration (dotfiles repo)

---

## 🧱 Architecture

ramyandex/
├── hypr/ # Hyprland configuration
├── launcher/ # Qt/QML application launcher (WIP)
├── qml/ # UI components and designs
├── qt-shell/ # future widgets system (CPU, volume, etc.)
├── scripts/ # utilities (brightness, audio, etc.)
├── sddm/ # login screen theme (future animated)
├── wallpapers/ # images and video wallpapers


---

## ⚙️ Core Stack

- :contentReference[oaicite:0]{index=0} → window manager
- :contentReference[oaicite:1]{index=1} → launcher & UI system
- QML → UI/animations
- C++ → performance backend
- Wayland → modern display server

---

## 🎯 Goals

- Custom launcher (fast + animated)
- Widgets system (CPU, GPU, volume, music)
- Animated SDDM login screen
- Video wallpapers support
- Fully modular dotfiles system
- Instant setup from GitHub

---

## ⌨️ Current Launcher (WIP)

- Built with Qt6 + QML
- Opens manually or via Hyprland keybind
- Base UI implemented
- Next: system app launcher integration

---

## 🔥 Vision

A fully custom Linux desktop that feels:
- fast ⚡
- minimal 🎨
- animated ✨
- fully personal 🧠

---

## 📌 Setup

```bash
git clone git@github.com:beckhamVi/ramyandex.git
cd ramyandex
