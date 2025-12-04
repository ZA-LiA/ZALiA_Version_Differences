# ZALiA_Version_Differences
Information on differences between ZALiA versions
---
<br>

## Difference Between the Current Release 1.0.0.2 and the Current Beta-Build

#### [Addition & Change] Rando: Mark Item Locations
> The feature that displays a checkmark on the overworld location of an acquired item now has an extra option to display item locations on the overworld regardless if the item has been acquired yet. This is helpful for people unfamiliar with ZALiA and its many item locations.

#### [Addition] Rando: Hint-NPC Indicator
> NPCs with a hint will now display a **question mark over their head** if the player has not yet talked to them.

#### [Addition] Rando: Zelda FLUTE Hint
> Because of the flute's special rando ability to warp to towns, the options for what hint Zelda will give you now includes the location of the FLUTE.

#### [Addition] Rando: Start With FLUTE
> The FLUTE has been added to the list of items you can start with for a rando run.

#### [Addition] Rando: Start with DOWN-THRUST and UP-THRUST
> The options to start rando with down-thrust and up-thrust have been added.

#### [Addition] In Dungeon Tileset Rando
> 1 extra tileset has been added to the shuffle pile and 2 special randomized textures.

#### [Addition] More Player Skins
> A few new player skins have been added.

#### [Addition] Alternative Game Fonts
> You can set the game's font to different fonts through the options menu.

#### [Addition] Quest Timer
> You can display the amount of time passed since starting the quest. Toggle in the options menu.

#### [Addition] Background Flash Color
> You can now disable background flashing in the options menu by setting the **BACKGROUND FLASHING** option to **NONE**.

#### [Addition] Overworld Softlock Failsafe
> If for whatever reason you get stuck in the overworld, you can warp to the **ContinueSave Screen**.
> To activate the failsafe:
> 1. **Press** the `pause button` to pause the overworld
> 2. **Hold** for 3 seconds: `RT+LT+XBox(B)` or `Ctrl+Backspace`

#### [Addition] App Graphic Effects
> You can enable and adjust various graphic effects(mostly retro-like ones) for the app:
> * Brightness
> * Saturation
> * Blur
> * Bloom
> * Scanlines
>
> This is done through a GUI called **Graphics Effects Editor** which can be enabled in **OTHER** of the options menu.
> 
> Please note that these are the first shaders I ever wrote so don't expect anything that pretty, including their permormance.

---
<br>

#### [Change] Nomaph Audio Set Updated
> Nomaph has remastered their audio set **Nomaph**.

#### [Change] Platforming Challenge Difficulty Reduction
> The difficulty has been reduced for the platforming challenge room at North Castle.

#### [Change] Crumble Floor Tile Graphics
> The graphics of floors that crumble when walked on has changed so there is much more of a distinction between which ones regenerate and which ones do not. This is only cosmetic.

#### [Change] Faster Player Movement Speed
> For fun, the **dash** dev cheat is available to the anyone. This is just faster walk speed for the player.
>
> Enable it in the **DEV TOOLS** section of the options menu and also make sure the **DEV TOOLS STATE** is set to **ON**. Then, when holding **RT**, the player's horizontal speed cap is increased by **66%** (**24->40**).

#### [Change] Quit App Buttons
> The button combo for quitting the app has changed from **Hold** `TL+TR+Select+Start` to **Hold** `TL+TR+Select`.

#### [Change] Options Menu Access
> You can now open the options menu by controller: **Hold** `BL+BR` + **Press** `XBox-Y`.

#### [Change] Automatic Rando Features
> Rando options that are mostly cosmetic no longer need to be requested when creating a new save file.
> 
> These options are now processed for every quest and are adjustable in the options menu:
> * Palette Rando
> * Dungeon Tileset Rando
> * Overworld Biome Rando
> * Scene Rando
> * Dungeon Completion Requirement

#### [Change] Rando Start-With Containers
> Rando now allows you to start with **1-9** heart/magic containers instead of only **3-8**.
>
> For starting items, rando logic will only interject to make sure the seed is completeable. So, if you start with less than the default **3** magic containers, the rando logic will make sure you can reach enough magic containers to progress, if required to progress.

#### [Change] Palette Rando
> Previously, non-dungeon rooms would re-randomize their colors every time the room refreshed. Now, a room's randomized palette will be the same for the whole quest.

#### [Change] Improved Room Rando
> Room Rando has been improved and includes more rooms in the rando mix, and balanced enemy difficulty.

#### [Change] Palette Rando Coloring
> The coloring of palette rando has been improved and is not limited to any set of colors.

#### [Change] Palette Swap System
> *Note the following will most likely only matter to people modding and adding graphics*
> 
> Previously, ZALiA's palette swap system could swap **3** distinct colors(full white, full red, full blue). That number is now **8**; full **WHITE**(0xFFFFFF), full **RED**(0x0000FF), full **BLUE**(0xFF0000), full **GREEN**(0x00FF00), full **YELLOW**(0x00FFFF), full **MAGENTA**(0xFF00FF), full **BLACK**(0x000000), full **CYAN**(0xFFFF00).
>
> Essentially, this means graphics can now use **8** colors, instead of **3**
> * Note that using full black **0x000000** may cause it to be swapped for a different color since it is now a base color. Therefor I recommend using the next closest color(**0x010101**) as your black.
> * Note that **0x7F7F7F**(mid-grey I think?) has the special property of becoming completely transparent if used. This functionality was added so that complicated shapes could be cut from images on the fly.

#### [Change] ZALiA's Palette
> *Note the following will most likely only matter to people modding and adding graphics*
> 
> Previously, ZALiA only used the **56** NES colors. More colors have been added, increasing the total **140**.
>
> However, these colors are just a predefined palette of suggested colors to use, ZALiA will accept ANY color you give it.

#### [Change] Consistancy of Item Positions in the Inventory
> The ||**ALLKEY**|| will always be in the 2nd row of items next to the ||**RED FAIRY**||.
> The ||**MASK**|| will always be the last to the right in the ||quest items row||.
> The ||**BOTTLE**|| will always be right above the ||magic container||.

#### [Change] Item Acquired Indication in Rando Spoiler File
> In the rando spoiler file, the text "ACQUIRED" will be noted next to an item if you've acquired that item. This action happens only after you save your game.

---
<br>

#### [Various]
> Other various fixes and adjustments.
