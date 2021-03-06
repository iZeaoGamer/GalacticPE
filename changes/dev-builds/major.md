## GalacticPE Version 3

## This version is a major version, and includes a lot of changes.
## GalacticPE, is a upcoming network, supporting SkyBlock, Factions, and Prisons, which has custom features that you might not see on MCPE before.

## This update is huge due to that, and includes a lot of improvements, stability fixes, and scoreboard changes, query fixes, tags, and so much more!

## Version: v3.0.0 / What's new?

- Added colored rank name, rather than just the plain rank name in scoreboards.

- Updated max player list to exclude Donor slots via scoreboards.

- Updated current online player list to exclude vanished players via scoreboards.

- Updated /list.

- You can no longer be seen in /list when vanished. (Though, people with permission can see you whilst in vanish).

- Added a way to remove yourself from the query list when vanished.

- Updated some addons list.

- Added staff mode when vanished.

- Added /bm - Allows you to edit/touch a protected area. Means build mode. Credits to @Owner | BigDisrespect for the idea!

- Added all ranks to the database!

- Owner is now multi-coloured! How awesome is that?

- You now have an option to use the Target a player item to either teleport to any random online players, or let it open a UI so you can choose which player to teleport to!

- Use Target A Player item to teleport to a random/select a player.

- Added new donor ranks to the GalacticPE server.

- Changed the way moderation management works.

- We've added 5 new items to vanish (As staff mode).

1. Target A Player - We've changed that massively. You can target players in two ways!
* Target a randomised online player, which will randomly teleport to any online player.

* Select a list of players online using a form.

2.  Freeze A player - Hit the specific user to freeze/unfreeze a player.

3. Random Target Teleporter - Toggle on/off online player teleporting using the Target item. If turned on, you can randomly teleport to a random online player. If turned off, the Target player item will show a form UI of selections of whoever you want to target.

4. InventorySee - You can check for other player's inventories, by hitting them! Of course though, this does come with availability of what you can and want to do. Depending whichever mode / option you select, you can open their player inventory or their ender chest inventory.

5. Inventory Type - By default, it's set to Player Inventory. If turned to Player Inventory, once damaged a player, it'll open their personal inventory (Player Inventory). If turned to Ender Chest Inventory, when you next damage a target player, you can see their ender chest inventory.

- Fixed Ice item from being place-able when in vanish.

- We've finally created our own area/world protection plugin and messages!

- Currently there's no available way of being able to create, edit, and delete a area. This is all done through coding. We may add support for in-game compatibility in the future.

- Added BuildMode support.

- Added /bm = buildmode to the server! How this works:
When you type /bm on, this means you can bypass area protections. You can break, and place any blocks, but the cache is you won't be able to drop any items. You will also be put in creative mode for obvious reasons. To disable this however, use /bm off.

- Added new world edit system

- We're now using a completely, updated, and brand new worldedit plugin that somewhat still works! 

- Added a new permission node: *. This permission node is very Overpowering. This permission will allow you to gain access to every single command without operator. This permission also acts like operator. This is globally, and this is very useful for if you don't want to op somebody on all servers.

- Added 2 new Staff items to vanish mode!

1. Staff Chat - You can toggle on/off staff chat, just by using items, or by typing /sc.

2. Chest - This item is place able, and will allow you to catch xray hackers! How this esentially works, is you can place this chest without it making a sound. It'll silently place a chest, which will have randomised loot. This loot can be used by players, which then we can decide whether or not they are xraying. It is really best to use this in mines (Because of course, xrayers love mining!) You can also break the chest. Once broken, it won't make a sound, and loot won't drop with the broken chest due to exploit reasons.

- Fixed staff chat exploit, where other players could see your white text message, acting as if the chat message were set to default, but also made it into staff chat.

- Added new text channel: #staff-chat. This chat will have all staff chat related messages from in-game to that channel.

- Cleaned-up player chat messages, which fixed a few other technical problems.

- Upon breaking a chest whilst in vanish, it'll now become silent!

- Picking up items whilst in vanish will no longer disappear, and then closes the entities within that world. It'll just not let you pick it up! We've done this change to ensure less duplications, and item loses.

- Added new command: /sc

- Fixed /spawn from not teleporting you to spawn correctly.

- Throw an error message if the Invsee feature is currently unavailable.

- Fixed /nick from causing future errors.

- /nick no longer relies on ranks, so even if the database is down, the nicknames won't cause an error.

- Fixed staff chat causing wrong error directions (ON/OFF) when used.

- Fixed join/quit messages occurring whilst in vanish, and if left whilst in vanish! Now, it won't pop up a join/quit message if you leave whilst in vanish! This was due to the join/quit messages occurring in the wrong moments.

- You can no longer use /tp, and /teleport whilst in vanish! This is to prevent cheating!

- Fixed being able to place blocks whilst in vanish! (This includes Staff items like Staff Chat (Concrete) being place-able.

- Moved setVanishTime() and getVanishTime() to Player::class. This is because it's more preferred that way than using other classes.

- Quit/Join messages will no longer display if you're in vanish, and you leave the server! - That way, nobody will know if you're on or not. This is a very great way to know, and as far as coding goes, there's absolutely no way anybody can find out if you're online or not!

- This update is most probably the biggest (Query) wise update ever. With /list hidden, voting site becoming hidden, server lists, and so much more! There's no possible way somebody can find out if you're online whilst in vanish!

- Completely revamped, and recoded Bans system!

- Added /ban. This command will show everything required, including the following:
* Ban information

* Ban searches

* Banning a player.

* Finding a banned player (AKA checking history).

* Remove, and confirm a ban!

- Class reasons are required reasons, instead of being able to enter an empty reason message.

- Make perm bans a "Forever" until ban date if expires is set to false.

- Added new punishment type: Mutes!

- You can now mute a player with the new punishment system. (TODO; Work on warns next!)

- Added /mutelist

- Many changes, and huge bug fixes to do with /banlist not working properly.

- You can now check a muted/banned player two ways!

1. Check using /mutelist <player> for the given muted player or /banlist <player> for the given banned player.

2. Check using /mutelist for all the muted players or /banlist for all the banned players.

- Change Player not found UI from Friend Manager to User Management for more professional UI's.

- You can no longer execute blocked commands whilst being muted. We will do much more than this in the future, such as: Disallowing players to write certain things on signs whilst muted, or nothing at all if muted.

- Added new plugin events: UserCommandEvent, and UserChatEvent.

* UserCommandEvent: Activates if a player uses a command that's blocked.

* UserChatEvent: Activates if a player uses the chat whilst muted.

- Fixed crash when executing /mute.

- Fixed crash when typing in chat.

- Fixed server crash when the database is back online, and you chat/leave/execute a command, it'll kick you out of the game, cause an error, and crash the server. We've added a way so this no longer happens. Which basically is once the database is back online, it'll fetch for all online players, and will reload CustomPlayer::class again.

- Added [item], where you can showyour items in chat. (Inventory support will be coming soon).

- Start work on IP Bans / IP Muted. (Not yet working)

- You can now modify user's ban/Mute! You can type it in two ways:

1. Use /mutelist -> Select player -> Modify mute or /banlist -> Select player -> Modify ban

2. Use /mutelist <player> -> Modify Mute or /banlist <player> -> Modify Ban.

- All bans modifications now update, work, and save properly!

- All mutes modifications now update, work, and save properly!

- You can now use Time formatting in another way!

* New way of adding time, is instead of typing for example, 1 day, you can type the Day, the Date, and the time. Though, this would be recommended and updated through Modifying a player's ban/mute! All you'd need to do, is update the day, date, and time of the mute/ban! It's recommended though to do the shortened way; <time> Shortened, where you can display how long a user's banned for via English textual datetime description. That's basically time formatting such as 1 day, or 5 days, 5 hours, 5 minutes, 1 second. Formatting a local date/time is dates you enter like Wed Jan 2 10:54:45 2021, which is the longer date/time formatting, which you use for modifying a player's mute/ban!

- You can now delete another player's mute/ban! You can do this in two ways!

1. Type /mutelist -> Select player -> Delete Mute or /banlist -> Select player -> Delete ban.

2. Type /mutelist <player> -> Delete mute or /banlist <player> -> Delete ban.

- Added more error message UI's, rather than debug messages.

- Updated Time invalid error to display in UI.

- IP Bans / Mutes have now been added! We are looking for any other possible way of actually bypassing IP Bans / Mutes (Excluding VPN's for now).

- Fixed staff chat from being made public when talking in the staff chat. Since before, it'd also display staff chat messages publicly due to a chat event not being cancelled correctly.

- Tweaked Galactic Energy a ton!

- If you have more than the required energy amount, it'll now update to the correct energy level. Before, it'd update, and reset Energy to zero, and add +1 to Energy level for the given item. This is more appropriately used for future implementations (such as Lootboxes, GC's, etc!).

- Fixed a bug, where tools updating automatically would send to an incorrect item, which would only occur if there's an item in your inventory with no custom name. Now, it'll only update the item in your hand (if no custom name was set), and not your contents in your inventory (Basically, the item that has no custom name must be in your hand for it to update now). 

- Fixed a major bug, where you can combine other things that aren't tools. Like dyes, emeralds, basically any item. Now, it'll only combine tools. 

- Fixed crash when updating your hand.

- You shouldn't log out whilst energy is going to your item. Depending on how much energy you are currently adding to your item using the energy item, it could take a while. If it's low amounts, then it should take less than a milisecond. But again, if it's a high amount, it'll be longer. Just don't log out or you'll lose the upcoming energy that was being added. No, you won't lose all of it, just the ones you  logged out before it appeared into your tool. Unfortunately there isn't an actual fix for this.

- You can no longer join a server if you're ip banned. The only way of bypassing this, would be to use a VPN. But we may/may not implement an Anti VPN system. Really depends on if we can get one.

- You can no longer chat on a server if you're ip muted. The only way of bypassing this, would be to use a VPN. But we may/may not implement an Anti VPN system. Really depends on if we can get one.

- Fixed onEnable() crash when registering all users to the User management database (Yes, this was a data loss crash), meaning all bans/mutes would be reset after restart.

- Fixed mr-broken user management registeration problems.

- Fixed crash when typing /gmc, /gms, /gma.

- Added new warns system!

- Warns are now calculated properly!

- Fixed warns data loss crash upon onEnable() state.

- Added Trainee role to the public discord server.

- Added brand new command: /fixconn - This command will allow operators (Me specifically) to attempt to fix the database connection (If broken). It'll also display the results, and whether or not it was a successful connection. If unsuccessful, it will display an error message along with the error code. Please note this command does not always fix connections. It's an attempt, meaning it'll try as much as possible to fix the database connection.

- Fixed staff chat bug, where you wouldn't be able to talk normally if database is offline, and you're in staff chat. Now, it'll automatically put you into global chat (Basically default chat in-game) until the database is back online again.

- Once warned 3+ times, it'll automatically kick you from the server, and resets your minimum warning points.

- New warning points system. How this works:

* There is minimum warnings, and total warnings. Minimum warnings is your warning points. That'll reset every 3+ times, and will reset those warning points, whereas total warning points, is where those warnings will never reset, and will encounter as your whole record of warns. This is so we know if you've been warned before.

- You can now use /vanish without the database being online. Basically meaning you can use vanish freely no matter if the database is online or offline.

- Fixed crash when warning a player.

- Fixed crash when deleting a player's warn.

- Fixed crash when deleting all of a player's warn.

- Fixed a bug, where permissions wouldn't update properly unless you logged out and logged back in again. (Basically re-logging). Yes, this has been an issue for some time which should now be fixed. (Untested).

- Energy percentages are now more accurate!

- Percentages before going to the next Energy level are now only up to 100%, just like Cosmic Java! How awesome is that!??

- Invsee has now been added to the Server!

- We've changed the port number for OP Prisons due to complications! The port is now 25574, so save that port into your server listing. Also, please share this to everyone as the port was changed. Yes, the IP is still the same. It's only the port number which had changed.

- Fixed a duplication word glitch: "muted" when muted from the server. It'll now only display the "You are muted" thing once, instead of saying "You are muted muted.".

- Freezing a player now properly works!

- Fixed a bug with freezing, where it'd display the same message as if you were frozen, even if you were being unfrozen. You could still move by then, but the message would duplicate, and would act as if you were just muted by a staff member.

- You will now get perm banned automatically if you log out whilst frozen!

- The "banned by" section of the perm ban will now display as "Console" when logged out whilst frozen!

- Fixed not being able to open Player's inventory and Ender chest's inventory of a player's Ender chest.

- Energy percentage now divides the amount by 100. That way, it'll convert this into how many energy you have, out of the max. The max and current will also be divided to so you know the percentage amount (max: 100%) out of the maximum energy required to go to the next level!

- Fixed a bug, where if you logged out whilst frozen, it wouldn't ban you. This was because we needed to update the ban API to the new punishment API we have implemented.

- Databases now refresh 10x faster than before!

- For now, we're no longer using #network status channel, to display the server's status. We will definitely add this back soon! We may add this back in the upcoming updates! I just thought I'd test it without the messages contexed to the channel and see if there's any other concurrent bugs.

- We're now using AsyncTask over Timer tasks (Also known as schedulers). AsyncTask is 10x faster, and the reason why it's 10x faster, is because when the database refreshes, or updates, reloads, and inserts a row or value, it won't put the server into restraint. This means databases and everything requiring for databases won't cause lag to the server, meaning better performance and more reliable (lag wise).

- Fixed crash when attempting to join the server.

- Added new error messages for database connectivity problems.

- You can now: Set rank's, set a user's permission, and things like warnings's without lagging the server or other players, causing this to lag the server.

- Database refresh is now 10x faster. (Again, I'm not sure if it's due to the network status temporarily removal, but we're working on bringing this back, better than ever!

- Use MySQLProvider::$connected to isDatabaseConnected() function. Returns true if connected, returns false if not.

- Added staff commands, and player commands channels!

- You can now check out all player commands, rather just staff

- Fixed staff chat from not working properly. (Once again).

- You can now speak properly in staff chat, and it'll enter your message directly in-game!

- Added new channel: #commands. This channel is like staff commands, but for all player commands.

- Re-coded GalacticPE's discord server, removed useless channels, and improved on less channels, but more efficient. Big thanks to Ducky for this change!

- Fixed crash when modifying a user's warn.

- Removed Store Credits (Old plugin) from GalacticPE. This was a older feature on VoidMinerPE, where you could buy things using store credits. We may replace something in the future similar to this!

- User permissions will now load, and work without having to log off, and log back on again. (This was because I forgot some virtual part of code required for this).

- You can now delete a chosen amount of warns.

- Every Database cache will no longer lag the server.

- Fixed server freezing from occurring on weird times.

- The server IP should now be working, alongside the port! You can use the new port: 25574 with the IP: prisons.galacticpe.ml.

- Fixed crash when kicking the warned user for being warned too many times.

- Fixed wrong error coding message when warning a player. It'd say "muted", instead of "warned".

- Added new query tasks, which extends AsyncQuery class.

- Fixed bug, where it'd say the user does not exist even if you entered it correctly in /addpermission command.

- Fixed crash when using /addpermission.

- Fixed wrong error coding with /addpermission.

- Fixed crash when database was offline.

- Fixed crash when attempting to join a server that has the database set to offline.

- Database is no longer required for commands to appear in appropriate discord channels.

- Fixed crash when warning a user.

- Fixed crash when muting a user.

- Fixed crash when banning a user.

- Fixed crash when warning a player, but wasn't able to due to the database becoming offline.

- Added "Loading" messages when warning a user. This is because warnings have a longer loading time than ban and mutes are due to Warnings being on the database system, whereas Bans and mutes aren't.

- Fixed crash when loading warns, but wasn't able to due to database issues.

- Fixed wrong message coding, relating to "Being muted", turning into "Being warned". Same may have gone for Bans also. Now, they're more appropriately, but correct message coding.

- Fixed crash when trying to join a server.

- Fixed crash when typing in chat, and if database hasn't yet refreshed yet. This error could potentially happen when the database has issues, after it was recently refreshed, within a good state of mind.

- Completely re-coded Custom enchants system, and its code style!

- All custom enchantments classes now extend a certain class type.

- Completely re-written Enchantments::classes, making it easier and readable than previously.

- We no longer use callable to retrieve Event::classes within each enchantment class.

-  All onBlockBreak() events are now relied and extends RecursiveEnchant. This is so there isn't any future errors regarding blockBreak() lag with custom enchants.

- Added new function: safeReact() to RecursiveEnchantment's classes which extend RecursiveEnchant.

- Lucky enchantment now works!

- We've completely rewritten how top tier enchantment works! We've also changed and renamed the top rarity from Executive to Heroic. Big thanks to Ducky for this explaination!

- All heroic enchants now require a certain enchant level! Heroic enchantments basically allow you to upgrade your current enchant to make it even better. It requires a specific enchantment along with the level it states in its description.

- Once a heroic has been enchanted, and the requirements for heroic's upgrade has been reached, it'll now remove the Required enchantment, and will upgrade to Heroic tier, which will have better chances along with higher amounts of it activating.

- PowerBall enchantment now fires at a certain block! Yes, we will make this only ores very soon! (It also has a cooldown too!)

- Fixed PowerBall enchantment from becoming inaccurate 
 when fired (Aiming wise).

- Added a enchantment limit. By default, it's 10. But the higher rank you have, the more the limit will increase.

- Added new feature: Enchantment Orbs! How this works:

- So by default, Enchantment limit is set to 10 or whatever your desired rank is. You can receive Enchantment orbs as you progress through-

- Events, GC's, Lootboxes, cc's, and more!

- Fixed Enchantment slots displaying from duplicating when you apply it onto an item.

- Enchantment Orb types:
* There are currently 3 Enchantment orb types!
* Here are the current types we offer:

1. Pickaxe

2. Armor

3. Weapon

- Completely rewritten how event classes work! This means we no longer use callable for events to receive the enchantment on that specific event.

- Fixed crash when mining blocks.

- Fixed crash when taking damage (Most of it would've been after you had health boost, and once it get's taken away, this bug would've occurred).

- Added Enchantment books (Success + Fail rate)! How this works:

* At this stage, we're not sure how you can obtain them! But this will be revealed once everything's been added and sorted out! When you receive Enchantment books, there's a randomised success rate, and a destroy rate. (AKA Failure rate). You will want the success rate to be higher than failure rate for a higher chance of adding the enchant to your item.
If the destroy rate occurs, then it will get rid of the item you tried to enchant as well as the enchantment book! So be careful!

- Fixed crash when obtaining The Enchantment orb item!

- We've now put all Enchantments along with their rarities in order! From top being the best rarity, to the bottom, the worst Rarity. This is so all enchants are less messy, and more in order than anything).

- Added Flame particles if the enchantment succeeds and adds the enchantment to the item.

- Added Health to Player's heads!

- Shatter explosions are now less OP! This was because before, shatter would explode to a further radius! But now, we're checking, and making sure the shatter won't be as OP as before.

- Eternal Luck's blocking from proc is now fixed! It should now block others from proccing enchantments of other player's! (This has been untested).
