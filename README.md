# OldSNES: SNES VC for Old 3DS users

WHAT'S DIFFERENT FROM THE ORIGINAL?
- Updated to snes9x_3ds v1.30 by moosan82.
- Updated to use Qyriad's banner creating procedure.
- Removed support for blargSNES.


PRE-INSTRUCTIONS (INSTALLING SNES9X):
- Download snes9x_3ds from: https://github.com/bubble2k16/snes9x_3ds/releases
- Follow the instructions on: https://github.com/bubble2k16/snes9x_3ds/blob/master/readme.md


INSTRUCTIONS:
- Create a folder for each game on the input folder (Earthbound, for example).
- Put your SNES rom on this folder.
- Put an icon image on this folder and rename it icon.png or icon.jpg. This can be whatever image you want for the home menu icon (a screenshot, for example).
- Run make_snes9x.bat.
- Type in the game's title, description (optional), publisher, product code (SNS-MW-USA, for example), and unique id (whatever you want from 00000 to fffff).
- Install the generated CIA file. (it's in OldSNES/cia/ folder)
- Enjoy.

Note: If you don't provide an icon image, banner.png/banner.jpg will be used for the icon instead.


CUSTOM BANNER (OPTIONAL):
- Download "Ultimate SNES Forwarder Maker for 3DS" from https://gbatemp.net/threads/release-ultimate-snes-forwarder-maker-for-3ds.460895/
- Run "Ultimate SNES Forwarder Maker for 3DS.exe"
- Open your rom file (.sfc or .smc)
- Enter Long name, Short name & Game publisher then click "Load icon image" and choose an image. (This can be whatever image you want for the home menu icon)
- Click on "Export icon.bin" button on the bottom then set the export location to OldSNES/input/"GameName" and name set the name as "icon".
- Click on "Next step (3d banner)" to advance to next part.
- Click on "Load inner image" and choose an image (a box art or cartridge label image of the game) then choose a style. 
- Enter banner text (1) and (2) accordingly to your game. Font used is not the same as the original vc titles so we're going to adjust that. Go to "OldSNES/input/" you'll see "SCE-PS3-RD-R-LATIN.TTF" click on it to install the font. Then go back to the app and click on "Select font (1) & (2)" and change font used to what you installed just now.
- Once you're all done, click on "Export banner.bin" button on the bottom then set the export location to OldSNES/input/"GameName" and name set the name as "banner".
- You can close the program now, we just used this program to create the banners for our vc.


UPDATING EXISTING CIAS:
- Put all of yours cias inside the cia folder (keep a backup of them just in case something goes wrong).
- Run update_snes9x.bat.
- OPTIONAL: If you want to add or replace files, put them into the folder you created for the game, then confirm when prompted to "include or update any extra files".
- OPTIONAL: If you want to delete existing files, go to the romfs folder and delete whichever file(s) you want. DO NOT DELETE ROM.SMC.


Credits:
- StapleButter and DiscostewSM for blargSNES.
- bubble2k16 for Snes9x 3DS.
- Asia81 for the SNES VC banner template.
- Qyriad for banner creation bat
- moosan82 for snes9x 1.30 update
