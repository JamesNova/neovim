# neovim
Neovim turned into IDE

# Installation
Obviously install `neovim` for your distro:
> Arch Based Distros:
```shell
sudo pacman -S neovim
```
> Debian Based Distros:
```shell
sudo apt-get install neovim
```

You also need to install `wbthomason/packer.nvim`:
```shell
git clone --depth 1 https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim
```

Then clone my config:
```shell
git clone https://github.com/JamesNova/neovim .config/nvim
```

Congrats! You've just installed neovim, next time you open `nvim` it will install the plugins needed automatically.
