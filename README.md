# alter-system-menu
bash-based system configration scripts for Alter Linux i3wm edition

---

## What's this
This is CUI system configration script written by bash.  
This script can do:
- **Display setting** (ARandr)
- **Network setting** (Network Manager)
- **Sound   setting** (pavuControl)
- **Pacages management** (pacman)
	- Update all packages
	- Search packages
	- Install packages
	- Remove packages
- **Time    setting**
	- Change Time zone
	- Sync network time
	- Write hardware clock
	- change ntp


## how to use
clone this repository, and run `./alter-system-menu`

## require packages
- arandr
- networkmanager
- pavucontrol
- ntpdate
- htop

`yay -S arandr networkmanager pavucontrol ntpdate htop`
