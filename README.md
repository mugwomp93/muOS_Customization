# Contents
1. [Perfect Overlays for RG35XX Plus/H/SP/2024](https://github.com/mugwomp93/muOS_Customization/tree/main#perfect-overlays-for-rg35xx-plushsp2024and-possibly-other-devices)
2. [Game Boy Metallics Overlays](https://github.com/mugwomp93/muOS_Customization?tab=readme-ov-file#game-boy-metallics-overlays)
3. [Other Overlays](https://github.com/mugwomp93/muOS_Customization/tree/main#other-overlays)
4. (***NEW!***) [720x720 Overlays](https://github.com/mugwomp93/muOS_Customization/tree/main#720x720-overlays)

# [Perfect Overlays for RG35XX Plus/H/SP/2024](https://github.com/mugwomp93/muOS_Customization/blob/main/Perfect_Overlays_for_muOS.zip)<br>(and possibly other devices)
![github_banner2](https://github.com/user-attachments/assets/901f929a-1d00-4c1b-acb1-4f7da8d07a4b)

*Settings with step-by-step instructions for muOS are included in the readmes in the various zip files.*<br><br>

These are adaptations of 1playerinsertcoin's Perfect [DMG-EX](https://www.reddit.com/r/MiyooMini/comments/18e2o0z/i_remastered_my_game_boy_dmg_overlay/), [GBC](https://www.reddit.com/r/MiyooMini/comments/1857xa7/i_made_a_game_boy_color_overlay/), and [GBA](https://www.reddit.com/r/MiyooMini/comments/18ovuld/i_made_a_game_boy_advance_overlay/) Miyoo Mini overlays.

The versions hosted here have had minor alignment fixes for the RG35XX Plus/H/SP/2024 series of devices and have been tested on an RG35XX Plus using muOS. These overlays may work on other 640x480 devices and CFWs, though ymmv with regard to setup and alignment (since all three of the devices that I'm familiar with have minor scaling and positioning differences). Russ at Retro Game Corps has put together an excellent [guide to overlays and shaders on retro handheld devices](https://retrogamecorps.com/2024/09/01/guide-shaders-and-overlays-on-retro-handhelds/) that you may find useful if you're looking to get these working on another platform, or really just in general.

For the original RG35XX, see my [Garlic OS repository](https://github.com/mugwomp93/GarlicOS_Customization).

For the Miyoo Mini (Plus), see [1playerinsertcoin's original Reddit posts](https://www.reddit.com/u/1playerinsertcoin/s/yhapRMwOJz). It's worth checking out all of their other overlays, too.
#
***Updates 2025-04-04:***
- **Perfect Overlays for muOS are included in muOS 2502.0 Pixie by default**
- However, the updated version of Retroarch in Pixie has additional Viewport Anchor Bias parameters in Video > Scaling that must be set for GBA instead of (Viewport Anchor Bias Y = 0.00) or in addition to (Viewport Anchor Bias Y = 1.00) the previously recommended scaling settings that aren't in the README that was merged
- If you're trying to use the Perfect GBA overlay and the top is cutoff, try setting Viewport Anchor Bias to 1.00 (or 0.00 if that doesn't work, but 1.00 seems to be the solution)
- If your Viewport Anchor Bias settings won't save with your override, try deleting all existing GBA content directory and/or core overrides and saving a new override
- Updated GBA scaling settings in the README included in files on this Github page for muOS 2502.0 Pixie

***Updated 2025-03-12:***
- Added additional recommended shaders and shader settings for DMG/GBP and GBA (pixel_aa, sharp-shimmerless) 
- No changes to overlays, no need to change settings if what you're currently using is working for you
- Sharp-shimmerless isn't quite as good for DMG/GBP as pixellate/pixel_aa, but is less demanding if you have slowdown
- Clarified linear scaling for GBA instead of default (for whatever reason, default gives me linear scaling but others report nearest neighbour)

***Updated 2025-01-08:***
- Clarified that custom palettes for DMG and GBP may need to be copied to TF2 if muOS has been migrated to SD2 using the Task Toolkit

***Updated 2024-12-30:***
- Fixed a minor visual artifact present in some GBP overlays

***Updated 2024-09-26:***
- Added versions using the optimized (non-bright) Perfect GBA overlay to the Perfect_Overlays_for_muOS and Perfect_GBA_for_muOS zips
- Added a zip with just the new versions (Perfect_GBA_non-bright_only) for people who had previously downloaded the GBA overlays<br><br>

The [Perfect_Overlays_for_muOS zip file](https://github.com/mugwomp93/muOS_Customization/blob/main/Perfect_Overlays_for_muOS.zip) is a compilation of all three system-specific zip files (DMG/GBP, GBC, and GBA).

1. **[Perfect DMG/GBP Overlays](https://github.com/mugwomp93/muOS_Customization/blob/main/Perfect_DMG_GBP_for_muOS.zip)** - *updated 2024-09-14*<br>Updated versions have a corrected 533 px grid (old was 532 px), a better shader recommendation, and a significantly improved border shadow. Much crisper image than the previous version. There are also no grid, no shadow, and no grid + no shadow options for all borders.<br><br>Comparison of new vs. old:<br>![DMG_overlay](https://github.com/user-attachments/assets/3b41e2a5-c3fa-4a41-b9a7-3f7010400ba4)<br><br>Border options:<br>![DMG_GBP_example_borders](https://github.com/user-attachments/assets/ddad0d35-1a17-4564-aed2-97aa497bd7db)<br><br><br>
2. **[Perfect GBA Overlays](https://github.com/mugwomp93/muOS_Customization/blob/main/Perfect_GBA_for_muOS.zip)** - *updated 2024-09-26*<br>Added versions using the optimized (non-bright) Perfect GBA overlay. No new border options were added.<br><br>Border options:<br>![GBA_example_borders](https://github.com/user-attachments/assets/17c2ddcf-d249-4d77-9d1a-12816d978408)<br><br><br>
3. **[Perfect GBC Overlays](https://github.com/mugwomp93/muOS_Customization/blob/main/Perfect_GBC_for_muOS.zip)** - *updated 2024-09-21*<br>Updated versions have a corrected 533 px grid (old was 532 px) and a better shader recommendation. A crisper image than the previous version. There are also no grid, no shadow, and no grid + no shadow options for all borders, plus a new border based on one of 1playerinsertcoin's original designs!<br><br>Comparison of new vs. old:<br>![GBC_overlay](https://github.com/user-attachments/assets/d1520c42-4cde-40e1-931c-254fe7fe4abc)<br><br>Border options:<br>![GBC_example_borders](https://github.com/user-attachments/assets/9790e994-5e64-4468-a1e4-d1d685c2ec98)<br><br>


# [Game Boy Metallics Overlays](https://github.com/mugwomp93/muOS_Customization/tree/main/Game%20Boy%20Metallics)
<br>![Game Boy Metallics Preview 2](https://github.com/user-attachments/assets/d34e6032-0dff-48ac-a8f7-a4076bc17442)

<br>*Updated 2024-12-02 to remove artifacts that should be invisible on most devices.*
<br>I recommend updating only if you are experiencing unexplained performance issues (please test with and without the overlays applied to ensure these aren't part of the game or due to other settings) or can see artifacts around the right and bottom borders.

<br>***These overlays are identical to the ones found in my [Garlic OS repository](https://github.com/mugwomp93/GarlicOS_Customization)***

<br>This is the culmination of a couple of projects I've wanted to work on for a while: revisiting my first attempts at integer-scale Game Boy overlays and seeing if I could improve the default Game Boy palettes in Retroarch for my RG35XX Plus (which I've never been happy with). The result is these overlays, which use colored grids to tweak the appearances of the internal Gambatte Game Boy palettes.

The final versions were a compromise of color, grid line visibility, and contrast within the constraints of the existing internal palettes (e.g., changing the overlay opacity affects also affects the color and contrast). As a result, I ended up creating some optional custom palettes to help improve the contrast and in some cases (DMG, GBL) further refine the color schemes.

<br>***Note that these are likely horribly oversaturated on better screens***<br> 
<br><br>![Example - DMG](https://github.com/user-attachments/assets/86e042cd-f108-4878-98ad-e8ce099bd746)
<br><br>![Example - GB Pocket](https://github.com/user-attachments/assets/90c705dc-b28c-401e-92d0-a13915df43cf)
<br><br>![Example - GB Light](https://github.com/user-attachments/assets/28e9615f-5ae7-4b3a-959f-e20c4aa18a2d)
<br><br>![Example - Virtual Boy](https://github.com/user-attachments/assets/c14436ab-d522-4867-b194-943aedbb579b)<br><br>

The screenshots used in the pictures above were taken on an RG35XX Plus and edited to match (at least as closely as possible) what I see on my original RG35XX. The colors on my RG35XX Plus are similar if slightly more washed out. Given the difficulties in conveying accurate colors (my display isn't calibrated, your display likely isn't calibrated, your handheld likely doesn't display accurate colors anyway, etc.), it's difficult to say whether the colors you see are representative of what these overlays and palettes will look like on your device; however, each image is internally consistent with the colors on my RG35XX, so you can likely compare the raw palette images with what those palettes look like on your device to get an idea of how the overlays will look.

If you just want the four overlays featured in the images, you can download my [preferred pack](https://github.com/mugwomp93/muOS_Customization/blob/main/Game%20Boy%20Metallics%20-%20Preferred%20Pack.zip). Otherwise, I've uploaded all combinations of the borders x overlay grids, with and without power lights, as well as borders-only and no-borders versions, [here](https://github.com/mugwomp93/muOS_Customization/tree/main/Game%20Boy%20Metallics). You'll need to download the custom palette(s) from the relevant subfolders if you decide to download individual overlays, or you can download a zip file with all of them [here](https://github.com/mugwomp93/muOS_Customization/blob/main/GBM_Custom_Palettes.zip) (make sure to read the readme for instructions).

**Recommended settings and instructions for the custom palettes can be found in the readme files in both the preferred pack zip file and the top-level Game Boy Metallics folder.**<br><br>


# Other Overlays

1. **[Neo Geo Pocket Color](https://github.com/mugwomp93/muOS_Customization/blob/main/NGPC_mugwomp93.zip)**
<br>*An integer-scale NGPC overlay that uses a repeated 3x3 pixel section of 1playerinsertcoin's Perfect GBA overlay to create an lcd effect*<br><br>![NGPC_examples](https://github.com/user-attachments/assets/de9f492f-5997-4b98-9a25-5d000bfd1c5c)

# [720x720 Overlays](https://github.com/mugwomp93/720x720_overlays/tree/main)

I've created a [new repository](https://github.com/mugwomp93/720x720_overlays/tree/main) of 720x720 overlays that I'm working on. There's an integer-scale GB Advance overlay, non-integer scale grid+borders versions for GB Pocket/GB Light, GB Color, and Game Gear, and a variety of integer and non-integer scale, grid-only overlays created by 1playerinsertcoin for GB Advance, GB Color, Game Gear, Neo Geo Pocket Color, and PICO-8. (Note that Github scaling often creates banding in overlay grids depending on viewing size, zoom, etc. For best viewing, I recommend downloading the example images instead of viewing in Github if this is a concern)

![GBA_composite](https://github.com/user-attachments/assets/729affc3-2ce6-4dfa-88eb-b4b5f57e99f0)
![GBP_composite](https://github.com/user-attachments/assets/44d416ca-9248-47dc-b111-635575f1e9b5)
![GBL-Teal_composite](https://github.com/user-attachments/assets/a4e1f2c1-a701-420d-a198-ae7a601ba47e)
![GBL-Blue_composite](https://github.com/user-attachments/assets/2f4c8113-3cbd-42e9-9003-236f8f3a35cf)
![GBC_composite](https://github.com/user-attachments/assets/796b24a5-e0d8-4f3a-823e-16879ce216b6)
![GG_composite](https://github.com/user-attachments/assets/50a01f21-fa25-41a1-a8e1-51a591716b94)


