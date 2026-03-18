# SuperAnarchyPlus
# ⚔️ Custom 3-Wave PvE Dungeon (Macstle)
### *Solving "Gear-Fear" in Semi-Anarchy Minecraft*

## 📖 Overview
This is a custom 3-wave PvE dungeon designed specifically for **Semi-Anarchy Minecraft Servers**. 

The main goal of this project is to **remove the fear of losing gear**. By providing winners with **Tier-A loot**, players gain the capability to engage in real anarchy fights and high-stakes battles without worrying about losing hours of grinding. This allows players **to extract the real fun of anarchy—combat and conquest**.

## 🕹️ How it Works
1. **The Spawn:** Players start in a protected WorldSpawn region to prevent spawn-killing. From there, they can grind for basic gear. (Giving newbies PvP protection is highly recommended).
2. **The Mactsle:** Players enter the main castle guided by holograms.
3. **The Challenge:** Survive 3 waves of PvE combat followed by a parkour skill test.
4. **The Reward:** Winners enter the **Victory Room** to collect Tier-A gear (Netherite, Totems, Gaps, XP).
5. **The Wilderness:** Players leave the dungeon fully equipped to dominate the anarchy wilderness.

## 🎁 Customizable Loot
The loot is fully customizable inside the game. You do not need to edit config files to change the rewards—simply **replace the items in the barrel** located inside the **Macstle**.

**Pre-configured loot includes:**
* 12 Netherite Sets & Tools
* Swords, Axes, Bows, Crossbows, and 4 Shields
* 27 Stacks of Golden Apples (Gaps)
* Totems of Undying, Arrows, and XP Bottles

## 🛠️ Implementation & Requirements
### 📋 Required Versions
* **Minecraft Version:** `1.21.11` (Java Edition)
* **Server Software:** [PaperMC](https://papermc.io/) (Recommended)
### Required Plugins:
* **Citizens & CommandNPC**
* **DecentHolograms**
* **DeluxeMenus**
* **WorldGuard & WorldGuardExtraFlags**
* **EssentialsX,EssentialSpawn,EssentialChat**
* **PlaceholderAPI**

## 🛠️ Installation & Setup
Follow these steps to install the **Macstle** on your server:

1. **Stop your server** before making any any changes to prevent file corruption.
2. **The World:**
   * Upload the `world` folder from this repository to your server's root directory.
   * > **Note:** If your main world is not named "world", rename this folder to match the `level-name` in your `server.properties` file.
3. **The Plugins:**
   * Open the `plugins` folder in this repository.
   * Copy the configuration folders (e.g., `DecentHolograms`, `Citizens`, `DeluxeMenus`) into your server's `/plugins/` directory.
4. **The Jar Files:**
   * Ensure you have the `.jar` files for all required plugins installed. 
   * **⚠️ Important:** Do not copy `.jar` files from unknown sources; always download the latest official versions from **Modrinth**, **Hangar**, or **SpigotMC**.
5. **Finalize:**
   * Start your server.
   * Use `/dh reload` and `/dm reload` to initialize the dungeon holograms and menus.

## 📜 License
This project is licensed under **CC BY-NC 4.0** (Attribution-NonCommercial). 
* You **must** give credit to the original creator.
* You **cannot** sell these files or charge players for access to this dungeon.
