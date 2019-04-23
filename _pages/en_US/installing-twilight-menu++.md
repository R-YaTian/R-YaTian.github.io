---
title: Installing TWiLight Menu++
redirect_from:
  - /guide/finalizing-setup
  - /finalizing-setup
  - /installing-twlmenu++
  - more/replacing-system-menu
  - replacing-system-menu-with-srloader
  - replacing-system-menu-with-dsimenu++
  - replacing-system-menu-with-twilight-menu++
  - replacing-system-menu-with-twlmenu++
---

{% include toc title="Table of Contents" %}

TWiLight Menu++ is an open-source & customizable unified interface for launching NES, SNES, Gameboy (Color), SEGA GameGear, SEGA Genesis/Mega Drive, Nintendo DS & DSiWare titles that can completely replace the default menu. It can be used as a frontend for either nds-bootstrap or supported flashcards.

## Requirements

- The latest release of [TWiLight Menu++](https://github.com/RocketRobz/TWiLightMenu/releases){:target="_blank"}
- The latest release of the [TWiLight Menu++ Updater](https://github.com/RocketRobz/TWiLightMenu-Updater/releases){:target="_blank"} for 3DS users
- An active internet connection on your 3DS if you'd like to use the Automatic Installation process. If you do not own a Nintendo 3DS/you have not setup an active internet connection, follow the Manual Installation process.

## Manual Installation (3DS, DSi & Flashcard users)

1. Open the TWiLight Menu++ `.7z` file
2. Copy the `_nds` folder to the root of your SD card
3. For DSi users, copy *the contents of* `DSi - CFW users/SDNAND root` to the root of your SD card
4. For 3DS users, copy *the contents of* `3DS - CFW users` and `TWiLightMenu-Updater.cia` to the `cia` folder of your SD card.
5. For flashcard users, copy the `_nds` folder and the `boot.nds` file located inside the `flashcard` folder to the root of your SD card
6. For DSi & 3DS users, copy the `_nds` folder and `boot.nds` file from `DSi&3DS - SD card users` folder to the root of your SD card
7. For 3DS users, install the 3 cia files found inside the cia folder using a CIA manager.

For 3DS and DSi users, TWiLight Menu++ should now be on your System Menu, as any other DSiWare would be.
{: .notice--info}
For Flashcard users, TWiLight Menu++ can now be loaded using your flashcard loader.
{: .notice--info}

## Automatic Installation (3DS users)

1. Copy `TWiLightMenu-Updater.cia` to the `cia` folder of your SD card
2. Install `TWiLightMenu-Updater.cia` using FBI.
3. Launch the updater.
4. Download the latest release of TWiLightMenu++ & nds-bootstrap using the updater.

TWiLight Menu++ should now appear on your System Menu, as any other DSiWare would be
{: .notice--info}

## Usage

- To launch Gameboy Advance games, you'll need a copy of the GBA BIOS named `bios.bin` on the root of your SD card.
- You can place ROMs anywhere on the SD card.
- If you own a DSTWO, you can launch .plg files from the loader as well.
- You can pick between a Nintendo DSi theme, a Nintendo 3DS theme, a R4 theme and an akmenu theme.
- You can load sub-themes off the SD card. DS Homebrew contains repositories to host R4 themes, akmenu themes, DSi themes and 3DS themes.
- For DSi users, if you have Unlaunch and HiyaCFW, TWiLight Menu++ can completely replace your System Menu. This can help work around several bugs with SD card sizes and the DSiWare block limit.
- For flashcard users, if you have a compatible flashcard, you can make your flashcard autoboot into TWiLight Menu++.

## (DSi) Replacing the System Menu

You must have [Unlaunch](/guide/installing-unlaunch/) and [HiyaCFW](/guide/installing-hiyacfw/) installed before proceeding.
{: .notice--info}

1. Power on your DSi while holding **SELECT**
2. If `Autoboot title` is not checked, navigate to it and press **A**
3. Press **START** to save and continue booting
    - TWiLight Menu++ will appear

TWiLight Menu++ is now your System Menu. If you want to run DSiWare, wait for steps on how to run them to appear.
