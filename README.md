<!-- Core project info -->
[![License](https://img.shields.io/github/license/PHNexus/MacTahoe-icon-theme)](https://github.com/PHNexus/MacTahoe-icon-theme/blob/main/LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Linux-green?logo=linux&logoColor=white)](https://kernel.org/)
[![Fork of vinceliuice/MacTahoe-icon-theme](https://img.shields.io/badge/fork%20of-vinceliuice%2FMacTahoe--icon--theme-blue?logo=github)](https://github.com/vinceliuice/MacTahoe-icon-theme)

# <img src="logo.png" alt="Logo" width="48" height="48" align="top" /> MacTahoe Icon Theme

> **Note:** This is a fork of [vinceliuice/MacTahoe-icon-theme](https://github.com/vinceliuice/MacTahoe-icon-theme). All credit goes to [@vinceliuice](https://github.com/vinceliuice). I do not own the original project.

> **Used by:** [PHNexus/Hyprland-configs](https://github.com/PHNexus/Hyprland-configs) — this fork is cloned directly by the dotfiles `install.sh` to bypass the extremely slow AUR packaging process and install the icons instantly.

MacOS Tahoe like icon theme for Linux desktops.

## Preview

![1](preview.png)
![2](screenshot1.jpg)
![3](screenshot2.jpg)

## Automatic install via Hyprland-configs

If you're using the [Hyprland-configs](https://github.com/PHNexus/Hyprland-configs) dotfiles, this icon theme is installed automatically by the `install.sh` script. 

Instead of compiling thousands of files via AUR (which takes a long time), the script performs a fast clone (`--depth 1`) directly into your local icons directory (`~/.local/share/icons/`), making the installation virtually instant. No manual steps needed.

## Manual Installation

Usage:  `./install.sh`  **[OPTIONS...]**

|  OPTIONS:           | |
|:--------------------|:-------------|
|-d, --dest           | Specify theme destination directory (Default: $HOME/.local/share/icons)|
|-n, --name           | Specify theme name (Default: MacTahoe)|
|-t, --theme          | Specify theme color variant(s) [default/purple/pink/red/orange/yellow/green/grey/all] (Default: blue)|
|-b, --bold           | Install bold panel icons version|
|-r,--remove,-u,--uninstall | Uninstall (remove) icon themes|
|-h, --help           | Show this help|

> **Note for snaps:** To use these icons with snaps, the best way is to make a copy of the application's .desktop located in `/var/lib/snapd/desktop/applications/name-of-the-snap-application.desktop` into `$HOME/.local/share/applications/`. Then use any text editor and change the "Icon=" to "Icon=name-of-the-icon.svg"

> For more information, run: `./install.sh --help`

### Bold Version

![bold](bold-size.png?raw=true)

> The bold version is recommended for use with a `High resolution display` like a 4k display with a 200% scale factor!

## Recommendations

This icon theme works well with:

- **GTK themes:** [MacTahoe-gtk-theme](https://github.com/vinceliuice/MacTahoe-gtk-theme)
- **Cursor themes:** [MacTahoe-cursor-theme](https://github.com/vinceliuice/MacTahoe-icon-theme/tree/main/cursors)

## Credits & Donate

All credit for the creation and design of these icons goes to **vinceliuice**. 

If you like the original project, please consider supporting the creator:
<span class="paypal"><a href="https://www.paypal.me/vinceliuice" title="Donate to this project using Paypal"><img src="https://www.paypalobjects.com/webstatic/mktg/Logo/pp-logo-100px.png" alt="PayPal donate button" /></a></span>

## License

GPL-3.0 License — see [LICENSE](LICENSE). Original license belongs to [@vinceliuice](https://github.com/vinceliuice).
