# Serverside Modlist

### Using fabric as the underlying modding toolchain
* [Fabric](https://fabricmc.net/)
* [Fabric API](https://www.curseforge.com/minecraft/mc-mods/fabric-api)


## Implemented
### Performance
* [Servercore](https://modrinth.com/mod/servercore) (performance options and optimizations for Minecraft servers)
* [Carpet](https://www.curseforge.com/minecraft/mc-mods/carpet/files/all) (general improvements for performance, QOL, etc., - with options for gameplay changing stuff as well)
* [Chunky Pregenerator](https://www.curseforge.com/minecraft/mc-mods/chunky-pregenerator) (chunk pre-generation to reduce lag from movement)
* [Spark](https://ci.lucko.me/job/spark/) (performance profiling of the server)
### GUI, HUD and interactions
## Textures, animations, skins, ...
* [Easy painter](https://github.com/aws404/easy-painter) (improved paintings)
* [Better signs and frames](https://www.curseforge.com/minecraft/mc-mods/better-signs-and-frames) (does what it says)
### Social
* [Simple voice chat](https://www.curseforge.com/minecraft/mc-mods/simple-voice-chat) (voice chat)
### QOL


## To be implemented
### startup flags
-Dterminal.jline=false -Dterminal.ansi=true -XX:+UseG1GC -XX:+ParallelRefProcEnabled -XX:MaxGCPauseMillis=200 -XX:+UnlockExperimentalVMOptions -XX:+DisableExplicitGC -XX:+AlwaysPreTouch -XX:G1NewSizePercent=30 -XX:G1MaxNewSizePercent=40 -XX:G1HeapRegionSize=8M -XX:G1ReservePercent=20 -XX:G1HeapWastePercent=5 -XX:G1MixedGCCountTarget=4 -XX:InitiatingHeapOccupancyPercent=15 -XX:G1MixedGCLiveThresholdPercent=90 -XX:G1RSetUpdatingPauseTimePercent=5 -XX:SurvivorRatio=32 -XX:+PerfDisableSharedMem -XX:MaxTenuringThreshold=1 -Dusing.aikars.flags=https://mcflags.emc.gs/ -Daikars.new.flags=true
### Performance 
* [Lithium](https://www.curseforge.com/minecraft/mc-mods/lithium/files/all) (holistic performance improvement mod)
* [Starlight](https://github.com/spottedleaf/starlight/releases) (better light engine)
* [DimensionalThreading](https://github.com/WearBlackAllDay/DimensionalThreading) (assign dimensions different threads)
* [Hydrogen](https://github.com/jellysquid3/hydrogen-fabric/releases) (reduce memory usage)
* [FerriteCore](https://www.curseforge.com/minecraft/mc-mods/ferritecore-fabric) (reduce memory usage)
* [Recipe Cache](https://www.curseforge.com/minecraft/mc-mods/recipe-cache) (caches recepies to reduce lag)
* [Krypton](https://github.com/astei/krypton/releases) (optimized networking and entity tracking)
* [LazyDFU](https://www.curseforge.com/minecraft/mc-mods/lazydfu) (initilization optimization)
* [Carpet Extra](https://www.curseforge.com/minecraft/mc-mods/carpet-extra/files/all) (more carpet)
* [Carpet TIS Addition](https://github.com/TISUnion/Carpet-TIS-Addition/releases) (even more carpet)
### Social
* [DisFabric](https://www.curseforge.com/minecraft/mc-mods/disfabric)
### GUI, HUD and interactions
* [Baila](https://github.com/TheEpicBlock/baila) ('What Am I Looking AT' UI)
### Textures, animations, skins, ...
* [Glow banners](https://www.curseforge.com/minecraft/mc-mods/glow-banners) (make glowing banners and item frames with new glowing squid mob drop)
### QOL
* [Appleskin](https://www.curseforge.com/minecraft/mc-mods/appleskin) (advanced food information)
* [Monsters in the closet](https://www.curseforge.com/minecraft/mc-mods/monsters-in-the-closet) (see monsters that keep you your hard earned sleep)
* Either **one**:
	* [Suitably stackable stews](https://www.curseforge.com/minecraft/mc-mods/suitably-stackable-stew) (does what it says)
	* [Lenient stack size](https://www.curseforge.com/minecraft/mc-mods/lenient-stack-size) ([bigger] stacks for books, snowballs, buckets, stews ...) [modify to not allow bed stacking]
* Either **one**:
	* [Right click harvest](https://modrinth.com/mod/rch) (does what it says)
	* [Replanting crops fabric](https://www.curseforge.com/minecraft/mc-mods/replanting-crops-fabric) (does what it says)
* Either **one**:
    * [Biome Locator](https://www.curseforge.com/minecraft/mc-mods/biome-locator) (compass for locating biomes)
		* [FlytreLib](https://www.curseforge.com/minecraft/mc-mods/lib) (dependency for Biome locator)
	* [Natures compass](https://www.curseforge.com/minecraft/mc-mods/natures-compass)  (does what it says)
* [Horse Stonks](https://www.curseforge.com/minecraft/mc-mods/horse-stonks) (prevents animals from getting worse stats than their parents when breeding)
* [Egg of capitalism](https://modrinth.com/mod/egg-of-capitalism) (every player that helped to kill the Ender Dragon for the first time gets an egg)
* VanillaTweaks (fast leaf decay is not needed any more) ![image](https://i.imgur.com/V1hbJfw.png) 
* [Trees do not float](https://www.curseforge.com/minecraft/mc-mods/trees-do-not-float) (timber and tree optimization)
### potentially game-changing
* [Repurposed structures (Fabric)](https://www.curseforge.com/minecraft/mc-mods/repurposed-structures-fabric) (does what it says) [Deepwolf will have to modify this one]
* [Universal Graves](https://modrinth.com/mod/universal-graves)
# stuff to look at
* Elytra! (might not be looked at afterall because of server performance reasons)
* anti mob block grief: [Damage Incroporated](https://modrinth.com/mod/damage-incorporated) or [Environmental Creepers](https://www.curseforge.com/minecraft/mc-mods/environmental-creepers)

[page up](https://github.com/WhiteBrownie/1.18Server/tree/main/1.18-rc4)
