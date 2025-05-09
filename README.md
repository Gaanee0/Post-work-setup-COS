# Post-work-setup-COS
This a my documentation of getting a work setup in cachy os.

## Pre installations
- Download the ISO from the [site](https://cachyos.org/) 
- Check the iso integrity & authenticiy with SHA256 & sig respectively [refer](https://wiki.cachyos.org/cachyos_basic/download/)
- Put iso in the Ventoy USB

## Live Installation
- Boot into it 
- Connect to wifi
select limine boot (supports BTRFS snapshot boot, theming)
Usual steps (language, keyboard and time)
[Partioning the disk](https://wiki.cachyos.org/installation/installation_on_root/)
  2048 GB for the ESP
  Rest of it for BTRFS wiht LUKS2
Select no desktop environmnet gonna use minimal niri setup 

### overview 
diselect some of the things 
  Cachy os Browser [(depreciated)](https://www.reddit.com/r/cachyos/comments/1kg85v8/cachy_browser_is_now_deprecated/)
  zsh-config
  micro-settings
  
  
