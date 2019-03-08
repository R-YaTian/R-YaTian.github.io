---
title: Installing DSiWare
redirect_from:
  - more/installing-dsiware
---

You must have [Unlaunch](/guide/installing-unlaunch/) and [HiyaCFW](/guide/installing-hiyacfw/) installed before proceeding.
{: .notice--info}

This will install your DSiWare dumps to your DSi console's home menu using maketmd, a tool that converts your DSiWare dumps into an installable format.

## What you need
- The latest release of [maketmd](https://github.com/Tuxality/maketmd/releases){:target="_blank"}
- Your DSiWare dump.

## Instructions
1. Copy *the contents of* the maketmd `.zip` file to a folder on your PC
2. Open the `content` folder inside the DSiWare dump.
3. Delete the `cmd` folder, and the `.tmd` file
4. Delete any `.ctx` files if they exist
5. Drag and drop the `.app` file onto the maketmd program
    - You will see a new file named `title.tmd` be created
6. Copy the DSiWare folder to the `/title/00030004` folder on your DSi's SD card
7. Power on your DSi, and unwrap the DSiWare
    - If you boot to an "error has occured" screen, you have exceeded the amount of allowed DSiWare blocks on your system. You can remove this installation by [installing TWiLight Menu++](installing-twilight-menu++)
