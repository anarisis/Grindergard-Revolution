# Changelog
All changes to Grindergard Revolution will be documented in this file. The format is informed by [Keep a Changelog](http://keepachangelog.com/en/1.0.0/). Version number structuring is inspired by [Semantic Versioning](https://semver.org/spec/v2.0.0.html) and can be read as follows: MAJOR.MINOR.PATCH(HOTFIX)

Major and Minor updates and Patches are all declared with ascending whole numbers, and Hotfixes are declared with ascending alphabetical characters. Major updates add gameplay features or otherwise significantly effect the experience of play and are not compatible with clients/servers of differing versions. Minor updates contain fixes and changes that are not compatible with clients/servers of differing versions. Patches contain fixes and changes that are significant but are intercompatible with clients/servers running packs of the same major and minor version. Hotfixes include only minor fixes and are intercompatible with clients/servers running packs of the same major and minor version, and these changes are included in the event of a subsequent patch.


*Example:* v1.2.0a *indicates a hotfix for the 1st major version with its 2nd minor update before any patches.*
| Features| Major | Minor | Patch | Hotfix
|------------------------------|-------|-------|-------|---|
| Intercompatible        | x     | x     | ✓     | ✓ |
| Incremented in whole numbers | ✓     | ✓     | ✓     | x |
| Incremented with letters       | x     | x     | x     | ✓

## RELEASE v1.6.0: Enchanting Update
This minor update overhauls the damage and enchantments system for better late-game balance. Items can now only have a maximum of three enchantments (not including Mending, Unbreaking, Efficiency, and Stepping). Enchanting gems cannot be used on diamond, netherite, advanced netherite, or ignitium items, but they can be applied beyond the enchanting cap. 30+ new enchantments have been added to encourage more diverse item builds. Notably, the Stepping enchant allows players to walk up one-block ledges similar to horse movement, the Spartan Weapon enchant provides bonus magic damage while wielding a shield, and the Focused Impact enchantment increases the damage of slow weapons.

The multiplayer update is currently delayed pending critical updates from mod developers but is still planned as the next update.

### Changes (2023-03-13, 1678696080 Unix Time):
- **[Added]** Altered Damage. This balances PVP damage and provides opportunities for more damage tuning later on.
- **[Added]** Armor & Damage Scaling. This rebalances the armor system to make early game armors more useful and temper the strength of modded armors.
- **[Added]** Connectivity. This smooths out poor internet issues for online play.
- **[Added]** Step. Adds the Stepping enchant.
- **[Added]** Unique Enchantments and Unique Enchantments Base. Adds numerous enchantments for armors, tools, and weapons and restricts enchanting to promote diverse build choices.
<br></br>
- **[Changed]** Vein Mining enchant to be compatible with Silk Touch.
<br></br>
- **[Updated]** Better Combat.
- **[Updated]** Blueprint.
- **[Updated]** Combat Roll.
- **[Updated]** Easy Anvils.
- **[Updated]** Jade.
- **[Updated]** Paragliders.
- **[Updated]** Vein Mining.
- **[Updated]** YUNG's Better Nether Fortresses.

### Known issues:
- Entering the mods/config menus can cause the game to stop rendering entities on the client. To fix, quit to desktop and re-open.
- While on a server, JER only displays vanilla mob and dungeon drops.
- Text in guidebooks may be illegible at certain resolutions. Resizing the UI scale within a patchouli book can fix text rendering.
- Lanterns in a hip slot will render in first person view several chunks ahead of the player with certain shaders while that curio slot's display is toggled on.
- Items sent to mailboxes made of modded wood types can only be retrieved by breaking the receiving mailbox.

## RELEASE v1.5.0b
This hotfix re-enables Create's "ponder" feature. To do this, Canary has been temporarily disabled due to a conflict. This will result in a reduction in performance, and it's recommended you leave Canary enabled on servers as the ponder crash is client-side exclusive.

### Changes (2023-03-07, 1678236000 Unix Time):
- **[Fixed]** Using Create's "ponder" feature crashes the client.

## RELEASE v1.5.0a
This hotfix resolves a crash on startup.

### Changes (2023-03-06, 1678130520 Unix Time):
- **[Fixed]** Supplementaries crashes the game due to malformed config.

## RELEASE v1.5.0
This minor update contains critical fixes for server functionality. The next update will be focused on improving the multiplayer and co-op experience.

### Changes (2023-03-06, 1678087380 Unix Time):
- **[Added]** Executioner loot.
- **[Added]** Vindicator loot.
<br></br>
- **[Changed]** JourneyMap default configs. Maps should now display players and mobs as icons instead of arrows.
<br></br>
- **[Fixed]** Not receiving pickup notifications when items go into a backpack.
- **[Fixed]** Players able to consume double the intended maximum of heart containers.
- **[Fixed]** Raids not giving stamina vessels upon completion. Participating in a successful raid should now appropriately award the player.
<br></br>
- **[Updated]** The Bumblezone
- **[Updated]** Canary
- **[Updated]** Collective
- **[Updated]** Dot Coin Mod. This should hopefully resolve wallets resetting randomly.
- **[Updated]** YUNG's API
- **[Updated]** YUNG's Better Desert Temples

### Known issues:
- Entering the mods/config menus can cause the game to stop rendering entities on the client. To fix, quit to desktop and re-open.
- While on a server, JER only displays vanilla mob and dungeon drops.
- Text in guidebooks may be illegible at certain resolutions. Resizing the UI scale within a patchouli book can fix text rendering.
- Lanterns in a hip slot will render in first person view several chunks ahead of the player with certain shaders while that curio slot's display is toggled on.

## RELEASE v1.4.0
This minor update fixes a few bugs and adds compatibility and missing server functionality.

### Changes (2023-03-03, 1677833520 Unix Time):
- **[Added]** An additional recipe for backpack upgrade bases using bonded leather.
- **[Added]** Barterer, Trader, Auto Trader, Breeder, Converter, and Incubator blocks for Easy Villagers.
- **[Added]** Compatibility for Quark's Sturdy Stone with Compressium to fix a backpack bug.
- **[Added]** Compatibility recipes for foods that use fried eggs.
- **[Added]** Compatibility recipes for foods that use rice.
- **[Added]** Curious Lanterns. Lanterns and quivers can now be equipped in a curios hip slot. You will have to delete your world's curios-server.toml for these changes to fully apply properly.
<br></br>
- **[Changed]** Alex's Mobs configs to reduce the rate of Crimson Mosquitos.
- **[Changed]** Sophisticated backpacks now use sheets instead of ravager hide to account for the increased difficulty of raids.
<br></br>
- **[Removed]** Pluto. This is an experimental change attempting to address some connectivity issues and may be reverted in a later patch.
<br></br>
- **[Updated]** Balm.
- **[Updated]** Better Combat.
- **[Updated]** The Bumblezone.
- **[Updated]** Cataclysm. There is now an additional overworld boss, and some boss weapons can be combined into powerful new versions of themselves.
- **[Updated]** Complementary Reimagined shaders. Now includes a "potato" setting which should work well on lower-end hardware.
- **[Updated]** Crafting Tweaks.
- **[Updated]** Create Enchantment Industry.
- **[Updated]** Curios API.
- **[Updated]** MmmMmmMmmMmm.
- **[Updated]** Moonlight Lib
- **[Updated]** playerAnimator.
- **[Updated]** ShetiPhianCore.
- **[Updated]** Supplementaries. This should fix an issue with configs not being properly saved.
- **[Updated]** Visual Workbench.
- **[Updated]** Waystones.
- **[Updated]** YUNG's Better Nether Fortresses.
- **[Updated]** The server guidebook to add miscellanious keybinds.

### Known issues:
- Entering the mods/config menus can cause the game to stop rendering entities on the client. To fix, quit to desktop and re-open.
- While on a server, JER only displays vanilla mob and dungeon drops.
- Text in guidebooks may be illegible at certain resolutions. Resizing the UI scale within a patchouli book can fix text rendering.
- Lanterns in a hip slot will render in first person view several chunks ahead of the player with certain shaders while that curio slot's display is toggled on.

## RELEASE v1.3.0
This minor update adds a handful of bugfixes.

### Changes (2023-02-23, 1677191880 Unix Time):
- **[Updated]** The Bumblezone.
- **[Updated]** CraftTweaker.
- **[Updated]** Moonlight Lib.
- **[Updated]** Simple Farming. Scarecrows now correctly prevent trampling.
- **[Updated]** Simply Swords.
- **[Updated]** YUNG's API.
- **[Updated]** YUNG's Better Nether Fortresses. Adds new structures to fortress bridge networks.

### Known issues:
- Entering the mods/config menus can cause the game to stop rendering entities on the client. To fix, quit to desktop and re-open.
- While on a server, JER only displays vanilla mob and dungeon drops.

## RELEASE v1.2.0
This minor update gives the Create mod more automation targets through Simple Farming, and adds a target dummy to more easily compare the various weapons and their damage output.

### Changes (2023-02-21, 1677011940 Unix Time):
- **[Added]** Simple Farming.
- **[Added]** MmmMmmMmmMmm. This adds a craftable target dummy that gives damage feedback when harmed.
<br></br>
- **[Updated]** Combat Roll & its configs.
- **[Updated]** CraftTweaker.
- **[Updated]** Entity Culling.
- **[Updated]** JEI.
- **[Updated]** The patchouli guide for the official server.

### Known issues:
- Entering the mods/config menus can cause the game to stop rendering entities on the client. To fix, quit to desktop and re-open.
- While on a server, JER only displays vanilla mob and dungeon drops.

## RELEASE v1.1.0
This minor update is mostly centered on stability fixes but also smooths out early game logistics through the addition of carts, rounds out lighting/decoration with Fairy Lights, and adds some UX tweaks through Auto Third Person.

### Changes (2023-02-20, 1676885520 Unix Time):
- **[Added]** AstikorCarts. These should be a good early game group-transit/bulk freight option that synergizes with the pack's existing work on improving horses. Create trains will always be the stronger alternative, but are inaccessible early game, so carts are here to make the transition a little smoother.
- **[Added]** Fairy Lights.
- **[Added]** YUNG's Better Nether Fortresses
- **[Added]** Auto Third Person.
<br></br>
- **[Removed]** RPG Parties. Opening the party UI was causing the client to crash out.
<br></br>
- **[Updated]** Better Beacon Placement.
- **[Updated]** Combat Roll.
- **[Updated]** Curios API.
- **[Updated]** Dot Coin Mod.
- **[Updated]** Just Enough Items & its configs. Toggled search-by-color off to make it easier to search for specific items.
- **[Updated]** Pick Up Notifier. Pick ups now display the total amount held by the player in addition to the amount picked up.
- **[Updated]** Realistic Bees & its configs.
- **[Updated]** Savage & Ravage.
- **[Updated]** Simply Swords & its configs.
- **[Updated]** The Bumblezone.
- **[Updated]** Yung's API.
- **[Updated]** The patchouli guide to include combat roll instructions.

### Known issues:
- Entering the mods/config menus can cause the game to stop rendering entities on the client. To fix, quit to desktop and re-open.
- While on a server, JER only displays vanilla mob and dungeon drops.

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
