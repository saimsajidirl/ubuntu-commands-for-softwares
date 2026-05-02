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
# Node Js
sudo apt install -y nodejs
# Npm
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
# Libre Office
sudo apt install -y libreoffice
```

---

## Multimedia (Audio, Video, Image Editing)
```bash
# VLC
sudo apt install -y vlc
# Audacity
sudo apt install -y audacity
# FFmpeg
sudo apt install -y ffmpeg
# FFmpeg Thumbnailer
sudo apt install -y ffmpegthumbnailer
# Kdenllive
sudo apt install -y kdenlive
# OpenShot
sudo apt install -y openshot-qt
# Obs Studio
sudo apt install -y obs-studio
# Hand brake
sudo apt install -y handbrake-cli
```

---

## Internet & Communication
```bash
# Firefox
sudo apt install -y firefox
# Chromium
sudo apt install -y chromium-browser
# Chrome
sudo apt install -y google-chrome-stable
# Brave Nightly
sudo apt install curl; sudo curl -fsSLo /usr/share/keyrings/brave-browser-nightly-archive-keyring.gpg https://brave-browser-apt-nightly.s3.brave.com/brave-browser-nightly-archive-keyring.gpg; sudo curl -fsSLo /etc/apt/sources.list.d/brave-browser-nightly.sources https://brave-browser-apt-nightly.s3.brave.com/brave-browser.sources; sudo apt update; sudo apt install brave-origin-nightly
# Zen Browser
curl -fsSL https://github.com/zen-browser/updates-server/raw/refs/heads/main/install.sh | $SHELL


```

---

## System Utilities
```bash
sudo apt install -y dconf-editor
sudo apt install -y gnome-tweaks
sudo apt install -y timeshift
sudo apt install -y rar
sudo apt install -y unrar
sudo apt install -y grep
```

---

## Database Tools
```bash
sudo apt install -y postgresql
sudo apt install -y postgresql-contrib
sudo apt install -y mysql-server
sudo apt install -y sqlite3
sudo apt install -y mongodb
sudo apt install -y redis-server
sudo apt install -y dbeaver-ce
sudo apt install -y pgadmin4
```

---

## Virtualization
```bash
sudo apt install -y virtualbox
sudo apt install -y libvirt-daemon-system
```

---

## Security & Privacy
```bash
sudo apt install -y openssh-server
sudo apt install -y openssh-client
sudo apt install -y openssl
sudo apt install -y gpg
sudo apt install -y keepassxc
sudo apt install -y veracrypt
sudo apt install -y wireshark
sudo apt install -y nmap
sudo apt install -y fail2ban
```

---

## Gaming
```bash
sudo apt install -y steam
sudo apt install -y wine
sudo apt install -y wine32
```

---

## Screen Recording & Streaming
```bash
sudo apt install -y kazam
```

---

## Desktop Enhancements
```bash
sudo apt install -y wallpapers-gnome-backgrounds
```

---

## Package Managers
```bash
sudo apt install -y snapd
sudo apt install -y flatpak
```

---

## Clipboard Manager (Win+V equivalent)
```bash
sudo apt install -y copyq
```

---

## System Cleanup
```bash
sudo apt autoremove -y
sudo apt autoclean -y
sudo apt clean
```

---
