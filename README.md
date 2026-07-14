# tmenu-patches
My personal custom patches for tinyopsec's [tmenu](https://github.com/tinyopsec/tmenu).  

List of patches:
- Border: Adds a border around tmenu. (from https://tools.suckless.org/dmenu/patches/border/)
- Desktoponly: Adds an option to load *.desktop files. (from https://tools.suckless.org/dmenu/patches/desktoponly/)
- Gruvbox: Gruxbox theme (from https://tools.suckless.org/dmenu/patches/gruvbox/)
- Solarized Dark: Solarized Dark theme (from https://tools.suckless.org/dmenu/patches/solarized/)

## Use

Instructions: 
```
git clone https://github.com/tinyopsec/tmenu.git
cd tmenu
git apply --check PATCH.patch
make
sudo make install
```

This repository is not endorsed by tinyopsec.  Use at your own risk.

MIT License
