<p align="center"><img src="https://github.com/ThePansmith/Monifactory/assets/70342772/4ac1d5e7-0610-4f44-bfed-b3b2022eecc0" height="250" alt="Logo"></p>
<h1 align="center">Monifactory</h1>
<p align="center"><b><i>A Remaster and Port of <a href="https://github.com/Nomi-CEu/Nomi-CEu"> Nomifactory CEu</a>, using <a href="https://github.com/GregTechCEu/GregTech-Modern"> GregTech CEu Modern</a> and other mods</i></b></p>
<h1 align="center">
    <a href="https://github.com/ThePansmith/Monifactory/blob/main/LICENSE.md"><img src="https://img.shields.io/github/license/Nomi-CEu/Nomi-CEu?style=for-the-badge&logo=github" alt="License"></a>
    <img src="https://img.shields.io/github/actions/workflow/status/ThePansmith/Monifactory/build_pr.yml?branch=main&style=for-the-badge&label=Dev%20Build" alt="GitHub Actions Workflow Status">
    <!-- <a href="https://discord.com/invite/zwQzqP8b6q"><img src="https://img.shields.io/discord/927050775073534012?style=for-the-badge&logo=discord&color=5865F2&labelColor=grey&label=+" alt="Discord"></a> -->
    <br>
    <a href="https://www.curseforge.com/minecraft/modpacks/Monifactory"><img src="https://cf.way2muchnoise.eu/monifactory.svg?badge_style=for_the_badge" alt="CurseForge"></a>
    <a href="https://www.curseforge.com/minecraft/modpacks/Monifactory"><img src="https://cf.way2muchnoise.eu/versions/For%20MC_Monifactory_all.svg?badge_style=for_the_badge" alt="MC Versions"></a>
    <a href="https://github.com/ThePansmith/Monifactory/releases"><img src="https://img.shields.io/github/downloads/ThePansmith/Monifactory/total?style=for-the-badge&labelColor=grey&logo=github&label=+" alt="GitHub Downloads"></a>
</h1>

## Features
- [Plenty of changes throughout the entire pack, from new multiblocks, to new mods, to new progression](CHANGELOG.md)
- A complete overhaul of UV+ progression from Nomifactory CEu
- Draconic Evolution and Avaritia have been replaced with new mechanics involving Sculk
- A new, Expert difficulty mode for returning Nomi CEu Hard Mode players
- A retexturing of everything to fit the modern style
- Optional compatibility with various mods, such as Create or XNet

## Credits
- Original pack by [Exaxxion](https://github.com/Exaxxion).
- Nomifactory CEu pack by [Tracer4b](https://github.com/tracer4b).  
- README.md adapted from [GregTech CEu](https://github.com/GregTechCEu/GregTech).  
- Meowni (mascot) by [Mutso](https://bsky.app/profile/did:plc:pgazjc76vpn6mr7rldk56ugq).  
- Certain new quests from [GregTech Community Pack](https://github.com/GregTechCEu/GregTech-Community-Pack).  
Thank you!

## Hard/Expert Mode
Is Monifactory not Greggy enough for you? Or do you simply want a challenge? Try Hard Mode (or even Expert Mode, if you're not faint of heart!)

Highlights include:

- Forced Peaceful Mode
- The Steam Age
- No Hostile Neural Networks for easy infinite resources
- Monicoins can't be spent
- Harder processing lines for Platinum and Naquadah
- More focus on GregTech Power Generation

Expert Mode is a modifier for Hard Mode, and takes things a step further by:

- Disabling RF -> EU conversion, making GT power generation required
- EnderIO Conduits are removed
- LaserIO is disabled
- GT5u-style machine explosions
- Various other nerfs

## Installation:

### Hard/Expert Mode Installation:
1. Download [``./pack-mode-switcher.bat``](https://github.com/ThePansmith/Monifactory/blob/main/pack-mode-switcher.bat) if you're on Windows, or [``./pack-mode-switcher.sh``](https://github.com/ThePansmith/Monifactory/blob/main/pack-mode-switcher.sh) if you're on Linux/MacOS/GNU
2. Move the shell script into the ``.minecraft`` folder where Monifactory is installed
- Windows:
    - Manual:
        1. Open your Minecraft / Minecraft instance folder and click on ``pack-mode-switcher.bat``.
        2. Follow the prompt to select your mode.
        3. Redo steps 1 & 2 every time after you've updated the modpack.

    - Prism Launcher (and various other custom launchers):
        1. If your Minecraft launcher supports it, select your Minecraft instance -> Edit -> Settings -> Custom Commands, check ``Custom Commands``, paste
           ```
           $INST_DIR\minecraft\pack-mode-switcher.bat (N/H/E)
           ```
           into Pre-launch command and specify your wanted mode.

- Linux/Apple/GNU:
1. Open [``./pack-mode-switcher.sh``](https://github.com/ThePansmith/Monifactory/blob/main/pack-mode-switcher.sh) and download the file to your Minecraft / Minecraft instance folder.
1. Open your Minecraft / Minecraft instance folder and click on ``pack-mode-switcher.sh``.
2. Follow the prompt to select your mode.

### Addon Mods (AKA Optional Compats)
To spice up your Monifactory experience, you can add any of the following mods to your ``minecraft/mods`` folder for their recipes and config files to be automatically altered for compatibility with Monifactory progression.
1. [Create](https://www.curseforge.com/minecraft/mc-mods/create)
    1a. [Create: Steam and Rails](https://www.curseforge.com/minecraft/mc-mods/create-steam-n-rails)
    1b. [Create Deco](https://www.curseforge.com/minecraft/mc-mods/create-deco)
2. [ComputerCraft: Tweaked](https://modrinth.com/mod/cc-tweaked)
    2a. [Advanced Peripherals](https://www.curseforge.com/minecraft/mc-mods/advanced-peripherals)
3. [Tempad](https://www.curseforge.com/minecraft/mc-mods/tempad)
4. [XNet](https://www.curseforge.com/minecraft/mc-mods/xnet)
5. [Flux Networks](https://www.curseforge.com/minecraft/mc-mods/flux-networks)
6. [Project Red: Transmission](https://www.curseforge.com/minecraft/mc-mods/project-red-transmission)
7. [Modular Routers](https://www.curseforge.com/minecraft/mc-mods/modular-routers)
8. [Compact Machines](https://www.curseforge.com/minecraft/mc-mods/compact-machines)
9. [Architect's Palette](https://www.curseforge.com/minecraft/mc-mods/architects-palette)

### Dedicated Server Installation:
1. Download a server.zip file from the releases page.
2. Download the ``47.4.0`` forge installer from [here](https://files.minecraftforge.net/net/minecraftforge/forge/index_1.20.1.html).
3. Create a folder for the server (``mkdir MonifactoryServer``, name doesnt matter)
4. Move the server.zip and forge installer into your server directory. The rest of the guide assumes your current directory is the server directory.
5. Run the forge installer and install the forge server, this can be done with the command ``java -jar TheForgeInstallerName.jar --installServer``
6. ``unzip server.zip``
7. Move the contents of the overrides folder (from server.zip) into the server directory, this can be done with the command ``mv overrides/* .``
8. Use ``./run.sh`` to generate the eula.txt, then again after you accepted run it again to start the server. Modifying the server.properties file to change the port may be neccesary.
9. To upgrade an existing Monifactory server, see See [FAQ.md](FAQ.md).

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## Frequently Asked Questions

See [FAQ.md](FAQ.md)

## Known Issues

See [KNOWN-ISSUES.md](KNOWN-ISSUES.md)
