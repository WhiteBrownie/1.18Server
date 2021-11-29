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



### Social
* [Simple Voice Chat](https://www.curseforge.com/minecraft/mc-mods/simple-voice-chat)

### QOL


## To be implemented
### startup flags
-Dterminal.jline=false -Dterminal.ansi=true -XX:+UseG1GC -XX:+ParallelRefProcEnabled -XX:MaxGCPauseMillis=200 -XX:+UnlockExperimentalVMOptions -XX:+DisableExplicitGC -XX:+AlwaysPreTouch -XX:G1NewSizePercent=30 -XX:G1MaxNewSizePercent=40 -XX:G1HeapRegionSize=8M -XX:G1ReservePercent=20 -XX:G1HeapWastePercent=5 -XX:G1MixedGCCountTarget=4 -XX:InitiatingHeapOccupancyPercent=15 -XX:G1MixedGCLiveThresholdPercent=90 -XX:G1RSetUpdatingPauseTimePercent=5 -XX:SurvivorRatio=32 -XX:+PerfDisableSharedMem -XX:MaxTenuringThreshold=1 -Dusing.aikars.flags=https://mcflags.emc.gs/ -Daikars.new.flags=true

* [Lithium](https://www.curseforge.com/minecraft/mc-mods/lithium/files/all) (holistic performance improvement mod)
* [Starlight](https://github.com/spottedleaf/starlight/releases) (better light engine)
* [DimensionalThreading](https://github.com/WearBlackAllDay/DimensionalThreading) (assign dimensions different threads)
* [Hydrogen](https://github.com/jellysquid3/hydrogen-fabric/releases) (reduce memory usage)
* [FerriteCore](https://www.curseforge.com/minecraft/mc-mods/ferritecore-fabric) (reduce memory usage)
* [Recipe Cache](https://www.curseforge.com/minecraft/mc-mods/recipe-cache) (caches recepies to reduce lag)
* [Krypton](https://github.com/astei/krypton/releases) (optimized networking and entity tracking)
* [LazyDFU](https://modrinth.com/mod/lazydfu) (improves server-startup time)
* [Carpet Extra](https://www.curseforge.com/minecraft/mc-mods/carpet-extra/files/all) (more carpet)
* [Carpet TIS Addition](https://github.com/TISUnion/Carpet-TIS-Addition/releases) (even more carpet)
### Social
* [DisFabric](https://www.curseforge.com/minecraft/mc-mods/disfabric)
### QOL


## To be discussed
### Performance
### Social
### QOL
[page up](https://github.com/WhiteBrownie/1.18Server/tree/main/1.18-rc3)



