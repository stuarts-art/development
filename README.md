## Install Basics:

- Initial Updates and Upgrades
  - `apt-get update`
  - `apt-get upgrade` (NOTE use `apt-get dist-upgrade` for proxmox root)
  - `apt update`
  - `apt install build-essential` (Installs c compiler and other build tools)
- Installing Neovim
  - Go to file `/etc/apt/sources.list.d/debian.sources`
  - Add testing to the suites line: `Suites: trixie trixie-updates testing`
  - `apt-get update`
  - install neovim `apt-get install -t testing neovim`
- Installing [LazyVim](https://www.lazyvim.org/installation)
  - `git clone https://github.com/LazyVim/starter ~/.config/nvim`
  - ```rm -rf ~/.config/nvim/.git
  - `rm -rf ~/.config/nvim/.git`
- Installing zsh and ohmyzsh
  - `apt install zsh zplug`
  - `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)`
