# pfc-firmware
This repository contains official Wago firmware releases for 750-8xxx(PFC) series.

<div style="text-align: left" >
<img src="images/pfcs.png"
     alt="install docker" width="500"/>
</div>

# How to install:
WAGO recommends exclusive use of original WAGO SD cards, as the new firmware has been tested and released based on these cards. If using cards other than WAGO, WAGO cannot guarantee and take responsibility for proper functioning of the controller/coupler.

## Installation

1. Delete full content of the card with the tool "Active@KillDisk" - to download click here: http://www.killdisk.com/downloads/KillDisk-Freeware-Setup.exe
2. Write <a href="https://github.com/WAGO/pfc-firmware/releases" title="image">image</a> on the WAGO SD card with "Win32DiskImager" - to download click here: https://sourceforge.net/projects/win32diskimager/
3. Plug-in the WAGO SD card first before booting the PFC100/200.
4. Adjust the static IP address with "Wago Ethernet Settings".
5. Due to changes in the WebBasedManagement (WBM), make sure to delete the full browser cache (!) and restart the browser after.
6. Open "WebBasedManagement / Administrations – Menue / Create Image // Create bootable image from active partition (SD) // Start Copy".
7. WAGO Ethernet settings is at least required in version 6.8.2.2. To download this version, click following link: https://wago.sharefile.eu/d-s6d218ea736c4918a
