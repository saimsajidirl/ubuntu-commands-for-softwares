# Ubuntu Software Installation Commands (with sudo -y)

## System Update (Do First)
```bash
# Update and Upgrade
sudo apt update && sudo apt upgrade -y
```

---

## Development & Programming
```bash
# Git
sudo apt install -y git

# Curl
sudo apt install -y curl

# Wget
sudo apt install -y wget

# Build Essentials
sudo apt install -y build-essential

# Python
sudo apt install -y python3

# Python Pip
sudo apt install -y python3-pip

# Python Venv
sudo apt install -y python3-venv

# Node.js
sudo apt install -y nodejs

# npm (Node Package Manager)
sudo apt install -y npm

# Docker
sudo apt install -y docker.io

# Docker Compose
sudo apt install -y docker-compose
```

---

## AI
```bash
# Claude Desktop
curl -fsSL https://pkg.claude-desktop-debian.dev/KEY.gpg | sudo gpg --dearmor -o /usr/share/keyrings/claude-desktop.gpg && echo "deb [signed-by=/usr/share/keyrings/claude-desktop.gpg arch=amd64,arm64] https://pkg.claude-desktop-debian.dev stable main" | sudo tee /etc/apt/sources.list.d/claude-desktop.list && sudo apt update && sudo apt install claude-desktop
```

---

## Text Editors & IDEs
```bash
# VS Code
sudo apt install -y code

# Sublime Text
sudo apt install -y sublime-text
```

---

## Office & Productivity
```bash
# LibreOffice
sudo apt install -y libreoffice
```

---

## Multimedia (Audio, Video, Image Editing)
```bash
# VLC Media Player
sudo apt install -y vlc

# Audacity (Audio Editor)
sudo apt install -y audacity

# FFmpeg (Video/Audio Converter)
sudo apt install -y ffmpeg

# FFmpeg Thumbnailer (Thumbnail Generator)
sudo apt install -y ffmpegthumbnailer

# Kdenlive (Video Editor)
sudo apt install -y kdenlive

# OpenShot Qt (Video Editor)
sudo apt install -y openshot-qt

# OBS Studio (Screen Recording/Streaming)
sudo apt install -y obs-studio

# HandBrake CLI (Video Converter)
sudo apt install -y handbrake-cli

# GIMP (Image Editor)
sudo apt install -y gimp

# Krita (Digital Painting)
sudo apt install -y krita
```

---

## Internet & Communication
```bash
# Firefox Browser
sudo apt install -y firefox

# Chromium Browser
sudo apt install -y chromium-browser

# Google Chrome
sudo apt install -y google-chrome-stable

# Brave Browser (Nightly)
sudo curl -fsSLo /usr/share/keyrings/brave-browser-nightly-archive-keyring.gpg https://brave-browser-apt-nightly.s3.brave.com/brave-browser-nightly-archive-keyring.gpg && sudo curl -fsSLo /etc/apt/sources.list.d/brave-browser-nightly.sources https://brave-browser-apt-nightly.s3.brave.com/brave-browser.sources && sudo apt update && sudo apt install -y brave-origin-nightly

# Zen Browser
curl -fsSL https://github.com/zen-browser/updates-server/raw/refs/heads/main/install.sh | $SHELL
```

---

## System Utilities
```bash
# Dconf Editor (Settings Editor)
sudo apt install -y dconf-editor

# GNOME Tweaks (Desktop Customization)
sudo apt install -y gnome-tweaks

# Timeshift (System Backup)
sudo apt install -y timeshift

# RAR (Archive Manager - RAR format)
sudo apt install -y rar

# Unrar (Extract RAR files)
sudo apt install -y unrar

# Grep (Text Search Utility)
sudo apt install -y grep

# GNOME System Monitor (Hardware Monitoring)
sudo apt install -y gnome-system-monitor

# Htop (Process Manager)
sudo apt install -y htop
```

---

## Download & File Management
```bash
# Aria2 (Download Manager)
sudo apt install -y aria2

# Rsync (Fast File Copy)
sudo apt install -y rsync
```

---

## Database Tools
```bash
# PostgreSQL
sudo apt install -y postgresql

# PostgreSQL Contrib
sudo apt install -y postgresql-contrib

# MySQL Server
sudo apt install -y mysql-server

# SQLite3
sudo apt install -y sqlite3

# MongoDB
sudo apt install -y mongodb

# Redis Server
sudo apt install -y redis-server

# DBeaver Community Edition (Database GUI)
sudo apt install -y dbeaver-ce

# pgAdmin4 (PostgreSQL GUI)
sudo apt install -y pgadmin4
```

---

## USB & System Tools
```bash
# Balena Etcher (USB Bootable Creator)
sudo snap install balena-etcher-electron

# CPU-X (CPU Information)
sudo apt install -y cpu-x
```

---

## Video Editing & Streaming
```bash
# DaVinci Resolve (Professional Video Editor)
sudo snap install davinci-resolve
```

---

## Virtualization
```bash
# VirtualBox (Virtual Machines)
sudo apt install -y virtualbox

# libvirt (Virtualization Library)
sudo apt install -y libvirt-daemon-system
```

---

## Security & Privacy
```bash
# OpenSSH Server
sudo apt install -y openssh-server

# OpenSSH Client
sudo apt install -y openssh-client

# OpenSSL (Encryption)
sudo apt install -y openssl

# GPG (Encryption/Signing)
sudo apt install -y gpg

# KeePassXC (Password Manager)
sudo apt install -y keepassxc

# VeraCrypt (Disk Encryption)
sudo apt install -y veracrypt

# Wireshark (Network Analyzer)
sudo apt install -y wireshark

# Nmap (Network Scanner)
sudo apt install -y nmap

# Fail2ban (Intrusion Prevention)
sudo apt install -y fail2ban

# ClamAV (Antivirus Scanner)
sudo apt install -y clamav clamav-daemon
```

---

## Gaming
```bash
# Steam (Gaming Platform)
sudo apt install -y steam

# Wine (Windows Compatibility)
sudo apt install -y wine

# Wine 32-bit Support
sudo apt install -y wine32
```

---

## Screen Recording & Streaming
```bash
# Kazam (Screen Recorder)
sudo apt install -y kazam
```

---

## Desktop Enhancements
```bash
# GNOME Wallpapers
sudo apt install -y wallpapers-gnome-backgrounds
```

---

## Package Managers
```bash
# Snap Package Manager
sudo apt install -y snapd

# Flatpak Package Manager
sudo apt install -y flatpak
```

---

## Clipboard Manager (Windows+V equivalent)
```bash
# CopyQ (Clipboard Manager)
sudo apt install -y copyq
```

---

## PDF Tools
```bash
# Okular (PDF Editor & Viewer)
sudo apt install -y okular
```

---

## System Cleanup
```bash
# Remove unused packages
sudo apt autoremove -y

# Remove cache
sudo apt autoclean -y

# Clean package cache
sudo apt clean
```

---

## Install Everything at Once (Recommended)
```bash
# Copy and run this single command to install most tools
sudo apt update && sudo apt upgrade -y && sudo apt install -y git curl wget build-essential python3 python3-pip python3-venv nodejs npm docker.io docker-compose code sublime-text libreoffice vlc audacity ffmpeg ffmpegthumbnailer kdenlive openshot-qt obs-studio handbrake-cli gimp krita firefox chromium-browser dconf-editor gnome-tweaks timeshift rar unrar grep gnome-system-monitor htop aria2 rsync postgresql postgresql-contrib mysql-server sqlite3 redis-server veracrypt wireshark nmap fail2ban clamav clamav-daemon steam wine wine32 kazam wallpapers-gnome-backgrounds snapd flatpak copyq okular && sudo snap install balena-etcher-electron davinci-resolve && sudo apt autoremove -y && sudo apt autoclean -y && sudo apt clean
```

---

## Quick Install Bundles

### Development Bundle
```bash
sudo apt update && sudo apt install -y git curl wget build-essential python3 python3-pip python3-venv nodejs npm docker.io docker-compose code
```

### Creative Suite Bundle
```bash
sudo apt update && sudo apt install -y gimp krita vlc audacity ffmpeg kdenlive obs-studio && sudo snap install davinci-resolve
```

### System Tools Bundle
```bash
sudo apt update && sudo apt install -y htop aria2 rsync timeshift gnome-system-monitor cpu-x okular && sudo snap install balena-etcher-electron
```

### Security Bundle
```bash
sudo apt update && sudo apt install -y openssh-server openssh-client openssl gpg keepassxc veracrypt wireshark nmap fail2ban clamav clamav-daemon
```
