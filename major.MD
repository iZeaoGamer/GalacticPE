## v1.0: The start of something new, the return of VoidMinerPE. The all-awaited server you've all been waiting for is finally here!

## This update brings back VoidMinerPE network. At the moment, this'll only include SkyBlock. We may release more servers in the future (if popularity is decent).

- Added a new gamemode: SkyBlock Adventure. Still not released yet.
- Added basic / certain MCMMO's.
- Added Mob AI functioning - //todo work on Dungeons next with customized health!
- Added /farm warp - This warp allows you to break down wood which gives you things, and some leaves too. This would be for later-uses with saplings.
- Added Ore generator; But this time, it's something very unique - No more requiring hard and very advanced water sources, no, no, no! None of that. We've introduced our own ore generation system, where you can place a glowing obsidian on your island, and just like that, it'll spawn cobblestone, and chances of retrieving ores.
- GlowingObsidian is now craftable. All you need, is planks, and wood. Just put the wood in the middle, whilst you add Planks to everything except the middle. You will now get GlowingObsidian. ;D
- You can no longer break grass or dirt blocks on your island, unless you have a shovel to expand this.
- Added Skill Points; You can levelup your skills, which you can use later on to buy upgrades and perks using /enchanter.
- Added /enchanter; Brings a chest GUI. How this works - When you type /enchanter, a Chest GUI will popup. Firstly, you'll have to verify what tool you want to upgrade, and add it to the Chest's inventory when it prompts you. After that, you have a list of upgrades you can use using Skill points. At the moment, we only have one upgrade, which is duplication. Duplication goes up to the max 6. We may decrease this in the upcoming future, as it's still a WIP.
- Added experience tools; How this works: You can use Tool experience to upgrade your skill level, which can be used later on using /enchanter to upgrade your tools.
- Added Item transportation system. How this works: When you're on your island, you can drop an item from your island, and it'll teleport to your island spawn point. How great is that?
- Added anti-Void.
- Dropped items will now constantly teleport to the island, even if it's in a constant loop. This would only happen if the island has no blocks above the spawnpoint. So you won't lose your items anymore, unless you log off. We may plan on fixing this if possible.
- Leaves no longer decay.
- Leaves will now turn to Lime wool in /farm.
- Wood will now turn into planks properly.
- Use getVanillaName() to detect the vanilla minecraft name of an item.
- When interacting with an enchantment table, it'll now open the Enchanter GUI.
- Use repeating task on player join to detect ItemTeleport(), but only use it once.
- Added Server Captcha to SkyBlock Season 2
- Add enderman teleport sound to Item teleportation system.
- Fixed a lot of broken issues.
- Do not randomize seeds in the world "farm" upon every server restart. Use 1 so spawn point's always the same.
- Fixed crash when breaking blocks using other items that are not tools.
- Added /guide - Shows you your profile information along with settings. - WIP, still need to complete.
- You can now interact with the book in your inventory; Will fix more things soon.
- Added Island chat. Simply type /guide, and then click "Menu: Settings", and click "Chat feed", which will toggle on/off island chat.
- Added Item dropping option to your island.
- /farm no longer suffocates you.
- Added Ranks to the server.
- Added the following 4 new donator ranks in order:
* Islander
* Mythic
* Legendary
* Void

- Added {island_level} variable to Chat formatting.
- Fixed crash upon level up.
- Fixed issues, where the level-up message would constantly display, and the EXP wouldn't go above zero.
- Swords and other items no longer count as "Experience tools", since that'd make no sense.
- Added basic Fishing and Fighting MCMMO (Untested).
- Island settings currently now work as expected.
- Item dropping will now disable properly if the Item Dropping option is set to false AKA off.
- Fixed crash upon player join.
- Fixed crash when attempting to chat.
- Tools now receive damage when in /farm. Before, tools wouldn't take any damage at all.
- Changed-up HotBar Crystal.
- When turning on Hotbar Crystal, it'll now be in your inventory to use to open the SkyBlock Guide. With this, you won't be able to take or transaction the Crystal out of your inventory. To disable this, use /guide or interact with the item, click on "Menu: Settings", and then click on "Hotbar Crystal" item.
- I’ve decided to completely reset the versions and the seasons due to different server name. It’ll now be “Season 1 / V1 UPCOMING UPDATE.”
- Added mining world.
- Hotbar crystal will now save into the appropriate data folder, instead of code-saving, which was very poor.
- Added Crusher menu. How this works: You can crush an item that has the option to crush, where you can crush them, basically turning them into different items. Yes, they have specific chances of them.
- Added Compost Menu - How this works: You can compost an farming item and turn them into different items. 
- Added Brewer menu - How this works: You can receive Potions (as a very rare chance) in Compost menu. You can use these potions to buy rarites / tiers of potions. The higher rarity you choose, the more potions it’ll cost you. With potions being potions, they’re custom potions, and can be used to do custom events such as: Absorb 250 damage, strength, overpowered regeneration, and more.
- Added skills menu. Type /skills or open it using the guide to see your skills information.
- Skills menu complete.
- Added crafting skills and leveling-up.
- Added Fight skills.
- Added mining skills.
- Added display tags for “Primary skills”, and “Secondary skills” to /skills. Essentially, what this does, and the differences between the two, is:
* Primary Skills - This basically means your main skills.
* Secondary skills are a sub-category of the main skills. So for example, Fighting skill is the primary skill, and Sword skill is a secondary skill of Fighting because they’re both related, and are related skills. All related skills to the primary skills are classed as “Secondary skill”.

- Added island chat, you can go to settings, and toggle “Island chat”. You can then talk in island chat, which will be associated with all your island members whom can see this chat.
- Added mining world. This will be where you can mine stone, ores, and anything that relates to mining and caves.
- Stone and diorite now turn into bedrock when broken. Keep in mind - They auto regenerate into their appropriate form after 1 minute after block being broken.
- Added auto-regenerations to Mining world.
- You now have to level-up your mining skill to mine ores. All was explained in the Mining levels video.
- Added Encanter to The Guide.
- Added Brewer to the guide.
- Added Crusher to the guide.
- Added Composter to the guide.
- Added dungeons to the server (A WIP).
- Added dungeons world.
- Mobs are now faster depending on your dungeon level. 

How does dungeons work?
Basically, with dungeons, there’ll be levels. Each level has their own dungeons. Progressively, the dungeons will be harder, as you go upto higher levels. The more dungeon levels you progress through your adventure, the more harder each boss will be. Increasing boss hearts, along with the speed of the mobs and bosses. Once you’ve killed a boss, you will automatically be teleported to the next dungeon level, and you will grant access to the next dungeon level warp. Soon, I plan to add boss drops as well as some rewards. Still are unknown as of yet.

## In english
It’ll be like a PVE feel of things, in which you don’t see much nowadays for MCPE.


- Fixed random server crashes.
- Do not check for worlds as a task.
- Item teleportation now works below the Y coordinates.
- Added Quest tier system. How this works: Each tier has its own quests inside it. All you need to do, is complete 4 tier sets of quests (since 4 is the max). to earn a reward. The reward hasn't been decided yet.
- Added /quest.
- Fixed crashes when using certain items to break blocks.
- Mobs no longer auto spawn, due to lag.
- Fixed quests system from breaking.
- Fixed some quests from not functioning, therefore you being stuck.
- Fixed a major exploit, where you could mine any block during the quest, and it'd still give you the amounts you've done.
- Added "Quest status" hotbar, where if you start a quest, it'll say "Quest Status: 0/64" as an example. This is so you can keep track of how much you're currently at and within the maximum show displays too.
- You can no longer receive Tier points for placing and breaking cobblestone. This is simply to prevent abuse of the quest system. You'll have to mine for it instead!
- Fixed a major dupe, where the tier points will double your blocks. This shouldn't do that, and is unacceptable.
- Reformatted the code, and fixed-up a lot of silly and useless issues, and bugs that we didn't need.
- Creepers no longer despawn after they explode - This is one of the funny features I've added to ensure creepers DO NOT despawn. The only way you can really kill them, is by hitting them to the void. Not sure why the knockback is broken on them, but that should hopefully be fixed soon.
- Added Item Frames flag, and Added ArmorStand protection.
- Protected Fishing world to ensure no one griefs it, and in anyway, in case if we forget later on.
- Updated /guide menu - Added some missing names to each of the block/item within the menu. Soon, I plan to make it so you can teleport to certain warps in /guide. (:
- You can no longer rotate or break item frames in protected areas. Yes, I had to code this within the code its self, not using /rg.
- You can no longer: Interact with Armor stands, and break armor stands. Since Breaking Armor Stands relies on EntityDamage() function, not BlockBreak() function.
- Added "PVE" world, where you can fight mobs, and level-up your skill.
- Added Shears Skill! You can shear sheep using "Shears", and gain Skill XP from it.
- Renamed "Excavation" to "Excavating" in all of our data, and server-side.
- Fixed item drops for ores.
- Added Ore regeneration every 60 seconds.
- All ore drops will now go directly straight into your inventory.
- Block Break Particles for Ores are no longer visible. This is due to the Block regeneration system in the Mining world.
- Fixed crash when mining Nether quartz ore.
- You can now receive XP when breaking Coal Ore, as you'd normally do in vanilla, except it'll be direct, not indirect (as in drops on the floor).
- Fixed major crash with certain skills.
- Every time a mob spawn, it'll now state the nametag, and levels of each mob. The difference between Dungeons and PvE, is with dungeons, mobs spawn specifically the Dungeon levels, times that. With PvE World, mobs will spawn with randomized levels, and health. The higher the mob level, the higher health it'll be.
- Added new Primary skill: Herbalism.

## What does the Herbalism Skill do?
Essentially it's apart of the farming skill, but still folds as its own category because of the differences between its purposes. Herbalism can double your drops within crops and growable items. The higher skill level you level-up your Herbalism, the higher the drops.
- Added Primary skill: Breeding.

## What does Breeding Skill do?
This skill will allow you to breed breedable mobs (as seen in vanilla), and once breeded, your Breeding skill will level-up. We plan to add a few more primary and sub skills in the future, But this is just the beginnging.
- Added checks before player Spawned is executed (AKA Player Join). This should prevent anymore server crashes later on.
- Fixed typo with the main priority checks.
- Added a way to find out how many more Skill XP you need to go to the next level to /skills.
- Added new Primary Skill: Magic.

## How this works?
You can obtain magic skill by using crushing table, which can be used in /guide. We may add more ways of obtaining Magic skill soon, but this is the start of it.

- Added new Primary Skill: Alchemy.

## How this works?
You can obtain Alchemy skill by using Brewing menu. Once you've bought potions, your Alchemy skill will obtain Experience.

- Added Secondary Skill: Crushing.

## How this works?
You can obtain and receive Experience from Crushing skill from the Crushing Table menu. The more you use it, the more experience it'll level you up as.

- Reorganized /skills menu, made Primary skills from Row 1 - 2, and the rest (from 3rd row), and below.
- Skill levels are now worth it - You can now receive Money from leveling up. The higher your skill level is, the more money you'll receive.
- Added Island Settings GUI.
- Added an error message for those that attempt to use Island settings GUI in the Menu settings, but it wouldn't work.
- Updated / changed "must be an island leader" message to suit the non leaders needs.
- Fixed crash when opening Island settings.
- Fixed crash when another island player that is on your island / a random player joins, and whilst you're on the island, this would lead the server to cause an error AKA crash.
- Made warps functional in /guide.
- Added /pve - Teleports to the PvE World.
- Added /mines - Teleports to the Mines world.
- Added alias command for /farm: /farms.
- Added /crusher
- Added /composter
- Added /brewer
- Added /spawn.
- Added Quests Menu to /guide.
- Added Island teleportation to /guide.
- Renamed Potion "Speed" to "Absorption" in /brewer.
