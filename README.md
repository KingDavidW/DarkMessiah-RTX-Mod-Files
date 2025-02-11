# Dark Messiah RTX Mod Files
The mod files for the DM RTX Mod. This is the final set of files, not compliable code.

## Dependencies
wiltOS Dark Messiah Mod Launcher [Download](https://www.moddb.com/games/dark-messiah-of-might-magic/downloads)

wiltOS Dark Messiah Advanced SDK Base Module [Download](https://github.com/KingDavidW/DarkMessiah-AdvancedSDK-Mod-Files)

RTX Remix [Download](https://github.com/NVIDIAGameWorks/rtx-remix)

## How to Install
Make sure you have the wiltOS Dark Messiah Mod Launcher installed!

Simply drag and drop the files from this repository and put them into your Dark Messiah Might and Magic Singleplayer folder.

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

The ChaiNNer and RTX Discord for helping get the whole thing put together!