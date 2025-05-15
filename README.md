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
  - nano-syntax
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
- manual snapshot -- fresh install
- packages to install
  - niri sddm refind kitty neovim keyd zen-browser kdeconnect rofi-wayland wl-clipboard xwayland-satellite xdg-desktop-portal-gtk gnome-keyring nautilus dolphin xdg-desktop-portal-gnome ttf-atkinson-hyperlegible ttf-jetbrains-mono-nerd ttf-jetbrains-mono sshfs asusctl tuned-ppd
- sudo asusctl -c 80
- sudo sytemctl enable --now tuned-ppd
- sudo tuned-adm profile powersave
- niri change the kitty,
- sudo sytemctl enable --now sddm
- [nvim rice](https://nvchad.com/docs/quickstart/install/)
- [keyd](https://github.com/rvaiya/keyd)
- refind install
- manual snapshot -- bare 
- reboot and put refind as default boot & disable other boot managers.
- Initial login
  - kde connect
  - zen-browser sync
  - github
  - chatgpt
  - deepseek
  - gemini
  - gork
- [refind theme](https://github.com/catppuccin/refind) --mocha
- after adjusting the theme make sure it works right
- manual snaphots -- after refind rice
- [Limine boot rice](https://github.com/catppuccin/limine) --mocha
- Check limine boot is working
- manual snapshot -- after limine rice
- [sddm rice](https://github.com/stepanzubkov/where-is-my-sddm-theme)
- Check the condition
- manual snapshot -- after sddm rice
- [niri](https://github.com/YaLTeR/niri) work space rice
  - follow the config [Cat](https://github.com/sansroot/hypr-dots/tree/sapphire)
  - make sure everything works
    - waybar
    - logout
    - Shutdown
    - idleinhibitor
    - change animation
    - lock when suspension
    - lock
    - wallpaper
    - swaylock wallpaper
    - x11 apps
    - niri kwybinds edit (over haul)
    - clipboard
    - make 60fps default
    - notification daemon
    - set battery red n the after 20
    - notification float in a windows left side down "windows rule match app-id"
    - set the downloading screen be in the middle
    - bluetooth daemon
    - brightness daemon
    - sound daemon
    - btrfs asistant
    - snapper
    - niri important apps
    - prettyfy everything
    - make cursor work
    - make tokyo dark the nautillus
    - zen rice
    - kitty raise
    - obsidian rice
  - [niri config by color](https://github.com/color00/arch-niri-public), [niri wiki](https://github.com/YaLTeR/niri/wiki/Getting-Started) for ref
- manual snapshot -- after niri rice
- update error
- Cachy post installation && mkinitcpio firmware && [sabi](https://github.com/sabi-31/My_Perfect_Arch-linux) skim throug it for post install
- reboot
- manual snapshot --post cachy opti
- bit-warden ente-auth-bin filen-desktop better-bird obsidian okular brave-bin spotify-adblock anki zapzap telegram-desktop electron-mail arch-audit-gtk vlc gwenview  ente-desktop-bin 
  - login ssh obsidian
  - login reddit, proton calendar youtube
  - ublock and leechcode
  - zen browser essential space
  - change search
  - setup brave
- manula snapshot -- all done But wooz
- [hyprpicker](https://github.com/hyprwm/hyprpicker) for zooming
- put the configs in the filen
  - .config
  - limineconig
  - refind config
  - sddm config
  -  
- manual snapshot
- download all the books
- put all the books in the filen

