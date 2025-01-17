﻿[← back to readme](README.md)

# Release notes
## 1.3.2
Released 16 Aug 2021.

* Fixed minor bug with gamepad controls/snappy menus being incorrect on window resize

## 1.3.1
Released 22 Jul 2021.

* Fixed minor bug with snappy menus when option count is equal to maximum displayable

## 1.3.0
Released 21 Jul 2021.

* Added sort by soundtrack order
* Added reverse current sort
* Added settings to:
    * show unheard tracks from various different categories
        * optionally unlock unheard tracks permanently on a save file
        * disable menu to use only permanent additions
    * show or hide tracks from the list using a combination of presets/a blacklist/a whitelist
    * show unheard songs as locked
    * choose random songs from the displayed list instead of heard tracks
    * use Bandcamp song names
    * hide alternate sorts
* Moved a large number of strings to i18n for potential translation support
* Update redraw on window size change (again)

## 1.2.1
Released 05 Jul 2021.

* Added support for [GenericModConfigMenu](https://www.nexusmods.com/stardewvalley/mods/5098)
* Properly fixed selecting `random` for the first time on a save file

## 1.2
Released 28 Dec 2020.

* Added alphabetical sorting (soundtrack order to come)
* Handle vanilla failure when `random` is selected for the first time on a save file

### 1.1.2
Released 27 Dec 2020.

* Fixed snapping for list buttons

### 1.1.1
Released 27 Dec 2020.

* Added speculative gamepad support
* Added hover effect to more buttons
* Added menu background if enabled
* Added slight tint over background if menu background is not enabled

## 1.1
Released 23 Dec 2020.

* Updated for Stardew Valley 1.5
    * Added vanilla randomize
    * Added support for UI scaling
* Force "Stardew Valley Overture" to always be first
* Fixed:
    * wrong menu position when game window resizes
    * Saloon Jukebox getting extra buttons when Mini-Jukebox is placed
    * appearance of "resetVariable" (speculative; not in vanilla, can't reproduce)

## 1.0
Released 10 May 2020.

* Initial release.
