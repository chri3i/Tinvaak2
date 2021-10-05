# Tinvaak 2

![Tinvaak-banner](https://raw.githubusercontent.com/Althro/Tinvaak2/main/.github/T2Banner.webp)

Wabbajack Modlist Installer by The Animonculory.

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

- [Tinvaak](#Tinvaak)
  - [Preamble](#preamble)
  - [System Requirements](#system-requirements)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
      - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
      - [Steam Config](#steam-config)
        - [Disable the Steam Overlay](#disable-the-steam-overlay)
      - [Change Steams Update Behavior](#change-steams-update-behavior)
      - [Set the Game language and Windows Region to English](#set-the-game-language-and-windows-region-to-english)
      - [Clean Skyrim](#clean-skyrim)
      - [Start Skyrim](#start-skyrim)
    - [Using Wabbajack](#using-wabbajack)
      - [Preparations](#preparations)
      - [Downloading and Installing](#downloading-and-installing)
        - [Problems with Wabbajack](#problems-with-wabbajack)
  - [Post-Installation](#post-installation)
    - [Game Folder](#game-folder)
    - [BethINI](#bethini)
    - [ENB](#enb)
  - [How to start up Tinvaak](#how-to-start-up-tinvaak)
  - [Updating](#updating)
  - [Changes to Gameplay](#Changes-to-Gameplay) 
  - [In-Game MCM Options](#in-game-mcm-options)
  - [Creating your Character](#creating-your-character)
  - [Other Post Installation FAQ](#other-post-installation-faq)
    - [Ultrawide Options](#ultrawide-options)
    - [Tweaking the Game Settings](#tweaking-the-game-settings)
	- [Tweaking the ENB](#tweaking-the-enb)
    - [Zoomed in Display](#zoomed-in-display)
    - [Removing the modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)
  - [Contact](#contact)
  - [Contributing](#contributing)
  - [Changelog](#changelog)

## Preamble

Tinvaak is a list focused on revitalising and reworking SkyrimSE into an actual roleplaying game. Featuring a wide range of new mechanics including a fully reworked combat system courtesy of Engarde and SkySA, Settlement building, Reworked Alchemy, quests such as Wyrmstooth and the VenjHammet Suite, Survival mods, optional Khajiit Speak and many other elements.

Version 2.0 has been completely rebuilt and reworked to provide the optimum performance, stability and experience. Get ready to improvise, adapt and survive your way through a revitalised worldspace.

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

## Creation Ethos

The core element of T2 is roleplaying and having a D&D like feel with some witcher elements thrown in for good measure. The essence of the feeling can be described as this: 

> "The Dragonborn may very well carry the day, but to this uncaring realm, you are just a mortal. Just another person in the worldspace to see and not necessarily interact with. As you advance, weapons drawn, you hesitate, unsure if you can really do this. That tiny bit of uncertainty, that small voice of doubt. It's amplified and ever present."

Do not expect vanilla gameplay. Many aspects have been changed from the original game. This list is **not recommended** if this is your first time playing Skyrim.

**Please read the ReadMe in Full. The installation process is not completed once you have finished the Wabbajack installation.**

## System Requirements

2.0 of Tinvaak has been tested on a variety of machines to help better understand the system requirements of the list. It is aimed at higher tier machines in terms of system requirements. 

 - *NOTE: T2 is **very** graphically demanding so it is highly recommended to be installed on a SSD and that you have at least 16GB of RAM. It may be possible to run on lower spec systems, however these specs are the recommended ones.*

Recommended Specs for 1080p:

- 2nd Gen Ryzen (2800x) / 7th Gen Intel i5 or better
- 16GB Ram
- SSD
- 6GB GPU such as GTX 1660 Super or RX 5600xt minimum; 8GB GPU such as 5700xt or GTX 1080 recommended.

Recommended Specs for 1440p:

- 3rd Gen Ryzen (3600) / 9th Gen Intel i5 or better
- 32GB Ram
- NVME SSD
- 8GB GPU such as RTX 2080 or RX 6700XT minimum; 10GB+ GPU such as RTX 3080TI or RX 6800 recommended.

I run the list at an average of locked 60fps with a few dips here and there at 1440p on the following specs:

- Ryzen 7 5800X
- 32GB 3600mhz Ram
- PCIe Based NVME SSD
- XFX RX 6800 16GB
- Windows 11 Dev Branch

One of the Dev Team runs the list at an average of locked 60 fps on the following specs:

- 2nd Gen Ryzen
- 32GB Ram
- Sata based SSD
- RTX 2080
- Ultrawide 21:9 1080p screen

Space required: Approx 250GB

## Installation

### Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Steam Config

##### Disable the Steam Overlay

The Steam Overlay can cause issues with ENB and is recommended to be turned off.

Open the Properties window (right click the game in your Library->Properties), navigate to the _General_ tab and un-tick the _Enable the Steam Overlay while in-game_ checkbox.

#### Change Steams Update Behavior

SSE is still being updated by Bethesda (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically updates the game for you, head over to the Properties window, navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_. You should also disable the Steam Cloud while you're at it.

#### Set the Game language and Windows Region to English

This entire Modlist is in English and 99% of all mods you will find are also in English. Some mods can break when using a non English version of Windows. Ensure that your Windows Regional Format is set to English. 

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

#### Clean Skyrim

Due to the way Tinvaak 2 is setup, I highly recommend uninstalling the game through Steam, deleting the game folder and reinstalling it. You should also clean up the `Skyrim Special Edition` folder in `Documents/My Games/` by deleting the contents in it. Alternatively, use the [Shredder](https://www.nexusmods.com/skyrimspecialedition/mods/30133) to complelety wipe the game.

### It is *vital* that your Binkw64.dll is unmodified and *not* a replacement from another mod. If you have a version that is not 292KB in size, delete it and verify your game files.

#### Start Skyrim

After you have done everything above and got a clean SSE installation ready, start the Launcher and and let it do the initial graphics check. Do not worry about this part as the installation will replace this graphics settings.
Start the game and exit once you're in the main menu.

### Using Wabbajack

#### Preparations

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in a _working folder_. This folder **must not** be in a _common folders_ like your Desktop, Downloads, OneDrive or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`.

#### Downloading and Installing

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

1. Open Wabbajack and click on browse modlists.
2. Download the modlist from the Wabbajack UI.
3. Once the download is done, set the installation folder to somewhere that is not affected by UAC (Please do not put it in Documents, Program Files, Desktop. Put it somewhere easy like `C:/Modlists/Tinvaak`). The downloads path should automatically fill in the installation path.
4. Click the Go/Begin button
5. Wait for Wabbajack to finish
6. If you run into any issues see the next section. If the installation is successful, proceed to [Post-Installation](#post-installation).

##### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you lose no progress.

**Could not download x**:

If a mod updated and the old files got deleted, it is impossible to download them. In this case just wait until I update the Modlist.

**x is not a whitelisted download**:

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

**Windows is reporting that a virus has been detected**:

Windows 10 has started to auto quarantine the usvfs_proxy_x86.exe file from the latest version of Mod Organizer 2 saying a threat was detected. This is a known false postive confirmed by the MO2 Devs. You can fix this by adding an exemption for MO2 Folder to your Antivirus. An example for windows defender can be found [here](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

### Game Folder
The installation will create a copy of your Skyrim Special Edition game in Installation Folder/Game Root. This will then contain all the necessary files such as SKSE, ENB Binaries and mod required dlls such as Engine Fixes. There is no need to copy anything to your Steam version of Skyrim as we will be running SKSE from within this folder to play the game.

### BethINI

Go to your Tinvaak 2 installation folder > Tools > BethINI and run the program, set up your resolution and choose whether you want borderless/windowed or fullscreen. Hit save and exit. You're done this part! IF you do not do this step, you may wind up running at an upscaled 1440p if you don't have a 1440p monitor. This could potentially save you some performance hit.

### ENB

Tinvaak 2 comes with a pre-configured Ominous ENB for Obsidian Weathers included. This has been heavily modified to work with the imagespace that's used in Tinvaak 2 and will look very different to what you may expect.

If you want a different ENB, you can choose from a wide variety of ENBs on the Nexus that support Obsidian Weathers.
- *NOTE: In order for the ENB to sit properly with the lighting mod used, you should look for an ENB that properly supports LUX.*

To replace the ENB installed, delete the enbcache folder, enbseries folder, enbseries.ini **from the game root folder** and replace those with the new ENB. You don't have to delete the enblocal.ini as that contains tweaks that don't affect how it looks but rather things like screenshot formats, vsync settings.

## How to start up Tinvaak

Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. Once it's launched, there will be a dropdown box on the top right and a big run button next to it. Ensure it is set to 'Play Tinvaak' by selecting it in the dropdown box and then hitting the run button. 

There are two profiles for Tinvaak, one for regular dialogue, and one for Khajiit Speak dialogue.

## Updating

If this Modlist receives an update, please check the Changelog before doing anything. Always back up your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

## Changes to Gameplay

A video showcase on what is in Tinvaak 2 can be viewed in the trailer `coming soon`

Please do not expect the game to be functionally similar to vanilla. There are a lot of mods installed that modify core base game functionality as well as adding on new mechanics. Please see the [Changes to Gameplay](https://github.com/Althro/Tinvaak2/blob/main/Changes%20to%20Gameplay.md) article for a non-exhaustive list of changes in Tinvaak.

## In-Game MCM Options

Most of the **Required MCM** setups have been automated and set for you.

Tweak the following to your liking:

- SkyUI
- Lucien (If you set a nickname that's supported he can call you by that name)
- RASS
- Storm Lightning (I recommend the ultra-realistic preset)
- Lock Overhaul (**Do not enable the spell unlock**)

For Widescreen users: 
- Extended UI: Aspect Ratio

### Skyrim Unbound
Configure this MCM last. Select your loadout, dragons, and dragonborn status. **Note**: If you want to be dragonborn, you have to set your dragonborn status to be dragonborn and not random. There are some pre-made presets that you can use if you are struggling to think of what to play. When you're ready to create your character, select `Let's go!`

## Creating your Character

Once you have finished the MCM setup, create your character in race menu. There are some Racemenu presets included with the list for you to use if you wish to.

### Sunhelm (Do This after character creation and you have spawned into the world.)
- General Settings
	- Gameplay Options
		- Toggle Raw Meat Damage [unchecked]
		- Toggle Carry Weight Penalty [unchecked]

## Other Post Installation FAQ

### Controller Setup

Please follow this [excellent guide by ShadesOfDawn and Chri3i](https://github.com/chri3i/Gamepad-Guide-by-ShadesOfDawn-and-me) for setting up a controller with Tinvaak. Antimicro is included with the list to allow for Engarde compatability.

### Ultrawide Options

I do not use an Ultrawide monitor thus cannot offer support beyond what is below.

Horizon UI inlcudes a 21:9 profile which you should activate, alongside the 21x9 loading screens replacer.

Open up BethINI, set up your resolution and enable borderless windowed in the settings, otherwise your game might look slightly offset.

### Tweaking the Game Settings

I highly recommend using [BethINI](https://www.nexusmods.com/skyrimspecialedition/mods/4875) which is included in this Modlist (can be found in `MO2/tools/BethINI`). I recommend tweaking the `Detail` section for more FPS:

- `Shadow Resolution`: Very big one. A good balance is `2048` which is the borderline between high FPS drainage and garbage looking shadows.
- `Ambient Occlusion`: Highly recommended to turn either this or your ENB version off. Do not have the game AO and an ENB AO turned on at the same time.
- `Remove Shadows`: If you really struggle, use this. This will disable all Shadows (not recommended)

### Tweaking the ENB

By default, Tinvaak ships with an ENB profile that has been custom tweaked to match the modlist. If you wish to make changes to them to better suit your visual preferences, follow the information below.

To remove the letterbox effect:
- Press [Shift+Enter] to open the ENB menu
- In the right tab called Shader parameters, there is a section called `ENBPOSTPASS.FX`. Select it to open it.
- Scroll down to letterbox and disable it.
- Press the save configuration button.
- You have now disabled letterbox and can press [shift+enter] to return to game.

Open the console with `~` before doing edits, so you're not randomly swinging weapons around while editing the ENB.

If you're really struggling with FPS but want the color correction and realism, disable the following in the ENB GUI [shift+enter]:

##### enbseries.ini
 
  - DetailedShadow
  - ComplexFireLights
  - ComplexParticleLights
  - Reflection
  - ComplexParticlLights Settings > Disable "Big Range" (This is circumstantial and location dependent, but it can save a lot of FPS in the long run.)

##### If you cannot handle the ENB: Disable `useEffect` in enbseries.ini

### Zoomed in Display

This can be caused by Window's Display Scaling feature. This usually is set to above 100% when using very large (32 inch++) sized monitors and TVs. There are two solutions to this

- Set the display scaling back to 100% in the Screen Resolution Settings for Windows
- Edit the mod SSE Display Tweaks.
  - Under `[Render]`
    - Set Fullscreen to `True`
    - Set Borderless to `False`
    
## Removing the Modlist

You can just delete the MO2 folder and be done with it.

## Credits and Thanks

- _YOU_ for actually reading the readme. Thanks a ton!!
- TheSpaniard, Chef & Annakins for assisting in the development and creation of Tinvaak 2.
- Galaxy Synth for help in the creation, configuration and setup of Tinvaak 1.
- Noggog for Mutagen.
- Special thanks to the Synthesis patcher devs.
- erri120 & jdsmith2816 - Repository template.
- iXanza, JanuarySnow and Nem for recompiled MCM scripts for automation.
- Shuckleberry for Skyrim Unbound Presets.
- Halgari and everyone the WJ Team - Wabbajack is awesome and so are you.
- Chef for Ultrawide installation instructions.
- My amazing Patreons.

## Contact

Whilst I'm always available on the [Wabbajack Discord](https://discord.gg/wabbajack) and my server, I would advise checking the [Issues](https://github.com/Althro/Tinvaak2/issues) (open **and** closed ones) on GitHub first if you have any problems. **DO NOT DM ME ON DISCORD. I WILL NOT PROVIDE SUPPORT FOR YOU IN DMS**.

## Contributing

See [Contributing](https://github.com/Althro/Tinvaak2/blob/main/Contributing.md).

## Changelog

See [Changelog](https://github.com/Althro/Tinvaak2/blob/main/Changelog.md).
