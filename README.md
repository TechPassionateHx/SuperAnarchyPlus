# SuperAnarchyPlus v1.1

⚔️ **Custom 3-Wave PvE Dungeon (Macstle) & Automated Vote-Based Player Bounty Hunt**
Solving "Gear-Fear" and driving PvP combat in Semi-Anarchy Minecraft.

## 📖 Overview
SuperAnarchyPlus transforms the standard semi-anarchy experience. 
The main goal of this project is to remove the fear of losing gear while actively encouraging high-stakes wilderness combat. 

By providing players with a PvE Dungeon to grind Tier-A loot, they gain the confidence to engage in real fights. Once they are geared up, our **Custom Vote-Based Bounty Hunt System** forces server-wide PvP encounters by allowing the community to put a **Wanted Tag** on players' heads.

---

## 🏰 Feature 1: The Macstle (PvE Dungeon)
**How it Works:**
* **The Spawn:** Players start in a protected WorldSpawn region to prevent spawn-killing. (Giving newbies PvP protection is highly recommended).
* **The Challenge:** Enter the main castle guided by holograms, survive 3 waves of PvE combat, and beat a parkour skill test.
* **The Reward:** Winners enter the Victory Room to collect Tier-A gear (Netherite, Totems, Gaps, XP).
* **Customizable Loot:** You do not need to edit config files to change rewards—simply replace the items in the barrel located inside the Macstle.

---

## 🎯 Feature 2: The Wilderness Bounty Hunt (v1.1)
**How it Works:**
A 100% custom-coded Skript system that turns the wilderness into a hunting ground through democratic chaos.
* **The Vote-Based Hitlist:** Players type `/vhunt` to open a GUI showing all online players and cast a vote on who should be hunted.
* **The Trigger:** Once a player receives **3 votes** from the server, the hunt officially begins! They are marked as `[WANTED]` and glow red. 
* **The Chase:** The target must survive for **30 Minutes**. Every other player on the server receives a Tracker Compass pointing directly to the target's coordinates.
* **The Blood Money:** * If the hunters kill the target, the killer gets **4 Crate Keys** and high-tier survival loot (Ender Pearls, Breeze Rods, Strength Pots).
  * If the target kills a hunter, the target gets **2 Crate Keys** and survival loot to keep fighting.
  * If the target survives the full 30 minutes, they receive the full survival loot drop!
  * Note: **Crate Keys** are tracked as digital Scoreboard points. Players can save these up to exchange for massive real-item rewards in future!*
* **Anti-Abuse & Edge Cases Handled:** * Players who combat log during a hunt receive an automatic 1-hour voting ban.
  * If friends try to abuse the system for free keys, admins can enforce a 48-hour voting ban.
  * Late joiners automatically receive live trackers, and stale compasses are confiscated upon login.

---

## 🛠️ Implementation & Requirements

**📋 Required Versions**
* Minecraft Version: `1.21.11` (Java Edition)
* Server Software: `PaperMC` (Recommended)

**🔌 Required Plugins:**
* **Skript (v2.12.2)** *(Required for the Bounty Hunt)*
* Citizens & CommandNPC
* DecentHolograms
* DeluxeMenus
* WorldGuard & WorldGuardExtraFlags
* EssentialsX, EssentialSpawn, EssentialChat
* PlaceholderAPI

---

## 🛠️ Installation & Setup

Stop your server before making any changes to prevent file corruption!

1. **The World:**
   Upload the `world` folder from this repository to your server's root directory. *(Note: If your main world is not named "world", rename this folder to match your `server.properties` file).*
2. **The Plugins & Scripts:**
   Open the `plugins` folder in this repository. Copy the configuration folders into your server's `/plugins/` directory. 
   
3. **The Jar Files:**
   Ensure you have the `.jar` files for all required plugins installed. 
   *⚠️ Important: Do not copy .jar files from unknown sources; always download the latest official versions from Modrinth, Hangar, or SpigotMC.*
4. **Finalize:**
   Start your server. Use `/dh reload` and `/dm reload` for holograms/menus, and `/sk reload hunt` to initialize the bounty system.

---

## 📜 License
This project is licensed under **CC BY-NC 4.0** (Attribution-NonCommercial).
* You **must** give credit to the original creator.
* You **cannot** sell these files or charge players for access to this dungeon/script.
