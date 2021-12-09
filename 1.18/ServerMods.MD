# Serverside Modlist

### Using fabric as the underlying modding toolchain
* [Fabric](https://fabricmc.net/)
* [Fabric API](https://www.curseforge.com/minecraft/mc-mods/fabric-api)
## Implemented
### Performance
* [Carpet](https://www.curseforge.com/minecraft/mc-mods/carpet/files/all) (general improvements for performance, QOL, etc., - with options for gameplay changing stuff as well)
* [Carpet Extra](https://www.curseforge.com/minecraft/mc-mods/carpet-extra/files/all) (more carpet)
* [Carpet TIS Addition](https://github.com/TISUnion/Carpet-TIS-Addition/releases) (even more carpet)
* [Chunky Pregenerator](https://www.curseforge.com/minecraft/mc-mods/chunky-pregenerator) (chunk pre-generation to reduce lag from movement)
* [DimensionalThreading](https://github.com/WearBlackAllDay/DimensionalThreading) (assign dimensions different threads)
* [FerriteCore](https://www.curseforge.com/minecraft/mc-mods/ferritecore-fabric) (reduce memory usage)
* [Hydrogen](https://github.com/jellysquid3/hydrogen-fabric/releases) (reduce memory usage)
* [Krypton](https://github.com/astei/krypton/releases) (optimized networking and entity tracking)
* [LazyDFU](https://www.curseforge.com/minecraft/mc-mods/lazydfu) (initilization optimization)
* [Lithium](https://www.curseforge.com/minecraft/mc-mods/lithium/files/all) (holistic performance improvement mod)
* [Phosphor](https://github.com/CaffeineMC/phosphor-fabric) (light engine rework for better performance, esp. CPU)
* [Servercore](https://modrinth.com/mod/servercore) (performance options and optimizations for Minecraft servers)
* [Spark](https://ci.lucko.me/job/spark/) (performance profiling of the server)
### GUI, HUD and interactions
* [AppleSkin](https://www.curseforge.com/minecraft/mc-mods/appleskin) (food information GUI with animations)
* [Dynmapp](https://github.com/webbukkit/dynmap) (adds a dynamic worldmap, viewable from a browser)
* [MiniMOTD](https://www.curseforge.com/minecraft/mc-mods/minimotd-fabric) (better MOTD)
### Textures, animations, skins, visual block-addition, ...
* [Better signs and frames](https://www.curseforge.com/minecraft/mc-mods/better-signs-and-frames) (does what it says)
* [Glow banners](https://www.curseforge.com/minecraft/mc-mods/glow-banners) (make glowing banners and item frames with new glowing squid mob drop)
### Social
* [Simple voice chat](https://www.curseforge.com/minecraft/mc-mods/simple-voice-chat) (voice chat)
### QOL
* [Lenient stack size](https://www.curseforge.com/minecraft/mc-mods/lenient-stack-size) ([bigger] stacks for books, snowballs, buckets, stews ...) **modify to not allow bed stacking**
* [Quick Shulker](https://www.curseforge.com/minecraft/mc-mods/quick-shulker) (better access to shulker box)
* [Rightclickharvest Fabric](https://www.curseforge.com/minecraft/mc-mods/rightclickharvest-fabric) (does what it says)
* [Tree harvester (Fabric)](https://www.curseforge.com/minecraft/mc-mods/tree-harvester-fabric) (timber mod)
* [Universal Graves](https://modrinth.com/mod/universal-graves) (graves mod)
  * in the indium configuration file `mixin.chunk.palette=false` has to be set in order to avoid a crash and render bug (see [isssue](https://github.com/Patbox/UniversalGraves/issues/30))
* [VanillaTweaks](https://vanillatweaks.net/share#rUoss6) **(fast leaf decay might not be needed with timber mod)**
  * AFK Display
  * Armore Statues
  * Back
  * Cauldron Concrete
  * Count Mob Deaths
  * Custom Nether Portals
  * Double Shulker Shells
  * Fast Leaf Decay [removed, not needed any more becazse of [Tree Harvester]((https://www.curseforge.com/minecraft/mc-mods/tree-harvester-fabric))]
  * Kill Empty Boats
  * More Mob Heads
  * Nether Portal Coords
  * Player Head Drops
  * Silence Mobs
  * Track Raw Statistics
  * Track Statisctics
  * Unlock All Recepies
  * Villager Death Messages
  * Villager Workstation Highlights
  * Wandering Trades
  * XP Management
  * Back to Blocks
  * Craftable Bundles (Rabbit Hide)
  * Craftable Bundles (Leather)
### World generation
* [Repurposed structures (Fabric)](https://www.curseforge.com/minecraft/mc-mods/repurposed-structures-fabric)
### Administration
* [LuckyPerms](https://luckperms.net/) (Permissions mod)
### Dependencies
* [Cloth Config API (Fabric)](https://www.curseforge.com/minecraft/mc-mods/cloth-config/)
* [Collective (Fabric)](https://www.curseforge.com/minecraft/mc-mods/collective-fabric)

## Startup flags
-Dterminal.jline=false -Dterminal.ansi=true -XX:+UseG1GC -XX:+ParallelRefProcEnabled -XX:MaxGCPauseMillis=200 -XX:+UnlockExperimentalVMOptions -XX:+DisableExplicitGC -XX:+AlwaysPreTouch -XX:G1NewSizePercent=30 -XX:G1MaxNewSizePercent=40 -XX:G1HeapRegionSize=8M -XX:G1ReservePercent=20 -XX:G1HeapWastePercent=5 -XX:G1MixedGCCountTarget=4 -XX:InitiatingHeapOccupancyPercent=15 -XX:G1MixedGCLiveThresholdPercent=90 -XX:G1RSetUpdatingPauseTimePercent=5 -XX:SurvivorRatio=32 -XX:+PerfDisableSharedMem -XX:MaxTenuringThreshold=1 -Dusing.aikars.flags=https://mcflags.emc.gs/ -Daikars.new.flags=true

## Deprecated
* [DisFabric](https://www.curseforge.com/minecraft/mc-mods/disfabric) (Discord chat integration)
* [Replanting crops fabric](https://www.curseforge.com/minecraft/mc-mods/replanting-crops-fabric) (right-click replanting)
