# Ubuntu Software Installation Commands (with sudo -y)

## System Update (Do First)
```bash
sudo apt update && sudo apt upgrade -y
```

---

## Development & Programming

```bash
sudo apt install -y git
sudo apt install -y curl
sudo apt install -y wget
sudo apt install -y build-essential
sudo apt install -y make
sudo apt install -y python3
sudo apt install -y python3-pip
sudo apt install -y python3-venv
sudo apt install -y nodejs
sudo apt install -y npm
sudo apt install -y docker.io
sudo apt install -y docker-compose
sudo apt install -y git-flow
```

---

## Text Editors & IDEs
```bash
sudo apt install -y code
sudo apt install -y mousepad
sudo apt install -y sublime-text
```

---

## Office & Productivity
```bash
sudo apt install -y libreoffice
```

---

## Multimedia (Audio, Video, Image Editing)
```bash
sudo apt install -y vlc
sudo apt install -y audacity
sudo apt install -y ffmpeg
sudo apt install -y ffmpegthumbnailer
sudo apt install -y imagemagick
sudo apt install -y gimp
sudo apt install -y kdenlive
sudo apt install -y shotcut
sudo apt install -y openshot-qt
sudo apt install -y krita
sudo apt install -y blender
sudo apt install -y obs-studio
sudo apt install -y handbrake-cli
sudo apt install -y sox
sudo apt install -y mpg123
sudo apt install -y flac
sudo apt install -y libav-tools
```

---

## Graphic Design & Image Editing
```bash
sudo apt install -y gimp
```

---

## Internet & Communication
```bash
sudo apt install -y firefox
sudo apt install -y chromium-browser
sudo apt install -y google-chrome-stable
sudo apt install -y openssh-client
sudo apt install -y openssh-server
sudo apt install curl; sudo curl -fsSLo /usr/share/keyrings/brave-browser-nightly-archive-keyring.gpg https://brave-browser-apt-nightly.s3.brave.com/brave-browser-nightly-archive-keyring.gpg; sudo curl -fsSLo /etc/apt/sources.list.d/brave-browser-nightly.sources https://brave-browser-apt-nightly.s3.brave.com/brave-browser.sources; sudo apt update; sudo apt install brave-origin-nightly
curl -fsSL https://github.com/zen-browser/updates-server/raw/refs/heads/main/install.sh | $SHELL


```

---

## System Utilities
```bash
sudo apt install -y htop
sudo apt install -y btop
sudo apt install -y neofetch
sudo apt install -y tree
sudo apt install -y ranger
sudo apt install -y midnight-commander
sudo apt install -y gparted
sudo apt install -y baobab
sudo apt install -y dconf-editor
sudo apt install -y gnome-tweaks
sudo apt install -y stacer
sudo apt install -y bleachbit
sudo apt install -y timeshift
sudo apt install -y unzip
sudo apt install -y zip
sudo apt install -y p7zip-full
sudo apt install -y rar
sudo apt install -y unrar
sudo apt install -y rsync
sudo apt install -y grep
sudo apt install -y sed
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
sudo apt install -y qemu-kvm
sudo apt install -y libvirt-daemon-system
sudo apt install -y virt-manager
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

## Terminal & Shell
```bash
sudo apt install -y terminator
sudo apt install -y tilix
sudo apt install -y guake
sudo apt install -y zsh
sudo apt install -y tmux
sudo apt install -y screen
sudo apt install -y byobu
```

---

## Gaming
```bash
sudo apt install -y steam
sudo apt install -y lutris
sudo apt install -y wine
sudo apt install -y wine32
sudo apt install -y playonlinux
sudo apt install -y protontricks
```

---

## Cloud & Sync
```bash
sudo apt install -y nextcloud-client
sudo apt install -y syncthing
sudo apt install -y rclone
```

---

## Document & PDF Tools
```bash
sudo apt install -y okular
sudo apt install -y evince
sudo apt install -y pdftk
sudo apt install -y ghostscript
sudo apt install -y qpdf
```

---

## Screen Recording & Streaming
```bash
sudo apt install -y obs-studio
sudo apt install -y simplescreenrecorder
sudo apt install -y kazam
sudo apt install -y recordmydesktop
```

---

## Desktop Enhancements
```bash
sudo apt install -y conky
sudo apt install -y albert
sudo apt install -y ulauncher
sudo apt install -y variety
sudo apt install -y wallpapers-gnome-backgrounds
sudo apt install -y papirus-icon-theme
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
