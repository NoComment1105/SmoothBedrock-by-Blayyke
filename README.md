# Periodic mod Fabric
![Github license](https://img.shields.io/github/license/NoComment1105/SmoothBedrock-by-Blayyke.svg?label=License)
![Github Issues](https://img.shields.io/github/issues/NoComment1105/SmoothBedrock-by-Blayyke.svg?label=Issues)
![Latest Release](https://img.shields.io/github/v/release/NoComment1105/SmoothBedrock-by-Blayyke?label=Latest%20Release)
[![Discord Chat](https://img.shields.io/badge/Chat%20on-Discord-7289DA)](https://discord.gg/28N2Eeq2tT)
#### Download Counts
[![Github all releases](https://img.shields.io/github/downloads/NoComment1105/SmoothBedrock-by-Blayyke/total.svg?label=Downloads%20From%20GH)](https://GitHub.com/NoComment1105/SmoothBedrock-by-Blayyke/releases/)


Elements from the periodic table in Minecraft >=1.16.2


### What does this Mod do?
This mod changes the bedrock layers in the Overworld and Nether to generate in a perfect *smooth* layer

### The Developers

| Author   | Role   | Links   |
|:---------|:-------|:--------|
| Blayyke | Original Mod | [Original Repo](https://github.com/Blayyke/SmoothBedrockFabric)
| NoComment1105 | Mod Lead | [Contributions](https://github.com/NoComment1105/periodic-mod-fabric/commits?author=NoComment1105) |

### Versioning
This mod is >=1.16.2 at it's oldest. I am **NOT** going to back-port this mod to any older versions
I will try my hardest to updates this mod, in its latest release at the time, within a week the next version
#### If you want earlier versions got to the [original repo](https://github.com/Blayyke/SmoothBedrockFabric) or the [Curseforge page](https://www.curseforge.com/minecraft/mc-mods/blayykes-smooth-bedrock) 

<img src="https://user-images.githubusercontent.com/67918617/115963692-69eefc00-a518-11eb-9a4b-28196a8ea004.png" alt="No Forge" width="225"></a>

----
### Config
these are the config defaults:

`{ // Set to false to make the dimension whitelist act as a blacklist. "isWhitelist": true, /* A list of dimension ids that this mod should filter based on the 'Act as whitelist' setting. Modded dimensionFilter will need to be added here to be affected. */ "dimensionFilter": [ "minecraft:overworld", "minecraft:the_nether" ] }`

If `isWhitelist` is True then anything in `dimensionFilter` will have flat bedrock

If `isWhitelist` is false then anything in `dimensionFilter` will no have flat bedrock

----
#### This part requires some knowledge of coding to use, please move on at your own choice
### Building the mod
To build this mod in its dev version you need to follow some steps to compile it into the .jar Minecraft needs to use this mod. (Windows verison as that is my platform)

#### Requirements
You will need to have a JDK 8 or greater installed on your computer to build my mod. An easy location to acquire one of these is on [AdoptOpenJDK](https://adoptopenjdk.net)

#### Compiling
Find the place where you've cloned the repository and type in the address bar `cmd` to launch Command Prompt. In here you want to type `gradlew build`. If this is your first time building a mod on your computer, Gradle will take a bit longer to set itself up, but after that the mod will build, you will find the resulting `.jar` files in `build/gradle`. Once you have found the folder, you want to drag and drop `smoothbedrock-by-blayyke-X.X.X-SNAPSHOT.jar` into your mods directory and then you're good to go

----

### Issues
If you have discovered an issue with my mod, please do not hesitate to ask anything in my [Discord](https://discord.gg/28N2Eeq2tT) or leave an issue in my [issue tracker](https://www.github.com/NoComment1105/SmoothBedrock-by-Blayyke/issues) but please check for a duplicate of your issue first, thanks :)

### License
SmoothBedrock-by-Blayyke is licensed under GNU LGPLv3, which is a free and open-source license. If you want to know more, poke your nose in the [license file](https://github.com/NoComment1105/SmoothBedrock-by-Blayyke/blob/1.16.x/main/LICENSE)
