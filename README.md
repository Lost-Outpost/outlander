<a href="#"><img src="images/banner.webp" target="_blank"></a>

---

<p align="center">
  <a href="https://www.nexusmods.com/enderalspecialedition/mods/389">Nexus Page</a> ·
  <a href="README.md">Installation</a> ·
  <a href="GAMEPLAY.md">Gameplay Guide</a> ·
  <a href="CONFIGURATION.md">Configuration</a> ·
  <a href="CHANGELOG.md">Changelog</a> ·
  <a href="HELP.md">Help</a>
</p>

---

**Modlist Download: [The Path.wabbajack](https://github.com/Guitarninja2/thepath/releases/download/1.0.0-BETA2/The.Path-1.0.0-BETA2.wabbajack)**

**Modlist Support: [The Animonculory Server](https://discord.gg/DffHKcszfg)**

# Installation

- [Introduction](#introduction)
  - [Minimum Specs](#minimum-specs)
  - [Community](#community)
  - [List Contents](#list-contents)
- [Installation](#installation)
  - [Pre-Installation](#pre-installation)
    - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
    - [Steam Library](#steam-library)
    - [Set the Game language to English](#set-the-game-language-to-english)
    - [Clean Enderal](#clean-enderal)
    - [Start Enderal](#start-enderal)
  - [Using Wabbajack](#using-wabbajack)
    - [Preparations](#preparations)
    - [Downloading and Installing](#downloading-and-installing)
      - [Problems with Wabbajack](#problems-with-wabbajack)
    - [Stock Game](#stock-game)
    - [Pagefile in prevention of memory crashes](#pagefile-in-prevention-of-memory-crashes)
- [Updating](#updating)
- [Final Checklist](#final-checklist)
- [Gameplay Guide](#gameplay-guide)
- [Configuration](#configuration)
- [Issues](#issues)
- [The Path Team](#the-path-team)

# Introduction

The Path is a lightweight Enderal modlist meant to enhance visuals, provide quality of life improvements and introduce some small content additions while keeping close to the game's original vision.

### Minimum Specs
Users have reported running the list fine with as low as a Ryzen 1300x and a GTX960. You may need to use performance ini files (included) with systems this low but it should run fine and still look great!

### Community

Support is offered in [The Animonculory Server](https://discord.gg/DffHKcszfg) server and in the [Issues](https://github.com/Guitarninja2/thepath/issues) section of The Path GitHub. If you have any questions following the add-on's instructions or if you find a typo or any other mistake in the documentation, feel free to report in TPF Discord server's support channel.

### List Contents

You can browse the full list contents [here](https://loadorderlibrary.com/lists/thepath) if you want to know exactly what you're getting.

# Installation

Installation is handled through [Wabbajack](https://www.wabbajack.org/#/) with a one-click install of the modlist. There are some pre-installation steps which must be followed for first time users so please pay attention to those.

## Pre-Installation

These steps are only needed if you install the Modlist for the first time. If you are updating the Modlist, jump straight to [Updating](#updating).

### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. This package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

### Installing Microsoft .NET 5.0

Please ensure you have .NET v5.0 installed. The game will not launch if you do not have it installed. Download the **desktop app x64 AND console app x64 installers** from Microsoft [here](https://dotnet.microsoft.com/download/dotnet/5.0/runtime).

![Dot Net](https://raw.githubusercontent.com/Guitarninja2/septimus/main/images/microsoft-net-5-0-installation.png)

### Steam Library

If you have your Steam library in Program Files, read [this](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) to put it somewhere else.
I will not provide support to people with Enderal in their Program Files folder.
Locations like Documents, Downloads, Desktop, or OneDrive are NOT fine. The best location would be `C:\SteamLibrary` if you have a single drive, or whichever Drive Letter you have on your main Games drive. Such a location is also called the "root of the drive."

### Set the Game language to English

Just do it. This entire Modlist is in English and 99% of all mods you will find are also in English. I highly recommend playing the game in English and **I will not give support to people with a non-English game**.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

### Clean Enderal

I highly recommend uninstalling the game through Steam, deleting the game folder, and reinstalling it. You should also clean up the `Enderal Special Edition` folder in `Documents/My Games/` by deleting the contents in it.

[THIS](https://imgur.com/a/1dySo8q) is approximately what a clean Enderal install should look like after shredding or cleaning it manually.

## Start Enderal
Start the game and exit once you're in the main menu. This will ensure any settings files needed by Wabbajack are created in the Enderal directory.

## Using Wabbajack

### Preparations

Download the release to a _working folder_. This folder **must not** be in a _common folder_ like your Desktop, Downloads or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`.

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in the _working folder_.

### Downloading and Installing

The download and installation process can take a little while (an hour or more) depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

1. Create a folder for the List at the root of your drive (like the Wabbajack folder) called "The Path"
2. Go back to your drive, and create a new folder, called "Wabbajack Downloads Folder". This specific folder can be on a different drive if you wish
3. Download the latest release of `The Path` from the [Github Releases](https://github.com/Guitarninja2/thepath/releases) page
4. Select the created folder in step 1 as your installation folder
5. Select the created folder in step 2 as your downloads folder
6. Click the Go/Begin button and wait for Wabbajack to finish

### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you lose no progress.

Seriously, simply retrying the Wabbajack download fixes most problems.

**Could not download x**:

If a mod updated and the old files got deleted, it is impossible to download them. In this case, just wait until I update the Modlist.

Some files are known to be problematic, it is likely those are the ones that failed. You can download them manually from their source and place the archives **AS IS** in the downloads folder.

**x is not a whitelisted download**:

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

### Stock Game

Unlike regular Enderal installation or some other Wabbajack Lists, The Path comes with the **Stock Game Feature**.

Basically, the **Stock Game Feature** is a copy of a Enderal installation located within your installation folder, cleaned and with everything required in it. It allows you to not worry about conflicting files with Vortex or other Wabbajack lists. Thus, after you install The Path using Wabbajack, you need not to move anything to your regular Enderal installation folder.

There are more steps though, so please keep following the next steps to setup the game optimally.

### Pagefile in prevention of memory crashes

Bigger Enderal modlists need a lot of memory, and when there is not enough available it may fail allocating more. To fix this, you'll want to have a bigger <a href="PAGEFILE.md" target="_blank">pagefile</a>.

# Updating

If this Modlist receives an update, please check the [changelog](CHANGELOG.md) before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your saves will be kept, but please check each update changelog to see if the update is save compatible. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

# Final Checklist
Check the following items before starting the game (they are easy to miss)
- If you are using a wide-screen monitor, make sure you have done the [post-install steps for wide-screens](https://github.com/Guitarninja2/thepath/blob/main/CONFIGURATION.md#widescreen)
- Choose the ENB Preset you want (if you want one) from the [enb configuration](https://github.com/Guitarninja2/thepath/blob/main/CONFIGURATION.md#enb-and-reshade-presets) page

# Gameplay Guide
My team and I have put together a helpful [gameplay guide](GAMEPLAY.md) to get you informed on any gameplay changes and additional content you should be aware of. You can find that [here](GAMEPLAY.md).

# Configuration

If you wish to further customize by changing the ENB preset, changing dodge keys, or swapping optional mods you can visit the [Configuration](CONFIGURATION.md) page for more info.

# Issues

If you find an issue, you can see if it is already on the list of [known issues](HELP.md), which also documents solutions and workarounds.

For issues that aren't yet [known](HELP.md), you can provide details in the [Github Issues](https://github.com/Guitarninja2/thepath/issues). Please provide as much info as you can (screenshots are great).

Finally, free feel to hop on the The Path Discord support channel to have discussions with our knowledgeable community members. Support is offered in [The Animonculory Server](https://discord.gg/DffHKcszfg).

# The Path Team
+ Webmetz - Author of the Relics of Hyrule addon and awesome modder!
+ Rsrogers4 - Tons of documentation help!
