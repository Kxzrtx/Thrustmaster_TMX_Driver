<div align="center">

# 🎮 Thrustmaster TMX Linux Driver Installer

[![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)](https://www.gnu.org/software/bash/)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://kernel.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

A simple installer script to get your **Thrustmaster TMX** wheel working on Linux with full Force Feedback support.

</div>

---

## 📦 What it installs

- [T150 Driver](https://github.com/scarburato/t150_driver) — kernel module for Thrustmaster wheels
- [TMDRV](https://github.com/her001/tmdrv) — userspace driver daemon
- [Oversteer](https://flathub.org/en/apps/io.github.berarma.Oversteer) — GUI for wheel configuration

> **Note:** I am **not** the author of T150 Driver, TMDRV or Oversteer. This script is provided as-is to simplify installation. Use at your own risk.

---

## ✅ Supported distros

![Arch Linux](https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white)
![CachyOS](https://img.shields.io/badge/CachyOS-00BFFF?style=for-the-badge&logo=arch-linux&logoColor=white)
![Manjaro](https://img.shields.io/badge/Manjaro-35BF5C?style=for-the-badge&logo=manjaro&logoColor=white)
![Fedora](https://img.shields.io/badge/Fedora-51A2DA?style=for-the-badge&logo=fedora&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Linux Mint](https://img.shields.io/badge/Linux_Mint-87CF3E?style=for-the-badge&logo=linux-mint&logoColor=white)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white)
![openSUSE](https://img.shields.io/badge/openSUSE-73BA25?style=for-the-badge&logo=opensuse&logoColor=white)

> Automatically detects and installs appropriate kernel headers (e.g. `linux-zen-headers` for the Zen kernel).

---

## 🚀 Installation

**1. Clone the repository**
```bash
git clone https://github.com/Kxzrtx/Thrustmaster_TMX_Driver
cd Thrustmaster_TMX_Driver
```

**2. Run the installer**
```bash
sudo bash ./install.sh
```

> ⚠️ Always use `sudo bash ./install.sh` — running `sudo ./install.sh` directly will fail because sudo excludes the current directory from PATH for security reasons.

**3. Follow the on-screen instructions**

**4. Restart your computer or reconnect the wheel**

Full Force Feedback should work automatically after restart.

---

## 🗑️ Uninstallation

```bash
sudo bash ./install.sh uninstall
```
- It uninstalls the drivers, disables system service and deletes every file related to those drivers.
---

## 🔧 Troubleshooting

**Permission denied error?**
```bash
chmod +x install.sh
sudo bash ./install.sh
```
- Make sure to be in the folder in which the script is installed!
---

## 📬 Contact

If you encounter any issues, feel free to reach out:

[![Email](https://img.shields.io/badge/Email-jakubjaki55@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jakubjaki55@gmail.com)
[![Discord](https://img.shields.io/badge/Discord-kxzrt123-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/)
