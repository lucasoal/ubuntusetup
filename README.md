# Ubuntu Pkgs + Shell Setup

> [!WARNING]
> Ubuntu 24.04 (Noble Numbat)

<div align="center">
  <img src="assets/lockscreen.png" width="49%"> <img src="assets/login.png" width="49%"> <br>
  <img src="assets/workspaces.png" width="49%"> <img src="assets/apps.png" width="49%"> <br>
  <img src="assets/desktop.png" width="49%">
</div>

<hr>

## 1. autoinstall.yaml

> [!IMPORTANT]
> Use [autoinstall.yaml](autoinstall.yaml) during the instalation.
> ```
> https://raw.githubusercontent.com/lucasoal/ubntsetup/refs/heads/main/autoinstall.yaml
> ```
> <div align="center"><img src="assets/autoinstall.png" width="50%"> <br> </div>

| ⚙️ **System Settings** | |
|-|-|
| Region & Language | `en_US.UTF-8`       |
| Time/Zone         | `America/Sao_Paulo` |
| ⌨️ **Keyboard**                         |
| Layout            | `br`                |
| Variant           | `abnt2`             |
| 👤 **User**                             |
| Real Name         | `Username`          |
| Username          | `user`              |
| Password          | `123`               |
| Hostname          | `computer`          |


| 📦 **Packages/Softwares** | |
|-|-|
| APT | `build-essential`, `ca-certificates`, `curl`, `dash`, `flameshot`, `git`, `git-lfs`, `gnome-clocks`, `gnome-shell-extension-manager`, `gnome-shell-extensions`, `gnome-tweaks`, `gnome-weather`, `htop`, `kdenlive`, `make`, `nodejs`, `python3-pip`, `python3-venv`, `remmina`, `snapd`, `software-properties-common`, `tilix`, `tree`, `unzip`, `vim`, `wget`, `whois`, `zsh` |
| Snap | `brave`, `dbeaver-ce`, `discord`, `postman` |

### ⚜️ Install

**Direct install (recommended)**

```sh
# using cURL
curl -fsSL https://raw.githubusercontent.com/lucasoal/ubntsetup/main/install | sudo bash
```

```sh
# using Wget
wget -qO- https://raw.githubusercontent.com/lucasoal/ubntsetup/main/install | sudo bash
```

**Manual installation**
```sh
git clone https://github.com/lucasoal/ubntsetup.git
cd ubntsetup 
chmod +x install
sudo ./install
```

> [!IMPORTANT]
> Use [install](./install) after install the OS.

| 📦 **Packages/Softwares** | |
|-|-|
| DEB | `Google Chrome`, `VS Code`               |
| PPA Deadsnakes | Python `3.10`, `3.12`, `3.14` |
| VPN | `Cloudflare WARP (1.1.1.1)`              |
| 🗑️ **Remove** |                                |
| Games & related pkgs | `gnome-games`, `sauerbraten`, `supertux`, `steam`... |

| 👁️ Visual | |
|-|-|
| 🖥️ **Terminal**                         |                       
| Shell             | ZSH (Oh My ZSH)     |
| Theme             | bira                |

| 🔤 **Fonts**                            ||
|-|-|
| Interface         | Google Sans 12      |
| Documents         | Google Sans 11      |
| Monospace         | Google Sans Code 12 |

| 🌄 **Background**                       ||
|-|-|
| Catalina          | https://wallpapercave.com/wp/wp10824773.jpg |

| 🧩 **Extensions** | |
|-|-|
| Gnome | [Alphabetical App Grid](https://extensions.gnome.org/extension/4269/alphabetical-app-grid), [Blur my Shell](https://extensions.gnome.org/extension/3193/blur-my-shell), [Dash to Dock](https://extensions.gnome.org/extension/307/dash-to-dock), [Tactile](https://extensions.gnome.org/extension/4548/tactile), [Desktop Icons NG (DING)](https://extensions.gnome.org/extension/2087/desktop-icons-ng-ding), [Ubuntu AppIndicators](https://extensions.gnome.org/extension/1301/ubuntu-appindicators), [Ubuntu Tiling ](https://extensions.gnome.org/extension/3733/tiling-assistant)


| ⌨️ Keyboard Shortcuts | | |
|-|-|-|
| Flameshot PrtSc    | `flameshot gui`       | `Super` + `PrtSc`              |
| Home Folder        | `nautilus $HOME`      | `Super` + `E`                  |
| Cloudflare VPN On  | `warp-cli connect`    | `Ctrl` + `Alt` + `V`           |
| Cloudflare VPN Off | `warp-cli disconnect` | `Ctrl` + `Alt` + `Shift` + `V` |