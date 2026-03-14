
  # ETERNAL DOOM

  *A frenetic top-down shooter where you take on the Slayer's unending fight against the forces of hell.*

Survive as long as possible by fending off endless waves of demons from the depths of hell. You'll be provided with some of the most lethal and iconic weapons from the franchise to aid in your crusade against unique hellborn monstrosities, each possessing different abilities and archetypes.

The game is an arcade-style, top-down spin on the established *Doom* formula, developed in C++ using the SFML graphics library. This project is built upon a robust Object-Oriented architecture, implementing a custom Entity Management System, dynamic enemy AI tracking, procedural loot generation, and fluid 360-degree mouse-aim combat mechanics.

[![Eternal Doom Gameplay](https://img.youtube.com/vi/xh_VsYCisdw/maxresdefault.jpg)](https://youtu.be/xh_VsYCisdw)
## ✨ Key Features

* **Entity Management System:** A robust Object-Oriented Programming (OOP) architecture that efficiently handles the lifecycle of all game entities (Player, Enemies, Projectiles, Pickups). Updating and rendering are centralized.
* **Dynamic Enemy AI:** Enemies possess unique abilities and specific tracking/attacking behaviors, relentlessly focusing on eliminating the player.
* **Complex Arsenal System:** Equip iconic weapons (Plasma Rifle, Rocket Launcher, Chaingun, BFG9000), each featuring distinct firing mechanics, projectile types, fire rates, and ammo consumption.
* **Custom Sprite Animation Engine:** A delta-time-based animation system that dynamically binds frames to entity states. It is specifically tailored to faithfully imitate the iconic visual feedback and retro animation pacing of the original *Doom* source material.
* **Mouse-Aim Combat:** Precision 360-degree shooting directed exactly at the cursor's coordinates.
* **Procedural Loot & Pickups:** Upon death, enemies have a calculated chance to drop between 0 and 3 pickups (Health, Armor, Ammo) to reward aggressive play and keep the combat flow engaging.
* **Game State Manager:** Seamless handling of game states, ensuring smooth transitions between the Main Menu, Active Gameplay, Pause Menu, and Game Over screen.
* **Integrated Audio System:** Real-time, independent control over the dynamic soundtrack and sound effects (SFX).

## 🎮 Gameplay Mechanics

* **The Player:** Spawns with full health, full armor, and maximum ammo for each weapon. Movement is constrained within the game window. The primary goal is to survive and rack up the highest score possible.
* **The Enemies:** Different enemy types yield varying points upon being killed, reflecting their threat level and abilities. They will attempt to eliminate the player making use of their abilities.
* **Game Over Condition:** The run ends when the player's health reaches 0. The final screen displays the total score achieved and offers the option to restart the crusade or exit to the desktop.

## 📥 How to Download & Play

1. Navigate to the **[Releases](../../releases)** tab on the right side of this repository.
2. Download the latest `.zip` archive for your operating system.
3. Extract the contents to a folder of your choice.
4. Run the executable file to start the game.
5. RIP AND TEAR

## ⌨️ Controls

### 🕹️ Menus
* `ENTER` - Start the game (Main Menu) / Restart the game (Game Over)
* `P` - Pause / Unpause the game
* `ESC` - Exit the game (Game Over)

### 🏃 Movement
* `W` - Move Up
* `A` - Move Left
* `S` - Move Down
* `D` - Move Right

### 🔫 Combat & Arsenal
* `LEFT MOUSE BUTTON` - Shoot (fires towards the cursor's position)
* `1` - Equip Plasma Rifle
* `2` - Equip Rocket Launcher
* `3` - Equip Chaingun
* `4` - Equip BFG9000

### 🎵 Audio Control
* `M` - Toggle music On/Off
* `-` (Minus) - Lower music volume
* `=` (Equal) - Raise music volume

## 💻 Technologies Used

* **C++** - Core programming language.
* **[CMake](https://github.com/Kitware/CMake/tree/master))** - Cross-platform build system utilized to configure the project, manage dependencies, and streamline the compilation process.
* **[SFML 3.0.0](https://github.com/SFML/SFML/tree/3.0.0)** (Zlib) - Simple and Fast Multimedia Library used for rendering, window management, and input.
* **[OpenAL](https://openal-soft.org/)** (LGPL) - Audio library (distributed as a shared library due to licensing).

## 🎨 Credits & Resources

While the codebase and logic are my own, this project utilizes community resources that I have edited and adapted (recoloring, resizing, etc.) to fit the game's vision. 
*Note: The image `chaingun_proj2.png` is my own creation.*

### Graphics & Textures
* **Main Sprite Database:** [Spriters Resource - Doom & Doom II](https://www.spriters-resource.com/ms_dos/doomdoomii/)
* **Secondary Sprite Database:** [Sprite Database - Doom](https://spritedatabase.net/game/760)
* **Main Menu Background:** [Reddit - Doom 1993 Upscaled](https://www.reddit.com/r/Doom/comments/g5tzyz/doom_1993_wallpaper_upscaled_to_4k_by_telamon618/)
* **Pause Screen Background:** [AlphaCoders Wallpaper](https://wall.alphacoders.com/big.php?i=1316641)
* **In-Game Background:** Generated by me using original textures from [Textures Resource](https://www.textures-resource.com/ms_dos/doom/texture/2236/).

### Audio
* **Pickup SFX:** [Half-Life Health Charger](https://www.myinstants.com/en/instant/half-life-health-charger-sound-9722/)
* **Doom II SFX Archive:** [Sounds Resource](https://www.sounds-resource.com/ms_dos/doomdoomii/sound/7956/)
* **Music:** Soundtrack by **RTPN** ([Official YouTube Channel](https://www.youtube.com/c/RTPNOfficial)).
    * Tracks used: *[ClownIsWe](https://youtu.be/O_t53q1vq04)*, *[Release](https://youtu.be/9eluFZIpmOs)*, *[Decay](https://youtu.be/kK2k_W0nKdE)*, *[Sustain](https://youtu.be/Si1Uw_nmjMk)*, *[Hive](https://youtu.be/u2lNDShmM-k)*, *[Uprizing I](https://youtu.be/-y_5KVimqxI)*.

### Fonts
* **Amazdoom:** Available on [DaFont](https://www.dafont.com/amazdoom.font)
