Hello, my name is Thomas.

I'm a recent graduate from QUT Gardens Point with a Bachelor of Information Technology in Computer Science. I also have minors in Intelligent Systems + Computational and Simulation Science.

I mostly work on Minecraft mods and datapacks in my free time. I'm in the process of updating all of them to 26.3 and publishing them on my [Modrinth](https://modrinth.com/user/brainage04) and [CurseForge](https://www.curseforge.com/members/brainage04/projects) profiles!

Here's a list of the private, closed-source mods I've made (these are private indefinitely until further notice):
- SkyportMinigames - adds a huge suite of minigames to Minecraft - tons of duel types, UHC gamemodes, Bed Wars and SkyWars gamemodes, a few TNT-based gamemodes and much, much more! You can find more info + an exhaustive list of minigames [on the website (private for now - will publish soon!)](https://skyportminigames.com) (on the Games page specifically), and you can play them for yourself by joining au.skyportminigames.com with Minecraft 26.2! (porting SkyportMinigames and SparringBots to 26.3 - should be ready in about 1 week's time hopefully!)
- SparringBots - adds competent PvP bots (used on SkyportMinigames) that can play many different gamemodes using a hybrid approach: heuristics for stuff like path-finding and strategy, and a machine learning model for the PvP.

Here's a list of the free and open-source mods I've made (all of these are for both NeoForge and Fabric 26.2 unless explicitly stated otherwise):
- [ProceduralDungeon](https://github.com/brainage04/ProceduralDungeon) - adds a procedurally generated dungeon that has multiple different difficulty/loot tiers and themes across all three vanilla dimensions. Major work in progress.
- [BrainageHUD](https://github.com/brainage04/BrainageHUD) - a highly customisable heads-up display mod that adds many different widgets - position, armour, keystrokes, reach display, network stats, and much more! Also comes with an easy to use drag-and-drop editor :) (if you're interested in a library that makes developing HUD mods much easier, that also has a built-in drag and drop editor, check out [HudRendererLib](https://github.com/brainage04/HudRendererLib))
- [ToggleSprint](https://github.com/brainage04/ToggleSprint) - a Forge 1.8.9 version of BrainageHUD, with a toggle sprint feature that is safe to use on Hypixel!
- [TextureAtlasGenerator](https://github.com/brainage04/TextureAtlasGenerator) - a texture atlas generator that supports vanilla + Hypixel SkyBlock texture atlases! Helpful if you ever need texture atlases for use in other Minecraft-related works such as websites.
- [MagicCarpet](https://github.com/brainage04/MagicCarpet) - adds three tiers of Magic Carpets that you can fly around in - complete with balanced recipes, advancements, cool flying animations and more! Tip: 2 people can ride a Magic Carpet at once :)
- [IceSkates](https://github.com/brainage04/IceSkates) - adds Ice Skates and Roller Skates, which basically let you glide on ice and regular terrain respectively as if you were surfing on a boat. Ice Skates are super fast on ice and super slow otherwise, Roller Skates are equally fast on ice and otherwise.
- [VeinMiner](https://github.com/brainage04/VeinMiner) - a Vein Miner mod that works with veins of the same mineral but different stone types (e.g. a mix of Diamond Ore and Deepslate Diamond Ore)
- [Telekinesis](https://github.com/brainage04/Telekinesis) - automatically teleports mob/block drops into your inventory, like the [Telekinesis](https://wiki.hypixel.net/Telekinesis_Enchantment) enchant from Hypixel SkyBlock!
- [BetterVillagerTrades](https://github.com/brainage04/BetterVillagerTrades) - modifies all enchantments on items and books offered by Villagers to always be max level and makes rerolling much less tedious!
- [AcceleratedDamage](https://github.com/brainage04/AcceleratedDamage) - server-side gamerules for accelerated combat - no invincibility frames and damage + healing over time (effects, fire, drowning, regeneration, mob attack cooldowns) at up to 10x speed.
- [DimensionStructureVariants](https://github.com/brainage04/DimensionStructureVariants) - adds cross-dimension variants of vanilla structures, like villages in the Nether and End, fortresses and bastions in the Overworld and End, End cities in the Overworld and Nether, and much more!
- [FloodedEnd](https://github.com/brainage04/FloodedEnd) - puts the ocean back into the End! End Ships float on water instead of air now :)
- [SimpleTPA](https://github.com/brainage04/SimpleTPA) - adds a "teleport ask" system with gamerules that allow auto-accepting of teleport requests globally and/or for players on your auto-accept whitelist!
- [SimpleHomes](https://github.com/brainage04/SimpleHomes) - named homes with per-player limits that you can share with specified players!
- [SpawnCommands](https://github.com/brainage04/SpawnCommands) - commands for the world spawn, your personal spawn and spawns other players have shared with you, using beds and respawn anchors!
- [SimpleTwitchChat](https://github.com/brainage04/SimpleTwitchChat) - connects your Twitch and Minecraft chats! Twitch chat messages get sent to your Minecraft chat, and /tc in Minecraft chat sends a message to your Twitch chat.

I also have a fairly exhaustive modern Fabric + NeoForge modding template called [ModernMinecraftModTemplate](https://github.com/brainage04/ModernMinecraftModTemplate):
- Server-only, client-only and server+client splits supported (click `Use this template` and then manually run the init workflow to choose your split)
- NeoForge and Fabric support
- Test and gametest modules for unit tests and GameTest tests respectively (todo - add option to remove in init workflow)
- Headless client GameTest tests for client-only and server+client splits (todo - add option to remove in init workflow)
- Automatic GitHub release, Modrinth project creation (if project does not already exist) and Modrinth + CurseForge version creation on tag creation

I also have a modding template for Forge 1.8.9 called [LegacyMinecraftModTemplate](https://github.com/brainage04/LegacyMinecraftModTemplate), which is similar to [ModernMinecraftModTemplate](https://github.com/brainage04/ModernMinecraftModTemplate), but it uses Kotlin, MoulConfig and modern Gradle tooling!

I also have a datapack template called [DatapackTemplate](https://github.com/brainage04/DatapackTemplate) that's pretty easy to use - just click `Use this template` and rename it, and it'll automatically refactor the datapack namespace/name according to the name you gave the GitHub repository.

You can reach me via various socials which can be found on my [website](https://brainage04.github.io).

Last updated: 25 October 2026
