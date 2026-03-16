# Dark Messiah RTX Mod Files
The mod files for the DM RTX Mod. This is the final set of files, not compliable code.

if you have an older (DM:RTX Patch) version of this mod, it is recommended you uninstall those files by deleting them!
## Dependencies
wiltOS Dark Messiah Mod Launcher [Download](https://www.moddb.com/games/dark-messiah-of-might-magic/downloads)

wiltOS Dark Messiah Advanced SDK Base Module [Download](https://github.com/KingDavidW/DarkMessiah-AdvancedSDK-Mod-Files)

Dark Messiah: RTX Base Files (this repo) [Download](https://github.com/KingDavidW/DarkMessiah-RTX-Mod-Files/archive/refs/heads/main.zip)

Dark Messiah: RTX Lite Edition Content [Download](https://github.com/KingDavidW/DarkMessiah-RTX-Mod-Files/releases)

## How to Install
First install the latest Mod Launcher

Then, install the latest SDK Base into your _mods folder

Next, install the RTX Base Files into your Dark Messiah of Might and Magic folder (same as the mod launcher)

Finally install the Lite Edition content. The content is available in the RELEASES section. Content is extremely large, and is installed the same way as the Base files. Note that there will be patches available there for new content and it should be all applied in order of release.

## Mod Order Requirement
Make the Advanced SDK the first mod in your list, above everything else.

## Note On Disabling

Since Remix is loaded at the core next to **mm.exe**, if you want to turn remix off you will need to rename or delete the **d3d9.dll** file in that directory. We'll work on fixing this in the future!

You'll also want to enable the DirectX 9.5 enforcement on relaunch, to make sure you get out of DX7 mode!

## Credits
King David for doing the programming and bug fixing

NVIDIA for the fixed function pipeline code that was reverse engineered out of Portal RTX

Lerd for making character mesh skins

Hetman Lerman for making environment art and some props

Riddick, Granto, and QWERTY for making some assorted props

Stickyfingaz for creating an algorithm for pulling color information from the original textures

Kapibaros for creating a bunch of models and the remaining environment textures

The ChaiNNer and RTX Discord for helping get the whole thing put together!
