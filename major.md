## V2.0: The proxy and biggest update ever!

- Added Friends and Party system globally.

- Added Finding a player within the network. All staff will have /find <player>.

- Added /altfinder search <player> - This command will allow you to globally search for alts on a player. Yes, this is indefinitely globally, and will most likely be on the release (if no issues arise with it).

- We've added Client stats to MCPE! We're not sure if we'll keep it due to backwards incompatibility, but we're going to try and work on adding protocols for MCPE's versions. But the command is /cstats, and this command will allow you to check all the client's information of a player. Merely this information will be their current minecraft version, and how many unique players have joined the entire network, and you should be able to check by months, or days. This hasn't been confirmed yet, so this could change.


- Adding support for clients from 1.9 to 1.16: This hasn't been tested, but according to server list, this server supports 1.9, but in reality, it supports 1.16.0. I'll most likely try to test using other versions and see if it works properly. 

## MORE NEWS
Bungeecord plugins now work directly in MCPE, as long as you use the proxy! Yay!

- Bungee Global Punishments system: Let me put some examples here.

## TEMP BANS
You will need to type /tempban <player> #TB <reason>

Good news with this system, is you can now silent ban players! If you have the -s permission, you should be able to temp ban a user by using:
/tempban <player> #TB <reason> -s
Only Moderators and above can use /tempban.

## Warning System
We have a new and rebranded warning system! You can type the following:
/warn <player> <reason>.

TIP: You can add -s at the end to make it a silent warn.

All staff ranks have access to /warn.

## Mute System
We have a new and rebranded mute system!
You will need to use: /tempmute <player> #TB <reason>

If you want to perm mute someone, type /mute <player> <reason> [-s]

Modrators and above will be able to mute or temp mute players.
TIP: You can add -s at the end to make it a silent mute.

## IP BANS CONTROL
We have a rebranded IP Ban system. Here are the following arguments:
Perm IP Ban: /banip <Name/IP> [reason]
You can also temp ban-ip a player by using /tempipban <Name/IP> #TB <reason>

Moderators and above will be able to IP ban a player.

## NEW HISTORY COMMAND
Newly rebranded history command! Type /history <player> to check for their bans/mutes/warns history.
Only moderators and above can use this command.

## NOTES

You need to specify a valid reason. Otherwise, they will be unbanned/unmuted/unwarned.

## ALL PUNISHMENTS ARE GLOBALLY! NO NEED TO BAN PER SERVER

We have more news retaining punishments system.
We have now what we call "Offenses Order". How this works, is when a player get's banned/muted, they'd get banned for 24 hours. If they get banned/muted again, it'd be a 1 week ban, and so on. We do this to ensure players will not hack or break the rules in the future. What we mean, is the more times the player is banned, the longer amount of times they'll stay banned. So our inspections are the player will realize this, and will stop what he's doing with immadiate affect.

Warns: If you receive 3 warnings, you will be kicked from the network, globally. At the moment, sometimes the kicked messages are bugged. This is not our issue. This is WaterDog's problem.

Mutes: We've added a better blocked command system when muted.
You can no longer bypass the mute system using commands. Also, it'll now entail how long before you will get muted (In an advanced to when using commands or trying to chat). With perm mutes, it won't come up with the time of expiry.

Warns-2: You can unwarn a player by using /unwarn <player>

Bans: You can unban a player by using /unban <player>

Mutes-2: You can unmute a player by using /unmute <player>.

IP-Bans are now globally and will not interfere with the proxy.

History Checks - You can now check history of a specific player, just by using /check <player>.

If a player was ip banned, you type /unban <IP>. TO check for their IP, use /check <player>.

## Global Staff Chat
We have made staff chat global, so you can talk to other staff members across the network, instead of per server. All staff ranks will gain access to staff chat.

* Join/Leave - It'll now let you know when a staff member joins a specific server, or leaves a specific server through out the network.

* Chat with # - This is a feature we had previously, but had been remove on OP Factions S9 (On Zector). This feature allows you to chat in staff chat with #, instead of with /sc or /staffchat command.

* Command: /staffchat - to toggle it on/off.
* Chat-Command: #test for saying the message "test" into staff chat directly, which will work across the network.


## Global Reporting System
We've done some upgrades on the purpose of reporting players, and being able to report them globally. All players will have the command: /report <player> <reason>. They can report for custom reasons. Once reported, you are able to take the report, you can use: /find <reporter>, and then teleport to their server using /server <server>.

## Global Ranks System + MORE
We've moved ranks, MySQL database, Online + Offline time, StaffChat, and Automatic restarts and made it global, rather than per server.


- Fixed ranking bug, where setting a player's rank would also occur for everyone that joins. This was because before, we were using Xbox Unique ID, which cannot be used in a proxy network for security reasons.

- Fixed client crash + Server crash when attempting to join a server, within the network.

- Added builder rank. They will be granted Operator. They are only here to build, not to do the jobs for us. Their role will only be useful when something new needs building. 

- We've removed a lot of in-game chats, and squashed it into one. We will now be using #global-public-chat for network chat. It will also display what server this user is chatting in. This is so we can reduce the amount of chats we have received. In the future, we may continue to reduce the amount of chats, and start to implement a one-way-chat system for discord's side, but that will be for another topic.

- We've made changes to how #last-seen generates the server name they're on.
- We've fixed a bug to do with server names not generating as expected. (#last-seen)

- Ranks now globally work across the network, officially. The previous announcement regarding ranks had a bug regarding ranks not updating, and would update to the wrong player or worse, all of the players that joined. Good thing that's fixed, aye?

We now have our own discord bot. Meet @VoidMinerPE.

## Explain what it is, what does the bot have?
The bot is a network-corded bot, allowing the bridge between minecraft and discord.

With this becomes very special abilities. Here are our current features:

- You can now chat directly to in game. (#global-public-chat).

## Examples:
If I had access to the chat, I’d be able to basically chat to players from discord to in-game. There isn’t much MCBE networks out there that offer this!

- You can now make conversation between discord and in-game. And yes, this is all globally.

- Bot status: It’ll now display how many players are currently on the network.

Those are the basic features of the bot.

We do plan to expand the bot in the future.

- We've finally updated and moved the MySQL Database system to the new hosting provider. We shouldn't expect to see its downtime anytime soon due to expiry reasons.

- We've finally made changes to how transferring to servers work.
- * You can now use /<server_name> instead of /server <server_name>. Much easier, and less typing to do! Which is what makes this feature as good as possible.

- The rank usage has been reset (As of yesterday) due to the recent database transfer.

- We've added a Anti VPN system to the network!
At the moment, there is a bug with the kick message not appearing. This is not our problem. This is a minecraft bug!

- We've done some improvements and bug fixes with the network in general, fixing the lag, etc.

 I have made some changes to SkyBlock Adventure Season 2. This is so we can make the server as stabled as possible without lag interrupting the stage, which is apart of the 2.0.0 network rebrand!

Here are the following updates, made to the server:

- Completely recoded, and redesigned Farming system.
- Farms should no longer lag the server. This was due to terrible code implementations. The code is now more simpler, and shorter.

- It'll now tell you in chat when you've unlocked a mining material or farming material you can mine. Example: If I reached Level 5, it'd tell me that I unlocked Potato, which means I can mine it now. Same goes with the mines also. (/mines).

- We've resigned a lot of Skill levels for farming and mining. This means all the levels have been changed. It'll still be hard, but you'll see some changes in terms with level changes for Farming and Mining materials.

- Use $cost upon each of the farm/ore ids, instead of using a long scripted code which was not even needed.

- Fixed errors that a pickaxe is not in use in the Farm world.

- Fixed errors that a hoe is  not in use in the Mine world.

^ Those two errors were to occur whenever you used the wrong set of tools in an incorrect world. Yes, this has been fixed, finally!

- Fixed farming and mining world not giving you Skill Experience if you mined other than stone/Wheat.

- Fixed possible client crash through out the network.

- Fixed #last-seen's Online and Offline time from not correctly working.

- Fixed crash when killing mobs / players.

- Fixed kick message only saying the reason, not the actual statement (Message before the reason).

- Removed duplicated kick messages to ensure there's no conflicts.

- Fixed SkyBlock Adventure from not showing up in #last-seen.

- Fixed server restarting kick message not displaying properly, and would instead say "Server Closed". Either way, it'll kick you to the lobby for the correct reasons now! ;D

- Fixed Sugar Canes being able to be broken when broken at the bottom. 

- Fixed Sugar Canes from not giving you the appropriate experience, and simply not saying any message regarding low levels.

- We have made it so our current servers will be online and available all the time, even if the MySQL host is offline. I've introduced this to ensure our servers do not go offline when players want to play.

How does it work?
So essentially, as you can see in the screenshots, there will be a error regarding the MySQL host being down. It'll also forward them the appropriate error, and will start to disable the plugin. When and if there's an MySQL host problem, it'll limit the network to do certain things, such as:

- Ranks, and Permissions.

- The plugin should now enable automatically if the required database is back online, and working without a need of a server restart. This is so we don't have to restart the server to guess its current availability.

## NOTE
This feature is experimental, and may not work as expected. But it is still currently being tested, and once the MySQL database is back online, we can check to see if the plugin enabled automatically without a server restart.

- The music player is now live. Check out the public discord server's announcement channel so you know how to use the music bot. It'll work globally (Staff chat and the public discord server).

## NOTE
Please use #bot-commands for music playing commands, and use the appropriate VC (Music) or similar named voice chat to play the bot. Is there any bugs you've encounted within the Network 2.0.0 rebrand? Please let us know in #bug-reports. Thank you!

- There will be a new update regarding Network status.

## How Network Status will work

So at the moment, there will be a #network-status channel, where the service status for each server will be displayed. If it appears offline, it'll display also. Also including online too. It doesn't matter whether or not the server restarted, it'll still display so.

Before we release The Void Network, we will move this channel to the public discord server to ensure people know once it is back online. I won't add the ping to the network status because that could lead to mass pings in the future.

- fixed an issue, where it wouldn't display the server's offline status in #network-status. This was due to issues with functioning the onDisable() state. This could also be due to the amount of plugins the specific server has, thus meaning it wouldn't state the offline message in #network-status. This mainly happened on OG OP Factions, which has now been fixed.

- We've also done a new update, where the online status won't display until everything's been enabled on the server. This bug occurred because sometimes the server would go offline whilst its enabled. So it'll now state if it's online, in real time, no limits, no interruptions.

 - We have removed the "limbo" system, as what i mentioned earlier, and we've added 3 new lobbies. Lobby 1 is the main lobby, lobby 2 is the second lobby, and lobby 3 is the third lobby.

## How this system works?
The proxy will connect you to the least players online into a random lobby server. It'd usually be from main lobby to 3rd lobby. Example: If there were three lobbies, and none of them had players on, then the proxy will choose the lobby number by order. So top priority is: Lobby 1, Lobby 2, and Lobby 3. When one lobby starts filling up with players, it'll go to the next lobby. Once all the lobbies are used, it'll use the least amount of players online.

- Added /friend list: List all of your friends.

- Added /friend msg: Message a friend.

- Added /friend acceptall: Accepts all current pending friend requests.

- Added /friend denyall: denies all current pending friend requests.

-  Added /friend poke: Pokes the given friend.

- Added /friend listrequests: Lists your current friend requests.

- Added /friend broadcast - Broadcast a message to your friends.

- Added /friend cancel: Cancels a friend request.

- Added /friend toggle: Toggles if you message directly to your friend.

- Added /friend block: Blocks the given friend.

- Added /friend unblock: Unblocks the given friend.

- Added /friend blocklist: Lists all the friends you have blocked.

- Added /party toggle: Toggles if you message directly to your party members.

- Added new Chat Feature; @party != This feature will allow you to type @party <message>, which will be directed straight to party members (if you have a party created). If not, it won't work.

- We've made a huge change to how Automatic restarting works.

## What's new about this system?
- We've introduced a new way of restarting; Essentially, the server will restart at random intervals. Basically, upon server start up, it will no longer restart at the set intervals. It'll specify a randomized time (From 5400 to 30k seconds). It'll start to randomize on each server start up. Sometimes it could take longer to restart, sometimes it could be the normal average timer: 1 hour and 30 minutes. But that's very unlikely, as we look for a randomized time intervals between one specific time to another. 

This will indeed be on public release as of 2.0.0. We plan to do more updates regarding this, to make it an official release.

We've made a huge update regarding ScoreBoards!

## Scoreboard Update: What's new?
- We've added multi-lobby and single lobby support for Scoreboards.
- Added all of the current servers (including lobbies) to the scoreboard.
- Added lots of improvements to Offline detection, where it doesn't lag anymore. Before: It used to lag everytime a server is detected as "Offline". Now, it's a lot more improved than previously.
- Fixed player counter from not working as expected.

- We've introduced a BRAND new update coming to the Network rebrand 2.0.0. We're hugely changing the way our punishment system works. Don't worry though, all punishment logs will still be compatible with the newest punishment plugin.


- Removed a ton of commands, and added certain options as aliases of a command.
Here are the commands that have now been aliased:

## Please note of a few things!!
1. -s is a flag, which allows you to silently ban a player.
2. (time) can be anything. With this, you can use either one of the following formats as your ban:
- s = seconds.
- m = minutes.
- w = weeks.
- mo = months.
- years = years.

If you don't define one of the following, then the ban won't work properly.

* /ban <player> (time) <reason> [-s]
- Alias of /ban is now /tempban!

- To perm ban a player, you can use: /ban <player> <reason> [-s]

* /mute <player> (time) <reason> [-s]
^^ This is for temp mutes.

- To perm mute a player, you can use: /mute <player> <reason>.

- To warn a player, use:  /warn <player> <reason> [-s]

- To unwarn a player, use: /unwarn <player>

- We've added all history checks to the punishment system.

## NOTES
- IP bans get instantly banned upon ban execution as well as their UUID to ensure they can't get back online, unless the punishment time is over.

## FOR HIGHERUPS 
- You can use /history <player> to check out another player's history, and /staffhistory <player> for staff history reasons only. /staffhistory is only displayed if a player that isn't console banned the user. /history doesn't care whether or not it's ran by console.

- You can now check another player's UUID. You can use /lastuuid <player>.

## More new Updates!?
- We've also fixed the ping issue, caused on SkyBlock Adventure, where it'd ping the proxy, rather than the player its self.

- We have a brand new Anti-VPN system, where if a VPN IP address joins, then it'll IP ban that specific IP. It's also improved as well.

## NOTE
The VPN detection will only ip ban the VPN ip, not the user.

What if somebody got false banned by the VPN Detection?
Then they will need to justify their false ban from the VPN detection, and gather proof of them not using a VPN (including apps, etc).

## What happens if somebody bypasses the VPN detection?
If this were to occur, then we would do the best we can to block certain bypass-able VPN applications. Though, we do tend to keep this plugin up to date as much as possible for more bypass patches.

- Added Command blocker to the network: Proxied side, and our backend servers! How this works:

Proxy: Blocked commands will now be blocked with our very own custom blocked command messages.
Backend servers: We’ve added our very own unknown command messages. No more plain old “Unknown command. Type /help for help” message. It’ll now say “Unknown command. Sorry!”
This will be apart of the network rebrand 2.0.0!

- Fixed "Unknown command" occurring even if the command exists.

- We're now using Pocketmine's translator for Unknown command messages. 

- You'll now get muted instead of banned after a certain amount of warns. (Automatically)

- Made this a feature-rich plugin, meaning this has lots of features, and customizability is endless! - In the future, we may release this plugin to the public. But it isn't confirmed yet.

- As of ServerSelector 2.0.0, we will be using Chest GUI's, rather than UI forms. (We may make this customizable for players in-game in the future). But for now, we will be doing it this way.

- Server Selector 2.0.0 / Network rebrand v2.0, we will be adding "enchantments" support on items that are in the server selector menu. Yes, everything is virtually configurable. ;D

- Fixed potential lag when opening the Server Selector too many times. Since that made a memory leak.

- Items now automatically update from the Server Selector menu to ensure you have the actual Live server queries and statuses.

- We've added item lores of each server item. That way, you will now know what each of the server are before joining.

- Fixed lore's not being able to be fully displayed - We've cut down some of the lore's we used to have, and made it easy, but advanced to use, and generally, customizable.

- Added "Status" section, and the amount of players online! LIVE STATUS, Update every 5 seconds.

- Added Server Selector cooldown, so you can use it every certain amount of seconds to prevent further issues with chest and inventories.

- All of this, isn't built from coding. This is all built within a config file that I coded in, which allows you to fully customize your looking, hella-cool server selector. There's nothing like it for MCPE.

- We've fully upgraded Social Spy to 2.0.0. This version has many bug fixes, less annoying issues, and generally implements a new feature.

- Fixed SocialSpy from not being disabled properly when you leave the server.

- When you rejoin the server, and you had socialspy enabled before, it should now still be enabled without the need to execute /ss again. There is a cache though, and the cache is: If the server restarts, then the server will automatically disable socialspy for everyone. This is for security reasons.

- Completely different formatting for SocialSpy's commands, and chat messages.

- Fixed an issue, where if you rejoined the server, it would act like it was enabled using SS, but it wouldn't display the commands publicly that you should be able to see via socialspy.

- We've fixed a potential CPU Leak on OP Prisons. We plan to do the same for OP Factions. Though, we don't know when this will happen yet.

- We've moved Lobby 2 and Lobby 3 servers to a different node. This should be the last time we ever do this for a while, unless more bugs occur.

- Moderators and Void Team can now access /socialspy, and will be able to receive incoming commands.

- Added OG OP Prisons to the network (Still need to add its server to the network).

- Moderators can now set ranks. We've done this because we simply don't have enough people for the job. We may remove this permission for Moderators if it starts to cause issues in the future.

- Added Gray Stained Glass around the Server Selector in Lobbies.

- Added Gray Stained Glass in /enchanter, /quest, /skills, /guide, /is settings, brewer, crusher, composter, and so much more!

- Fixed massive CPU leak to do with /enchanter.

- It's now easier to know where to put Item that you want to /enchanter with. You'll now need to put it in the Empty slot, which has only 1 empty slot available, thus making it obvious.

- Redesigned inventories / menus, renamed Inventory names to ensure they receive the best-styled-coded formats.

- Database no longer disables if tried enough (3 times). It'll keep being in a loop until the database is online.

- It'll now announce the database status in #network-status.

- We've added a new parameter to the functions named: isDown. This will allow the server to know whether or not the database is down. If true, it'll return as database offline. If false, it'll return as database online.

If the isDown parameter is set to null, then it means it'll return as the server's current status.

- It'll now display what server's database is currently offline/online. In most cases, they are the same. But it's best to be sure, right?

- The server will be unplayable as of the most part, when the database is offline. We are doing this method so people know that our servers may be offline due to this, so we're actually giving you a reason as to why the server's down or unplayable.

- The database will automatically go online once it's available again. (Untested, but will let you know of the results once back online).

We will be doing a massive update regarding Ranks recode! We've sorted out promotions, and new system, ranks, and more!

## How it will work
We will be having 6 new sub-ranks. Sub ranks, are ranks that are all ranks in one. The main rank for these sub ranks we currently offer, is called "VoidTeam". In game, it'll be called "Management".

The 6 new sub ranks will be:
## Community Manager
This rank will mean you're in charge of the community side, listening to players, and generally being professional.

## Head of Server Moderation
This rank will mean you're fully in charge of Server's moderation - Any hackers reported by staff will be directed to this role so the Head of Server Moderation can decide whether or not that's enough proof before banning.

## Staff Manager
This rank will mean you're fully in charge of Server's staff members, you can: Demote, promote, or anything as the such if you wanted to, as long as it's for a reason, and we organize it.

## Organization Manager
This job will mean you can organize things such as:
* Events
* Promotions/Demotions.
* Everything that goes on within the server or network.

## Supervisor
This role is where you would help the staff with anything they need - If it's to do with punishments, then this role will do just that! It'll help staff, show them how it's done, and generally, an experienced void team member.

## Executives
This rank is in charge of everything that goes on. This role is above all. The only executives would be the owners.

- Changed the way databases are connected.

- Database will now automatically reconnect as soon as the database is back online.

- The server will now automatically check if the database is available, and will publicly state so in #network-status.

- Changed Ultra and Void Rank colors in the public discord server. (Will also update for in-game soon)

- Builders can now see this channel (#announcements).

- Added a new Music Bot system: 

To use the bot, type -help in #bot-commands (on either one of the discords), and it'll DM you some useful help information.

- Fixed potential bot lag (May still occur, but not as bad to the point where it'll stop responding). 

- Upgraded ram for VoidMinerPE's bot.

- Added new roles (Executive, Supervisor, Staff Manager, Head of Moderation, and Community Manager). All displays what each of their job description in #rank-info.

- Fixed permissions for Void Team role(s) from not being able to do certain things.

- Moved Lobby 3, Lobby 2, OG OP Prisons, and VoidMinerPE bot to a different node, which should be less buggy. :D

- We've added a new option to the Server Selector configuration named: proxy-transfer. (More explained below).

## What's Proxy transfer?
- Proxy Transfer, is an option to allow/disallow proxy side transfers. If this is set to false in one of your servers, it'll use pocketmine's default transfer system. If you set it to true, it'll use the proxy transfer (Bungeecord transfer), where it'll automatically connect you to a server instantly.

- We now support Minecraft bedrock vanilla servers to the server selectors! Yay! (So it isn't just PMMP we support.  finally!)

- Added Anarchy to the server selector.

- Added OG OP Prisons to /server and to Server Selector.

- Now made Proxy Transfer an optional option, meaning you don't have to enter it on every server! If proxyTransfer is empty, and you haven't made it appear in the config.yml, then it'll automatically set to true, and use Proxy's transfer. I haven't seen any public plugins that do this. It's also good because it reduces disk space. No need to use proxyTransfer as an option if you're using a proxy.

## KEEP IN MIND
If you're using servers that aren't built or supported by Bungeecord (E.G Vanilla bedrock servers), then use proxyTransfer, and set it to false.

- Fixed crash when selecting a specific server that has proxyTransfer set to true (automatically only).

- Bug fixes, and improvements to do with Database status reappearing twice.

- Added new option to Maintenance Mode plugin: kick_early.

## What does "kick early" option do?
If you set this option to true, then it'll use prelogin() event, rather than onJoin(). This option is useful for if you're using a proxy, and not using the hub. You can put it on other gamemode's (not the hub) and it'll kick before you are locating. It's useful for if you want the proxy kick message to occur before they actually join the server.

We've changed how database brings out many bugs, including ranks, #last-seen messages, permissions, user permissions, and so much more!

I am happy to announce we've fixed an issue, where databases being offline would bring out errors, and would be unjoin able due to those errors. 

- We've also added a new function: isDatabaseConnected() to the core. This function is a boolean, and allows you to check if a database is connected. If not, returns false.

This function brings out a lot of bug fixes to do with erroring and errors, and makes the plugin stabled.

Now, this isn't confirmed, but we've added a new Anti-Bot system to the network, probably the first ever in MCPE. Here's information on it:

## What does it offer?
>> https://cdn.discordapp.com/attachments/700404144963452999/768191358527209523/BotFeatures.PNG <<

## Videos
Down below are all the videos, tested with Bot Sentry and how it handles attacks.
https://youtu.be/4NzfEGhOmpU
https://youtu.be/aKXecm4LSkE
https://youtu.be/xxzrRErtziU
https://youtu.be/J4_SKBPXcSw
https://youtu.be/_82XnqDQyb4
https://youtu.be/pdnUxiCR9tw

## Website Verification
Great news! We also offer a new verification website to ensure you're not a bot. This should only be used when the network's under attack.

## LINK
http://vmpeverify.ml/

 As of Network rebrand 2.0.0, we will be recoding our #last-seen's online and offline time system. Here's what we've changed:

- We now support the following time formatting to Online and Offline time:
* Days
* Months
* Years

- We no longer store formats that have both zeros on the end. As you can see in the old formatting screenshot, it always required a 00. This is not the case anymore! Time formatting is now so much easier to read than before!

- Changed time formatting entirely, remove useless time formatting that required zeros in both ways.

- Time formatting has changed forever; Before, it'll always include the full time formatting nonetheless. Now, it'll only add the small timing that has more than 0 hours, minutes, days, and years. For example:
If I left the server for 30 seconds, then the time formatting will only display "seconds", and not the other timings. If I left the server for 1 minute, then it'll display "Seconds and minutes". If I left the server for 1 hour, it'll display "hours, minutes, and seconds". If I left the server for 1 month, then it'll display "months, hours, minutes, and seconds". If I left the server for a year (1), it'll display "Years, months, hours, minutes, and seconds". SO basically, it's now all partial times, and not the exact but full timing. We got rid of this due to chat clogged. It's now easier and better to use partial time, rather than full time.

- Fixed timing problems from happening sometimes.

- Timing that has no timing due to you either just joined or left, then it'll return "blank". I do plan to add a message to those timings that were blank so people are aware why this error may be occurring. This example would be where if you just joined the server, OnlineTime would return blank because you just joined. Same goes for if you left, OfflineTime would return blank because you just left, and only counts whilst you've left the server. (Same goes for if you join a server).

- Bug fixes, and incredible improvements.

- In terms with last seen's timing recode, I've also added "Time unavailable" message whenever the time can't be entered. (Most preferably) when the online or offline time is 0 seconds. This only occurs when you leave the server, the offline time will state "Time unavailable" due to  offline time not updating until player fully leaves the server. (Same goes for onlinetime, and joining a server) will also return the same error.

Last seen's bug fix update:
- We've added a comma from every time formatted time to ensure it's more easier to read and understand.
