Game Boy Metallics Overlays
by mugwomp93

These overlays use colored grids to tweak the appearances of the internal Gambatte Game Boy palettes.

These overlays were optimized on the original RG35XX as it doesn't have any other means of adjusting the image color, contrast, etc. The final versions were a compromise of color, grid line visibility, and contrast within the constraints of the existing internal palettes (e.g., so changing the overlay opacity affects also affects the color and contrast). As a result, I created optional custom overlays to help improve the contrast and in some cases (DMG, GBL) further refine the color schemes. Overlay alignment was tested on the RG35XX, RG35XX Plus, and Miyoo Mini Plus, and in all cases was correct.

Note that the DMG and GBP are dark overlays, and you'll need to increase your screen brightness to (near) maximum for them to appear correctly.

Thanks to 1playerinsertcoin for testing the alignment on the MM+ and their suggestions for improving the overlays!

-------------------------------------

Retroarch Settings:

	- Settings > Video > Scaling:

		Integer Scale: ON

		Integer Scale Overscale (if present): OFF

		Aspect Ratio: ON or Core provided



*****TO USE THE INTERNAL PALETTES*****

	- Quick Menu > Core Options

		GB Colorization: Internal

		Internal Palette (Overlay Type -> Palette): 

			DMG -> GB - DMG

			GB Pocket -> GB - Pocket

			GB Light -> GB - Light

			VB / PixelShift 44 -> PixelShift - Pack 1 
				AND PixelShift - Pack 1 -> PixelShift 44 - Virtual Boy*

		Color Correction: OFF

	*For Garlic OS and muOS, this is the 2nd palette before GB - DMG if cycling through with L2 and R2



*****TO USE THE CUSTOM PALETTES*****

	- Copy the palettes folder (containing default.pal) for the Game Boy color scheme you wish to use to your BIOS folder (or copy the palettes folder from GBM_Custom_Palettes.zip)

		- If you're using 2 SD cards, this may be on SD1 or SD2 depending on your CFW:

			- For Garlic OS, copy it to the BIOS folder on SD2

			- For muOS, copy it to the BIOS folder on SD1 (/mnt/mmc/MUOS/bios/)

		- If you're using GBM_Custom_Palettes.zip, the included default.pal file is for the DMG color scheme
	
			- If you wish to use a different color scheme, make a copy of the palette file for the scheme you want to use and rename it/overwrite default.pal

Note that there's no option to specify which custom palette to use in Retroarch (i.e., it only uses default.pal), so you can only use one custom palette at a time.** Copying additional palettes folder(s) to your BIOS folder will overwrite the previous default.pal file.



Retroarch Settings:		

	- Quick Menu > Core Options

		GB Colorization: Custom

		Color Correction: OFF



-------------------------------------

**There is a workaround for this:

CAUTION: THIS PROCESS USES DINGUX COMMANDER, WHICH ALLOWS YOU TO MOVE, MODIFY, AND DELETE FILES ON YOUR SD CARD. IT HAS THE POTENTIAL TO SERIOUSLY MESS UP AND/OR ERASE YOUR FILES IF YOU DON'T KNOW WHAT YOU'RE DOING. FOLLOW THESE INSTRUCTIONS AT YOUR OWN RISK.

To get access to all of the custom palettes on your device, rename the various palette files (e.g., DMG.pal, GBP.pal, GBL.pal, etc) prior to copying them all to the palettes folder. Make sure to also include a copy named default.pal for whichever palette you wish to use first. Then, whenever you want to switch palettes, use Dingux Commander to make a copy of the new palette and rename it to default.pal (you'll need to either overwrite the previous default.pal or delete it prior to this).

For example, if you've used my naming scheme and you want to switch to GBP.pal:

	- Open Dingux Commander (for muOS, press A again after opening - it's not really frozen)

	- In the left directory, navigate to the palettes folder

	- Select GBP.pal and press X

		- Copy GBP.pal to the right directory

	- Select the copy of GBP.pal in the right directory and press X

		- Rename to default.pal

	- Press X again

		- Move default.pal to the left directory

		- A prompt indicating that the file already exists will pop up if default.pal is already present

			- Select YES to overwrite

	- Press Y and select Quit to exit Dingux Commander

Dingux Commander is included in the applications section of muOS and can be downloaded for Garlic OS from RG35XX.com (https://www.rg35xx.com/en/apps/apps-for-garlicos/).
