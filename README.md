# 4:3 vertical game overlays for Retropie 4.x - Retroarch/Libretro 
Vertical arcade game overlays created for Lr-Mame2003 and Lr-FBA, with correct aspect ratio and 4:3 displays (1600x1200 and 1024x768).

Original logos, artwork, graphics and trademarks are property of their respective owners. 

Be sure to also check out our sibling project aimed to add [pause screens for arcade games](https://github.com/svera/arcade-pause-overlays).

## How to install

The `.cfg` files in `cfgs` assume retroarch overlay folder is: `/opt/retropie/emulators/retroarch/overlays/arcade-bezels/`. If folder does not exist on your RetroPie, create it. If using a different folder, edit `.cfg` files accordingly.

Summarizing the steps:
* SSH or FTP into Pi
* Copy `cfgs/romname.cfg` into your `configs/all/retroarch/config/MAME 2003` (lr-mame2003) or `configs/all/retroarch/config/FB Alpha` (lr-fba) folder
* Copy PNG file and `bezel-cfgs/romname.cfg` into overlay folder. There is also a `generic.png` bezel for games without a dedicated one.

## Credits

Thanks to AndrewH, UDb23 and Mayki from Retropie forums for their awesome work.
