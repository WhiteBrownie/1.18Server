# 1.18Server 
[Server Backups](https://1drv.ms/u/s!AnRpVm46qqDNjdUxbNgz45vrc8yFAg?e=peDNs2)
---
# To get up and running clientside
1. Go ahead and download [MultiMC](https://multimc.org/)
2. Extract MultiMC into a location of your choosing, it will stay there, no installation required
3. Download the MultiMC instance you want/need from [here](https://1drv.ms/u/s!AnRpVm46qqDNjdUy9MNKb798AQLBOg?e=OeDgn7) (most current version: `1.17.1 FABRIC_091121_2.7z`)
4. Extract the .7z file so that you are left with a .zip file (use the provided password)
5. Open up MultiMC (locate the MultiMC.exe inside of the MultiMC folder you extraced and double click it; you can add this to your Windows Start Menu by right clicking on it) and click on `Add Instance` in the top left corner
6. Click `Import from zip`. Use the .zip file you extracted in step 4. (if you don't provide a name yourself it will be set automatically)
7. In MultiMC on the top right corner click on `Profiles` and then on `Manage Accounts`
	7.1. In the new `Settings` window that opened, add you Minecraft Account via Microsoft or Mojang (see the right side)
	7.2. Click on the Account you just added and press `Set Default` on the right side
	7.3. You can close the Settings window
8. You're good to go, just double click on the instance in MultiMC to start up Minecraft
---
# Current state (1.17.1)
## Server side implemented:
### Optimization:
* [A number of optimization mods from this comprehensive list](https://gist.github.com/Obydux/55b967f5dcc00633fe895e5a473363d5)
* [Servercore](https://modrinth.com/mod/servercore)
### Voice Chat
* [Simple Voice Chat](https://www.curseforge.com/minecraft/mc-mods/simple-voice-chat)
### Discord Chat integration (Discord Chat integration is up for discussion in general)
* [DisFabric](https://www.curseforge.com/minecraft/mc-mods/disfabric)
### Visual
* [Glow banners](https://www.curseforge.com/minecraft/mc-mods/glow-banners) (make glowing banners and item frames with new glowing squid mob drop)
### QOL
* [Carpet](https://www.curseforge.com/minecraft/mc-mods/carpet) (optimizations and stuff)
* [Appleskin](https://www.curseforge.com/minecraft/mc-mods/appleskin) (advanced food information)
* Vanilla Tweaks
	* timber
	* villager death messages
	* silence mobs
	* redstone rotation wrench
	* player head drops
	* durability ping
	* track raw statistics
	* track statistics
	* graves
	* multiplayer sleep
	* fast leaf decay
	* afk display
	* unlock all recipes 
	* [Link to everything above](https://vanillatweaks.net/share#AT7Z00)
* [Baila](https://github.com/TheEpicBlock/baila) ('What Am I Looking AT' UI)
* *%UP FOR DISCUSSION* [Suitably stackable stews](https://www.curseforge.com/minecraft/mc-mods/suitably-stackable-stew) (does what it says)
* *%UP FOR DISCUSSION* [Monsters in the closet](https://www.curseforge.com/minecraft/mc-mods/monsters-in-the-closet) (see monsters that keep you your hard earned sleep)
* *%UP FOR DISCUSSION* [Inventory sorting](https://www.curseforge.com/minecraft/mc-mods/inventory-sorting) (does what it says)
* *%UP FOR DISCUSSION* [Better signs and frames](https://www.curseforge.com/minecraft/mc-mods/better-signs-and-frames) (does what it says)
* *%NOT WORKING*, won't be implemented [Playtime tracker](https://github.com/SpaceClouds42/PlaytimeTracker) (does what it says)
* *%NOT WORKING*, won't be implemented [Fabric Kotlin](https://www.curseforge.com/minecraft/mc-mods/fabric-language-kotlin) (needed for PlaytimeTracker)
---
## Client side implemented:
* Fabric
* Fabric API
* [Architectury API](https://www.curseforge.com/minecraft/mc-mods/architectury-fabric) (dependency)
* [Modmenu](https://www.curseforge.com/minecraft/mc-mods/modmenu) (mod menu, access settings for various installed mods)
* [Simple voice chat](https://www.curseforge.com/minecraft/mc-mods/simple-voice-chat) (voice chat)
* [LambDynamicLights](https://www.curseforge.com/minecraft/mc-mods/lambdynamiclights) (dynamic light)
* [Irisshaders](https://www.curseforge.com/minecraft/mc-mods/irisshaders) (shader and performance
* [Not enough animations](https://www.curseforge.com/minecraft/mc-mods/not-enough-animations) (animations)
  *  [Transliterationlib](https://www.curseforge.com/minecraft/mc-mods/transliterationlib) (compatability layer for NOA)
* [Couplings](https://www.curseforge.com/minecraft/mc-mods/couplings) (doors, trapdoors, etc. get coupled and can be opened by one click)
* [Appleskin](https://www.curseforge.com/minecraft/mc-mods/appleskin) (advanced food information)
* [Chat Heads](https://www.curseforge.com/minecraft/mc-mods/chat-heads) (show player skin heads shown in chat)
  * [Cloth Config API](https://www.curseforge.com/minecraft/mc-mods/cloth-config) (dependency for Chat Heads)
* [Nearly Sighted](https://www.curseforge.com/minecraft/mc-mods/near-sightedly) (match view distance of PC configuration to server)
* [Eating animation fabric](https://www.curseforge.com/minecraft/mc-mods/eating-animation-fabric) (more/better eating animations)
* [Glow banners](https://www.curseforge.com/minecraft/mc-mods/glow-banners) (make glowing banners and item frames with new glowing squid mob drop)
* *NOT CONFIRMED WORKING YET* [skins layers 3d](https://www.curseforge.com/minecraft/mc-mods/skin-layers-3d) (3D skins)
* [Continuity](https://www.curseforge.com/minecraft/mc-mods/continuity) (Connected textures fix)
* [Enhanced block entities](https://www.curseforge.com/minecraft/mc-mods/enhanced-block-entities) (performance optimization for chests, beds, etc.)
---
# Up for discussion:
* [Multiworld fabric](https://www.curseforge.com/minecraft/mc-mods/multiworld-fabric) (create and teleport between multiple worlds, might be useful for a farmworld or something similar)
* Either **one**:
	* [Right click harvest](https://modrinth.com/mod/rch) (does what it says)
	* [Replanting crops fabric](https://www.curseforge.com/minecraft/mc-mods/replanting-crops-fabric) (does what it says)
* [Fluid physics](https://www.curseforge.com/minecraft/mc-mods/fluid-physics) (does what it says, you can build actual pumps with pistons and stuff)
* [Repurposed structures](https://www.curseforge.com/minecraft/mc-mods/repurposed-structures) (does what it says)
* Any **one** of these:
	* [Leukocyte](https://github.com/NucleoidMC/leukocyte) (world/land protection mod based on roles)
	  * [Player roles](https://github.com/NucleoidMC/player-roles) (dependency for leukocyte)
	* [Flan](https://github.com/Flemmli97/Flan) (land clamining mod, subclaims are possible)
	* [Factions](https://github.com/ickerio/factions) (factions mod, you will have to figth other factions for land claims and sustain a certain 'power level' to keep up the claims)
	* [Sewing machine utilities](https://www.curseforge.com/minecraft/mc-mods/sewing-machine-utilities) (extensive factions mod for claiming land, battles, currency, shops, ...; pretty much endless possiblities)
* [Conditional keep inventory](https://www.curseforge.com/minecraft/mc-mods/conditional-keep-inventory) (keep inventory only when dying in lava or by suffocating,...)
* [Egg of capitalism](https://modrinth.com/mod/egg-of-capitalism) (every player that helped to kill the Ender Dragon for the first time gets an egg)
* [Easy painter](https://github.com/aws404/easy-painter) (improved paintings)
* [Horse Stonks](https://www.curseforge.com/minecraft/mc-mods/horse-stonks) (prevents animals from getting worse stats than their parents when breeding)
* [Interdimensional map markers](https://www.curseforge.com/minecraft/mc-mods/interdimensional-map-markers) (make your overworld position on vanilla minecraft maps visible even when in other dimensions)
* [Lenient stack size](https://www.curseforge.com/minecraft/mc-mods/lenient-stack-size) ([bigger] stacks for books, snowballs, buckets, ...)
* Either one or both:
	* [Antique Atlas](https://www.curseforge.com/minecraft/mc-mods/antique-atlas) (craftable map with nice artstyle)
	* [Xaeros minimap](https://www.curseforge.com/minecraft/mc-mods/xaeros-minimap)  (does what it says)
* Vanilla Tweks additions:
	* possible to add: 
	* Anti Mob Grief
	* XP Management
	* Chunk Loaders
	* [Link to VanillaTweaks with everything already implemented plus everything above](https://vanillatweaks.net/share#AT7Z00)
	* possibly more?
* Either **one**:
	* [Biome Locator](https://www.curseforge.com/minecraft/mc-mods/biome-locator) (compass for locating biomes)
		* [FlytreLib](https://www.curseforge.com/minecraft/mc-mods/lib) (dependency for Biome locator)
	* [Natures compass](https://www.curseforge.com/minecraft/mc-mods/natures-compass)  (does what it says)
---

