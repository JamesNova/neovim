# neovim
Neovim turned into IDE

# Installation
Obviously install `neovim` for your distro:
 - Arch Based Distros: `sudo pacman -S neovim`

You also need to install `wbthomason/packer.nvim`:
`git clone --depth 1 https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim`

Then run:
`git clone https://github.com/JamesNova/neovim .config/nvim`

Congrats! You've just installed neovim, next time you open `nvim` it will install the plugins needed automatically.
