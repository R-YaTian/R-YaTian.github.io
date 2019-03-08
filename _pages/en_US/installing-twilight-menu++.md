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

TWiLightMenu++ is an open-source & customizable alternative to the Nintendo DSi's System Menu. It can be used as a frontend for either nds-bootstrap or supported flashcards. It also provides a unified interface for launching NES, SNES, Gameboy (color), SEGA GameGear, SEGA Genesis, Nintendo DS & DSiWare titles.

## Downloads

- The latest release of [TWiLight Menu++](https://github.com/RocketRobz/TWiLightMenu/releases){:target="_blank"}
- The latest release of [FBI](https://github.com/Steveice10/FBI/releases){:target="_blank"} for 3DS users
- The latest release of the [TWiLight Menu++ Updater](https://github.com/RocketRobz/TWiLightMenu-Updater/releases){:target="_blank"} for 3DS users

## Manual Installation (for 3DS, DSi & Flashcard users)

1. Open the TWiLight Menu++ `.7z` file
2. Copy the `_nds` folder to the root of your SD card
3. For DSi users, copy *the contents of* the `SDNAND root` folder in the `DSi - CFW users` folder to the root of your SD card
4. For 3DS users, copy *the contents of* the `3DS - CFW users` folder to the `cia` folder of your SD card.
5. For 3DS users, copy `TWiLightMenu-Updater.cia` to the `cia` folder of your SD card
5. For flashcard users, copy the `_nds` folder and the `boot.nds` file located inside the `flashcard` folder to the root of your SD card
6. For DSi & 3DS users, copy the `_nds` folder and `boot.nds` file from `DSi&3DS - SD card users` folder to the root of your SD card
7. For 3DS users, install the 3 cia files found inside the cia folder using FBI.

For 3DS and DSi users, TWiLight Menu++ should now be on your System Menu, as any other DSiWare would be.
For Flashcard users, TWiLight Menu++ can now be loaded using your flashcard loader.

## Automatic Installation (for 3DS users)

1. Copy `TWiLightMenu-Updater.cia` to the `cia` folder of your SD card
2. Install `TWiLightMenu-Updater.cia` using FBI.
3. Launch the updater.
4. Download the latest release of TWiLightMenu++ & nds-bootstrap using the updater.

## Usage

- To launch Gameboy Advance games, you'll need a copy of the GBA BIOS named `bios.bin` on the root of your SD card.
- You can place ROMs anywhere on the SD card.
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
