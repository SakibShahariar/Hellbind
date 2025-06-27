![git/assets/preview.gif](git/assets/preview.gif)

<h3 align="center">
  Hellbind Rice
</h3>

<p align="center">
  <a href="https://github.com/SakibShahariar/Hellbind/stargazers">
    <img src="https://img.shields.io/github/stars/SakibShahariar/Hellbind?style=for-the-badge&logo=starship&color=a6e3a1&logoColor=D9E0EE&labelColor=302D41">
  </a>
  <a href="https://github.com/SakibShahariar/Hellbind/issues">
    <img src="https://img.shields.io/github/issues/SakibShahariar/Hellbind?style=for-the-badge&logo=gitbook&color=fab387&logoColor=D9E0EE&labelColor=302D41">
  </a>
  <a href="https://github.com/SakibShahariar/Hellbind/contributors">
    <img src="https://img.shields.io/github/contributors/SakibShahariar/Hellbind?style=for-the-badge&logo=github&color=f38ba8&logoColor=D9E0EE&labelColor=302D41">
  </a>
</p>

# 🪴 Overview

**Hellbind** is a reactive GNOME rice built on Fedora 42. It uses your current wallpaper as the single source of truth to theme everything — from GTK to terminal — with no fixed palette, just pure **dynamic color extraction** powered by [`hellwal`](https://github.com/danihek/hellwal).

It’s minimalist, unified, and effortlessly adaptive. Just change your wallpaper — the rice will follow.

## 🧠 Main Principles

- Reactive theming based on wallpaper
- Cohesive visual identity across all apps
- Minimal distractions, maximum aesthetic impact

## 💜 System Setup

- **OS:** Fedora 42 (Wayland)
- **Color Source:** [`hellwal`](https://github.com/danihek/hellwal)
- **Desktop Environment:** GNOME
- **Shell:** Fish
- **Terminal:** Kitty
- **Editor:** Micro
- **File Manager:** Yazi
- **Browser Theme Sync:** Pywallzen
- **Folder Icon Script:** Custom Fish script to theme folders after wallpaper change

## 🧪 The Engine

Hellbind runs a Fish script that:

- 📂 Lets you pick or shuffle wallpapers
- 🖼 Sets it via GNOME `gsettings`
- 🌈 Runs `hellwal` for real-time color extraction
- 🎨 Applies colors to:
  - GTK 3 & 4 (`gtk.css`, `colors.css`)
  - Qt (`qt.conf`)
  - Kitty (`colors.conf`)
  - MPV
  - Micro editor
  - PywalZen/Pywalfox
  - Folder icons

Then it instantly updates terminal colors

## 🧩 Extensions Needed

- **Blur My Shell**
- **AppIndicator and KStatusNotifierItem Support**
- **Logo Menu**
- **Open Bar**
- **Pop Shell**
- **User Themes**
- **Vitals**
- **Weather O'Clock**


## 🖼️ Gallery

<img width=800 src="git/assets/screenshot1.png">
<img width=800 src="git/assets/screenshot2.png">
<img width=800 src="git/assets/screenshot3.png">
<img width=800 src="git/assets/screenshot4.png">

## 🛠️ Usage


