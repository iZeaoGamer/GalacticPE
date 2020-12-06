## v2.0.2: Minor

## SkyBlock Adventure

- Completely re-coded, and cleaned-up Farming, Mining, and wood/leaves breaking. There still may be some lag, but most of it should of been fixed.

- Fixed ore generator duplications!

- Fixed everything from becoming broken.

- You can now mine wood and leaves freely on your island.

- Allow all blocks to be used on your island. Before, it'd block you from doing so!

- You can now use shears or your fist to mine leaves.

- Protected farms world!

- It'll now drop the appropriate item where you are upon breaking a specific block in the farming world.

- Fixed not being able to receive Wood from /farms.

- Fixed not being able to receive Leaves from /farms.

- Fixed crash when using a shovel to break dirt and other things from your island.

- Fixed not being able to receive Wheat and other farming materials from /farms.

- You can now break blocks freely in /mines, but there's an exception, which is you can't break blocks that aren't suppose to be broken!

- Blocks that are breakable in /mines will now auto generate again - We had this before, but got removed due to a lot of bugs - We've successfully brought it back, better than ever!

- Changed the way item teleportation works.

- Items that fall from your island will now teleport to your position, rather than at island spawn point. This is because of issues previously, where item teleportation would only work for island leader / the first user online.

- Fixed crash when dropping items.

- Use PlayerDropItem event more reliably than using task handlers. Yes, we are trying to use events more often, rather than using task handlers.

## Network / Globally

- Completely re-coded Scoreboards!

- Gamemode scoreboards will now be relied on Events, instead of per scheduler. This is to reduce CPU overload as well as preventing any current lag.

- Scoreboards will now update whenever you leave/join, so it updates without the need of a scheduler task.

- Fixed crash when setting ranks.

- Added more typehints to Network::class functions.

- Fixed crash when executing /tpa

- Added new functions: matchPlayer(), and matchNickname() to Network::class.

