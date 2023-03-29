# Changelog
All changes to Grindergard Revolution will be documented in this file. The format is informed by [Keep a Changelog](http://keepachangelog.com/en/1.0.0/). Version number structuring is inspired by [Semantic Versioning](https://semver.org/spec/v2.0.0.html) and can be read as follows: MAJOR.MINOR.PATCH(HOTFIX)

Major and Minor updates and Patches are all declared with ascending whole numbers, and Hotfixes are declared with ascending alphabetical characters. Major updates add gameplay features or otherwise significantly effect the experience of play and are not compatible with clients/servers of differing versions. Minor updates contain fixes and changes that are not compatible with clients/servers of differing versions. Patches contain fixes and changes that are significant but are intercompatible with clients/servers running packs of the same major and minor version. Hotfixes include only minor fixes and are intercompatible with clients/servers running packs of the same major and minor version, and these changes are included in the event of a subsequent patch.


*Example:* v1.2.0a *indicates a hotfix for the 1st major version with its 2nd minor update before any patches.*
| Features| Major | Minor | Patch | Hotfix
|------------------------------|-------|-------|-------|---|
| Intercompatible        | x     | x     | ✓     | ✓ |
| Incremented in whole numbers | ✓     | ✓     | ✓     | x |
| Incremented with letters       | x     | x     | x     | ✓

## RELEASE v1.7.0: Multiplayer Update
This minor update completes the overhaul of the damage system started in 1.6.0. All armor sets provide more damage reduction out the gate, while the Protection and Sharpness enchants have been removed (with minor exceptions). This makes the effect of defensive stats more predictable, and the removal of "must-have" enchantments removes a barrier to both accessing high-end gear and exploring varied equipment builds. This update also improves upon the multiplayer experience in several ways. Cooperative exploration and dungeoneering is improved via the addition of the /friend command, which allows players to designate other players that will be immune to their damage, and by making all naturally-generated chests with loot contain separate and individualized loot for each player. Additionally, players can now directly trade with each other by right clicking each other with an empty hand!

One of the updated mods has received a complete rewrite. Be sure to back up your worlds before updating just in case.

### Changes (2023-03-28, 1680056400 Unix Time):
- **[Added]** AttributeFix.
- **[Added]** Better Spawner Control. Any spawner can now be deactivated by placing 5 torches on it.
- **[Added]** Better Statistics Screen.
- **[Added]** Create Compats.
- **[Added]** DontHitYourFriend. This mod will be replaced by another with more functionality later, and is only applicable to online play.
- **[Added]** Eclectic Trove resource pack.
- **[Added]** Harder Natural Healing. Passive healing from food is now less effective in combat. Crafting an ender flask for healing potions is highly recommended.
- **[Added]** [SBM] Jukebox. Jukeboxes can now be fed music discs, and hoppers can't remove them until the disc stops playing.
- **[Added]** Legendary Tooltips. Tooltips are now styled in accordance with the given item, and include a 3D preview of the item.
- **[Added]** Loot Integrations.
- **[Added]** Lootr. Naturally generated chests now have unique loot for each player that opens them.
- **[Added]** NetherPortalFix.
- **[Added]** Player Trade. Players can now open a trading interface with each other by right-clicking with an empty hand.
- **[Added]** Prism.
- **[Added]** Roleplay Armor. Like Weaver's Cosmetics, these are uncraftable and hidden from JEI. Server admins are encouraged to use them as rewards.
- **[Added]** ServerConfig Updater.
- **[Added]** Supplementaries Squared.
<br></br>
- **[Changed]** Armor mitigation. Wearing any armor now reduces incoming damage by at least 20% and each point of armor further reduces damage by 2.2%. Armor Toughness further reduces damage based on the percentage of HP you're losing, providing more protection against possible one-shot hits.
- **[Changed]** the order of items in JEI to organize them more logically.
<br></br>
- **[Fixed]** Bulbis Stem unobtainable. Bulbis wood can be crafted into stems with a stonecutter or Create saw.
- **[Fixed]** Sneaking while both a keyboard and controller are plugged in causes the player to move even more slowly. This was an issue with Controllable.
- **[Fixed]** Fresh installations crashing on startup caused by JourneyMap Integration looking for a default config.
- **[Fixed]** Using a waystone while an animal is on a lead doesn't bring them with you. This was a bug with Waystones.
<br></br>
- **[Removed]** Protection and Sharpness enchantments. Naga Leggings and Mining Master weapons retain their natural enchantments.
<br></br>
- **[Updated]** Balm.
- **[Updated]** Better Compatibility Checker.
- **[Updated]** Blueprint.
- **[Updated]** Bookshelf.
- **[Updated]** The Bumblezone.
- **[Updated]** Comforts.
- **[Updated]** Configured.
- **[Updated]** Controllable.
- **[Updated]** CraftTweaker.
- **[Updated]** Create: Extended Cogwheels. The mod has been completely rewritten, so make sure to backup your worlds.
- **[Updated]** Curious Lanterns.
- **[Updated]** DefaultSettings.
- **[Updated]** FancyMenu.
- **[Updated]** FTB Backups 2.
- **[Updated]** Handcrafted. Adds recipes for dying individual cushions and sheets. Also allows Create's cutting system to produce boards.
- **[Updated]** JCPlugin.
- **[Updated]** JourneyMap Integration.
- **[Updated]** JourneyMap.
- **[Updated]** Just Enough Items.
- **[Updated]** Just Enough Professions.
- **[Updated]** Just Enough Resources.
- **[Updated]** Kotlin for Forge.
- **[Updated]** L_Ender's Cataclysm. All bosses have received a rebalance, and custom boss bars have been added.
- **[Updated]** LibX.
- **[Updated]** Macaw's Doors.
- **[Updated]** Moonlight.
- **[Updated]** Placebo.
- **[Updated]** Quark.
- **[Updated]** Savage & Ravage.
- **[Updated]** Shield Expansion.
- **[Updated]** Simple Discord RPC.
- **[Updated]** Spark.
- **[Updated]** Starter Kit.
- **[Updated]** Structory.
- **[Updated]** Stylish Effects.
- **[Updated]** Supplementaries.
- **[Updated]** Visual Workbench.
- **[Updated]** Waystones.
- **[Updated]** Yung's API.

### Known issues:
- Entering the mods/config menus can cause the game to stop rendering entities on the client. To fix, quit to desktop and re-open.
- While on a server, JER only displays vanilla mob and dungeon drops.
- Text in guidebooks may be illegible at certain resolutions. Resizing the UI scale within a patchouli book can fix text rendering.
- Lanterns in a hip slot will render in first person view several chunks ahead of the player with certain shaders while that curio slot's display is toggled on.
- Items sent to mailboxes made of modded wood types can only be retrieved by breaking the receiving mailbox.
- A handful of music discs will not lock out a hopper for their full duration, or alternately will not unlock a pulling hopper.

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
