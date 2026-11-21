<div align="center">
# ⚔️ Araxia: Shadow of Etheros
 
**A complete retro RPG that fits on a 1.44 MB floppy disk.**
 
![Platform](https://img.shields.io/badge/platform-Windows-blue)
![Language](https://img.shields.io/badge/made%20with-FreeBASIC-orange)
![Size](https://img.shields.io/badge/size-under%201.44%20MB-green)
![License](https://img.shields.io/badge/price-freeware-brightgreen)
 
*Entry in the **1.44 MB Floppy Drive Game Contest** by **2p Arcade Games**, and one that advanced past Round 1.*
 
![Home screen](https://i.ibb.co/sJPWVn6s/Home-Screen.png)
 
</div>
---
 
## The Story
 
In the Fourth Age, the Southeastern Coast has known years of hard-won peace. Then the sea turns foul, the ground begins to tremble, and an old prophecy starts to look like a warning.
 
> *Hush... hush... the black wind sighs.*
> *Doom... doom... beneath dark skies.*
 
**Etheros**, the Lich-Lord of Forgotten Ages, has shattered his chains and his cultists are on the march. You are **Elaxian**, a young resident of the rough harbor slums of Thunder Bay, and you are about to find out that the sailors' tales are true.
 
Raise your strength, gear up, and follow the trail of shadow to the lair of the Master of the Dead.
 
## Screenshots
 
| In-game | In-game |
| :---: | :---: |
| ![Screenshot 1](https://i.ibb.co/93cpBm7V/SS1.png) | ![Screenshot 2](https://i.ibb.co/W4bGnPCW/SS2.png) |
 
<details>
<summary>Contest entry</summary>
![Contest entry](https://i.ibb.co/MzNZ6Gd/COntest.jpg)
 
*Contest entry: made it past Round 1.*
 
</details>
## Features
 
- **A full overworld adventure**: Thunder Bay and its districts, Yellowseed, Turnstead, Balthix and its cemetery, Eversmoke Woods, caves, a lighthouse, the Throllux Temple and finally the lair of Etheros. Over two dozen maps in all.
- **Turn-based combat** against groups of up to three enemies, with attack, run and item options. Around 30 enemy types, from Drowned Rats and Cultists to Basilisks, Rock Golems and Shadow Wraiths, plus boss fights.
- **Leveling to 20**: every level adds +1 Attack and +1 Defense, and tougher foes award more XP.
- **Gear, shops and relics**: buy and sell weapons and armor, stock up on healing potions, herbs and antidotes, and track down five unique relics that boost your stats.
- **Poison and rot**: some enemies poison you on hit. Cure it with an antidote or a night's rest.
- **Bestiary**: defeat five of any monster to unlock its stats.
- **Exploration extras**: search barrels, drink from fountains to heal, fish for coins and rare catches, and take on side quests.
- **Mini-map with fog of war** in dungeon areas.
- **Save anywhere indoors**, with your map progress and bestiary stored too.
- **MIDI soundtrack** with separate town, dungeon, battle and boss themes, played through Windows' built-in MIDI player. No extra DLLs needed.
- **Display options**: fullscreen, 1080p, 720p or 360p, with adjustable music volume and mini-map transparency.
- **Rebindable keys** for Interact, Inventory and Menu.
## Getting Started
 
### Play
 
1. Download the latest release, or clone this repo.
2. Run **`ARAXIA.exe`**. Keep the **`data`** folder right beside it, since the game loads all its maps, sprites, NPC dialogue and music from there.
3. Pick **New Game** and go.
**Requirements:** Windows. The game uses Windows' built-in `winmm` for music, so nothing else needs to be installed.
 
### Controls
 
| Action | Default key |
| :-- | :-- |
| Move | **Arrow keys** |
| Interact / talk / open | **Space** *(rebindable)* |
| Inventory | **I** *(rebindable)* |
| Game menu (items, status, bestiary, save, options) | **Esc** *(rebindable)* |
| Confirm in menus | **Enter** |
| Navigate menus | **Up / Down** (and **Left / Right** for settings) |
| In battle | **A** Fight · **B** Run · **C** Use item |
| Toggle music | **M** |
| Help and hints | **H** or **?** |
| Quit | **Q** |
 
You can change Interact, Inventory and Menu under **Options → Controls**. Settings are saved to `data/settings.cfg`.
 
### Tips for new adventurers
 
- **Save often**, but note that you can only save while **inside a building**.
- Search every barrel. Some hide gold, potions or junk.
- Fountains heal 5 HP, free and at any time.
- Face the water to fish, then sell your catch at any shop.
- Carry antidotes before heading into poison-heavy areas.
- Check the in-game **Help/Info** screen for the full dictionary and hints.
## Building from Source
 
The whole game is a single FreeBASIC source file, `ARAXIA.BAS`.
 
1. Install [FreeBASIC](https://www.freebasic.net/) (default location `C:\FreeBASIC`).
2. Run **`build.bat`**. It uses `fbc64.exe`, or falls back to `fbc32.exe`.
Or compile by hand:
 
```
fbc -lang fblite -s gui ARAXIA.BAS
```
 
Keep the `data\` folder next to the resulting `ARAXIA.exe`.
 
## Project Layout
 
```
ARAXIA.BAS      Game source (FreeBASIC, ~3,900 lines)
ARAXIA.exe      Prebuilt Windows executable
build.bat       Build script
data/
 ├─ *.MAP       World maps
 ├─ *.MDT       Tile and sprite graphics
 ├─ *.NPC/.npcs NPC dialogue and signs
 ├─ ENEMY.DAT   Enemy stats
 ├─ NMEDIA.PAL  Color palette
 ├─ *.mid       Music
 └─ settings.cfg
```
 
## The Floppy Challenge
 
The contest rule was simple: the entire game had to fit on a 1.44 MB floppy disk. Araxia comes in at roughly **0.7 MB uncompressed** (about 0.3 MB zipped), executable included, which leaves plenty of room to spare.
 
## Contest Milestone
 
Advanced past **Round 1** of the 2p Arcade Games 1.44 MB Floppy Drive Game Contest. 🏆
 
## Credits
 
- **Story, scripts, maps and NPCs:** Eric "Manmadedrummer" Gates
- **Graphics:** Daniel Wilfong and Jocke The Beast, with some custom art by Eric Gates
- **Music:** royalty-free MIDI from various sources, with some tracks by Eric Gates
## License
 
Araxia Games, freeware.
 
---
 
<div align="center">
Made by [Manmadedrummer](https://github.com/Manmadedrummer)
 
</div>
 
