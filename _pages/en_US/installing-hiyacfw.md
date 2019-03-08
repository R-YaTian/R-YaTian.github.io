---
title: Installing HiyaCFW
redirect_from:
  - /guide/installing-hiyacfw
---

{% include toc title="Table of Contents" %}

You will need [Unlaunch](installing-unlaunch/) installed before proceeding.
{: .notice--primary}

Do not perform a system update after installing HiyaCFW, as it will remove HiyaCFW's SD patches.
{: .notice--danger}

If your SD card is larger than 2 GB, keep in mind that HiyaCFW may not boot in to the System Menu. You will need to install TWiLight Menu++ as a System Menu replacement when the option is given.
{: .notice--info}

If you do not see TWiLight Menu++ on the System Menu, or if you see the "An error has occured" screen after installing TWiLight Menu++ as a System Menu replacement, then the HiyaCFW Helper isn't applying the CFW's patches properly. Please wait for a fix in the helper.
{: .notice--info}

HiyaCFW is the world's first CFW with features that include:
- Booting the system from the SD card
- Installing homebrew applications to the System Menu with ease
- Including a custom splash screen on boot
- Automatically booting into another application, such as [TWiLight Menu++](installing-twilight-menu++)


## Requirements

- A NAND backup taken from your device, with the NO$GBA Footer
  - fwTool 2.0 will create this footer automatically when it makes a backup
  - You should already have this backup from the previous section
- [HiyaCFW Helper](https://github.com/mondul/HiyaCFW-Helper/releases){:target="_blank"}
  - Windows users may use the .EXE
  - Users of other operating systems may use the .py (requires [Python 2](https://www.python.org/downloads/){:target="_blank"})
  - Windows users will additionally need the latest release of [OSFMount](https://www.osforensics.com/tools/mount-disk-images.html){:target="_blank"}

## Instructions

1. Insert your SD card into your PC
2. Copy *the contents of* the HiyaCFW Helper `.zip` file to a folder on your PC
3. Navigate to the extracted folder
4. Open HiyaCFW Helper as admin
  - This can be done on Windows by right-clicking -> `Run as administrator`
6. Click the `...` button in the `NAND file with No$GBA footer` box
7. Navigate to your NAND backup, and click `Open`
  - If you'd like to install TWiLight Menu++ as a replacement for the Nintendo DSi Menu, tick the `Install TWiLight Menu++ on custom firmware` checkbox.
8. Press `Start`
9. In the new pop-up window, navigate to your SD card, and press `OK`
  - The process may take several minutes
10. Close HiyaCFW Helper
11. Unplug your SD card, and insert it in your DSi
12. Power on your console
  - Unlaunch's GUI should appear
13. Navigate to `OPTIONS`, and press (A)
14. Press (A) to configure a default software to boot in to when no button is held
15. Navigate to `HIYACFW`, and press (A)
16. Navigate to `SAVE & EXIT`, and press (A)
17. Power off your console, and turn it back on
  - HiyaCFW's settings screen should appear
18. Change the settings to your liking, and press (START) to continue
  - If you boot to "An error has occured" screen, it's most likely because your SD card is larger than 2GB; follow [Replacing System Menu with TWiLight Menu++](replacing-system-menu-with-twilight-menu++) to work around this issue

Your system will now boot from the SD card instead of the internal NAND.

If you want to boot in to the internal storage, you may configure `LAUNCHER` to a hotkey in a similar manner to the one you just did for HiyaCFW.
