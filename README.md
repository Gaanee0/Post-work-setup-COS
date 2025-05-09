# Work-setup-COS & dual boot with windows
This a my documentation of getting a work setup in cachy os.

## Pre installations
- Download the ISO from the [site](https://cachyos.org/) 
- Check the iso integrity & authenticiy with SHA256 & sig respectively [refer](https://wiki.cachyos.org/cachyos_basic/download/)
- Put iso in the Ventoy USB

## Live Installation
- Boot into it 
- Connect to wifi or LAN
- Select limine boot (supports BTRFS snapshot boot, theming)
- Usual steps (language, location (time), and keyboard)
- [Partioning the disk](https://wiki.cachyos.org/installation/installation_on_root/)
  - 2048 GB for the ESP
  - Rest of it for BTRFS wiht LUKS2
- Select no desktop environmnet gonna use minimal niri setup 

### overview 
- diselect some of the things 
  - Cachy os Browser [(depreciated)](https://www.reddit.com/r/cachyos/comments/1kg85v8/cachy_browser_is_now_deprecated/)
  - zsh-config
  - micro-settings
  - wallpapers
  - alacritty
  - btop
  - meld
  - nano-ayntax
  - vi
  - micro
  - nano
  - vim
  - openssh
  - amd ucode

## User & Passwords
- name and pass words

## Summary
Check everything is right and install it

## Post installation
- tty login
- paru
- manual snapshot -- fresh
- packages to install
  - niri sddm refind kitty neovim keyd zen-browser
- [keyd](https://github.com/rvaiya/keyd}
- refind install
- enable sddm
- manual snapshot -- before refind rice
- reboot and put refind as default boot & disable other boot managers.
- [refind theme](https://github.com/indgy/refind-bsd-black) 
- after adjusting the theme make sure it works right
- manual snaphots -- after refind rice
- [Limine boot rice](https://github.com/catppuccin/limine)
- 
