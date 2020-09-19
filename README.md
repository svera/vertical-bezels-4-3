# 4:3 vertical game overlays for Retropie 4.x - Retroarch/Libretro 
Vertical arcade game overlays created for Lr-Mame2003 and Lr-FBA, with correct aspect ratio and 4:3 displays (1600x1200 and 1024x768).

Original logos, artwork, graphics and trademarks are property of their respective owners. 

## How to install

The `.cfg` files in `cfgs` assume retroarch overlay folder is: `/opt/retropie/emulators/retroarch/overlays/arcade-bezels/`. If folder does not exist on your RetroPie, create it. If using a different folder, edit `.cfg` files accordingly.

Summarizing the steps:
* SSH or FTP into Pi
* Copy `cfgs/romname.cfg` into your `configs/all/retroarch/config/MAME 2003` (lr-mame2003) or `configs/all/retroarch/config/FB Alpha` (lr-fba) folder
* Copy PNG file and `bezel-cfgs/romname.cfg` into overlay folder. There is also a `generic.png` bezel for games without a dedicated one.

## Credits

Thanks to AndrewH, UDb23 and Mayki from Retropie forums for their awesome work.

--------------
MDLAV8R Notes:
--------------

Added:

- Tron
- Championship Bowling
- Tempest
- PacMan Plus

Target GitHub Folders - I have a total of 5 minutes of GitHub knowledge and 1 day of retroarch folder knowledge so this section is for my sanity (terms may be incorrect):

Image files (.png) go in 1024 or 1600 folder depending on resolution.  

"Overlay config" files (.cfg) ==> bezel.cfgs folder.  
These are the .cfg files that sit in the retroarch OVERLAY folder (the same arcade-bezels folder as the .png files on your emulator).

"Config config" files (.cfg) ==> cfgs folder.  
These are the .cfg files that sit in the retrorach CONFIGS folder (files are stripped down to remove everything but overlay info).

Big thanks to svera for giving 4:3 bezels a home!!!
