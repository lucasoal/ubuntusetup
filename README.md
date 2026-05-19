<div align="center">
  <h1>Ubuntu + Env Setup</h1>
  <a href="https://github.com/lucasoal/ubntsetup/archive/refs/heads/main.zip">📁 • Download ZIP</a>
  <br> <br>
</div>

> [!WARNING]
> Ubuntu 24.04 (Noble Numbat)

The script automates the installation and configuration of a full development workstation</i>

<div align="center">
  <img src="assets/lockscreen.png" width="49%"> <img src="assets/login.png" width="49%"> <br>
  <img src="assets/workspaces.png" width="49%"> <img src="assets/apps.png" width="49%"> <br>
  <img src="assets/desktop.png" width="49%">
</div>

<hr>

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

<div align="center">⏺ ⏺ ⏺</div>

### 📦 Packages / Softwares

> [!IMPORTANT]
> Use [autoinstall.yaml](autoinstall.yaml) during the instalation.
>   ```
>   https://raw.githubusercontent.com/lucasoal/ubntsetup/refs/heads/main/autoinstall.yaml
>   ```
>
> <img src="assets/autoinstall.png" width="40%"> <br>

- **APT**
  - `build-essential` | `curl` | `flameshot` | `git` | `gnome-clocks` | `gnome-shell-extension-manager` | `gnome-tweaks` | `gnome-weather` | `htop` | `jq` | `make` | `nodejs` | `python3-pip` | `python3-venv` | `remmina` | `software-properties-common` | `tar` | `tree` | `unzip` | `vim` | `wget` | `zip` | `zsh`
- **Snap**
  - `brave` | `dbeaver-ce` | `discord` | `postman` | `pyenv` 
- **DEB**
  - `Google Chrome` | `VS Code`
- **PPA Deadsnakes**
  - Python `3.10` | `3.12` | `3.14`
- **VPN**
  - Cloudflare WARP (1.1.1.1)

#### 🗑️ Remove

- Games and related packages (`gnome-games`, `sauerbraten`, `supertux`, `steam`...)

<div align="center">⏺ ⏺ ⏺</div>

### 🐚 Shell

> [!IMPORTANT]
> Use [install](./install) after install the OS.

- **Terminal**
  - Oh My ZSH
    - Theme · "bira"
- **Fonts**
  - Interface · Helvetica 12
  - Documents · Helvetica 11
  - Monospace · Monospace 12
- **Background**
  - Catalina 

<div align="center">⏺ ⏺ ⏺</div>

### ⌨️ Keyboard Shortcuts

- **Flameshot PrtSc**
  - `flameshot gui`
  - `Super` + `PrtSc`
- **Home Folder**
  - `nautilus $HOME`
  - `Super` + `E`
- **Cloudflare VPN On**
  - `warp-cli connect`
  - `Ctrl` + `Alt` + `V`
- **Cloudflare VPN Off**
  - `warp-cli disconnect`
  - `Ctrl` + `Alt` + `Shift` + `V`