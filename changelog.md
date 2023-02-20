# Changelog
All changes to Grindergard Revolution will be documented in this file. The format is informed by [Keep a Changelog](http://keepachangelog.com/en/1.0.0/). Version number structuring is inspired by [Semantic Versioning](https://semver.org/spec/v2.0.0.html) and can be read as follows: MAJOR.MINOR.PATCH(HOTFIX)

Major and Minor updates and Patches are all declared with ascending whole numbers, and Hotfixes are declared with ascending alphabetical characters. Major updates add gameplay features or otherwise significantly effect the experience of play and are not compatible with clients/servers of differing versions. Minor updates contain fixes and changes that are not compatible with clients/servers of differing versions. Patches contain fixes and changes that are significant but are intercompatible with clients/servers running packs of the same major and minor version. Hotfixes include only minor fixes and are intercompatible with clients/servers running packs of the same major and minor version, and these changes are included in the event of a subsequent patch.


*Example:* v1.2.0a *indicates a hotfix for the 1st major version with its 2nd minor update before any patches.*
| Features| Major | Minor | Patch | Hotfix
|------------------------------|-------|-------|-------|---|
| Intercompatible        | x     | x     | ✓     | ✓ |
| Incremented in whole numbers | ✓     | ✓     | ✓     | x |
| Incremented with letters       | x     | x     | x     | ✓

## RELEASE v1.0.0
### Changes (2023-02-18, 1676749320 Unix Time):
- **[Added]** Dot Coin Mod. Currency drops from piglin brutes and certain bosses, but currently have no mechanical use. Server owners are encouraged to implement a villager shop trading platinum for Simply Swords' unique weapons.
- **[Added]** LootJS. This is doing some backend work for mob drops.
- **[Added]** Menu panorama.
- **[Added]** A patchouli book for the official GR server. It doesn't have a crafting recipe and is written with the GR server in mind, but it does contain useful information on some interfaces. You can obtain it through cheat mode in JEI or through the creative menu, but it's not included in starter loot by default.
<br></br>
- **[Updated]** Architectury.
- **[Updated]** The Bumblezone & its configs.
- **[Updated]** Chalk.
- **[Updated]** Collective.
- **[Updated]** CraftTweaker.
- **[Updated]** Create: Steam 'n Rails & its configs.
- **[Updated]** JourneyMap.
- **[Updated]** Kotlin for Forge.
- **[Updated]** Moonlight Lib.
- **[Updated]** Paxi Configs.
- **[Updated]** Simply Swords & its configs.
- **[Updated]** Starter Kit & its configs.
- **[Updated]** Supplementaries & its configs.
- **[Updated]** The Bumblezone & its configs.
- **[Updated]** The Twilight Forest & its configs.
- **[Updated]** Visual Workbench.

### Known issues:
- Entering the mods/config menus can cause the game to stop rendering entities on the client. To fix, quit to desktop and re-open.
- While on a server, JER only displays vanilla mob and dungeon drops.


## BETA v0.2.0
### Changes (2023-02-07, 1675810140 Unix Time):
- **[Added]** The whole modpack.

### Known issues:
- Entering the mods/config menus can cause the game to stop rendering entities on the client. To fix, quit to desktop and re-open.
- JER only displays vanilla mob/dungeon drops when playing on a server.
- No custom panorama yet.
