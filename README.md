# DesktopSwitcher

DesktopSwitcher is a lightweight macOS menu bar application that lets you  
quickly **toggle desktop icons ON/OFF** using a global hotkey or tray menu.

This tool is inspired by utilities like *HiddenMe*, but fully reimplemented in  
**C++ / Qt 6** with additional flexibility and open-source control.

---

## Features

- 🔁 Toggle **desktop icons visibility** instantly  
- ⌨️ **Global hotkey support** (default: `Ctrl + Shift + K`)  
- 🖥️ Runs **only in the menu bar** (no Dock icon, via `LSUIElement`)  
- 🚀 Optional **Launch at Login** using a macOS LaunchAgent  
- 📁 Open the Desktop folder directly from the menu  
- 🧱 Implemented using Qt 6 and QHotkey

---

## Requirements

- macOS 12 or later (Apple Silicon & Intel supported)
- Qt 6 (tested with Qt 6.10.1)
- CMake ≥ 3.16
- C++17 compatible compiler (AppleClang recommended)

---

## How to Use

1. Launch `DesktopSwitcher.app`  
2. The app appears **only in the menu bar**
3. Toggle desktop icons via:
   - Menu item **"Hide Desktop Icons"**
   - Global hotkey **Ctrl + Shift + K**
4. Enable “Launch at Login” to start automatically after login

---

## Build Instructions

Clone the repository:

```bash
git clone https://github.com/youbo0129ueno-star/DesktopSwitcher.git
cd DesktopSwitcher
