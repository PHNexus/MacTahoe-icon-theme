<!-- Core project info -->

[![License](https://img.shields.io/github/license/PHNexus/MacTahoe-icon-theme)](https://github.com/PHNexus/MacTahoe-icon-theme/blob/main/LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Linux-green?logo=linux\&logoColor=white)](https://kernel.org/)
[![Fork of vinceliuice/MacTahoe-icon-theme](https://img.shields.io/badge/fork%20of-vinceliuice%2FMacTahoe--icon--theme-blue?logo=github)](https://github.com/vinceliuice/MacTahoe-icon-theme)
[![Used by PHNexus/Hyprland-configs](https://img.shields.io/badge/used%20by-PHNexus%2FHyprland--configs-58E1FF?logo=github)](https://github.com/PHNexus/Hyprland-configs)

# <img src="logo.png" alt="Logo" width="48" height="48" align="top" /> MacTahoe Icon Theme

> **Note:** This is a fork of [vinceliuice/MacTahoe-icon-theme](https://github.com/vinceliuice/MacTahoe-icon-theme). All credit for the original design and project goes to [@vinceliuice](https://github.com/vinceliuice).

> **Used by:** [PHNexus/Hyprland-configs](https://github.com/PHNexus/Hyprland-configs) — this fork is cloned directly by the dotfiles `install.sh` to avoid the slow AUR packaging process.

A macOS Tahoe-like icon theme for Linux desktops.

## Preview

![Preview](preview.png)

![Screenshot 1](screenshot1.jpg)

![Screenshot 2](screenshot2.jpg)

## Automatic install via Hyprland-configs

If you're using the [Hyprland-configs](https://github.com/PHNexus/Hyprland-configs) dotfiles, this icon theme is installed automatically by `install.sh`.

Instead of building the icon theme through the AUR, the dotfiles installer clones this repository directly, making installation significantly faster.

## Manual Installation

The original installation script is included in this repository.

```bash
./install.sh
```

### Options

| Option                          | Description                                                                                                                      |
| ------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| `-d, --dest`                    | Specify the theme destination directory (Default: `$HOME/.local/share/icons`)                                                    |
| `-n, --name`                    | Specify the theme name (Default: `MacTahoe`)                                                                                     |
| `-t, --theme`                   | Specify theme color variant(s): `default`, `purple`, `pink`, `red`, `orange`, `yellow`, `green`, `grey`, `all` (Default: `blue`) |
| `-b, --bold`                    | Install the bold panel icons version                                                                                             |
| `-r, --remove, -u, --uninstall` | Uninstall/remove the icon theme                                                                                                  |
| `-h, --help`                    | Show the help message                                                                                                            |

For more information:

```bash
./install.sh --help
```

> **Note for Snaps:** To use these icons with Snap applications, copy the application's `.desktop` file from `/var/lib/snapd/desktop/applications/` to `$HOME/.local/share/applications/` and update the `Icon=` entry to use the desired icon.

## Bold Version

![Bold Version](bold-size.png?raw=true)

> The bold version is recommended for high-resolution displays, such as 4K displays using a 200% scale factor.

## Recommendations

This icon theme works well with:

* **GTK themes:** [MacTahoe-gtk-theme](https://github.com/vinceliuice/MacTahoe-gtk-theme)
* **Cursor themes:** [MacTahoe-cursor-theme](https://github.com/vinceliuice/MacTahoe-cursor-theme)

## Credits

All credit for the original creation and design of this icon theme goes to **vinceliuice**.

Original project:
https://github.com/vinceliuice/MacTahoe-icon-theme

Fork maintained by:
https://github.com/PHNexus/MacTahoe-icon-theme

## License

GPL-3.0 License — see [LICENSE](LICENSE).

The original project and its license belong to [@vinceliuice](https://github.com/vinceliuice).
