# Contents
- [Full command list](https://github.com/brokenphilip/bulb-hub-commands#full-command-list)
- [Notes about command usage](https://github.com/brokenphilip/bulb-hub-commands#notes-about-command-usage)
- [Note 1 - Convar Faking](https://github.com/brokenphilip/bulb-hub-commands#note-1---convar-faking)
- [Note 2 - Item Attributes](https://github.com/brokenphilip/bulb-hub-commands#note-2---item-attributes)
  - [Most common format types](https://github.com/brokenphilip/bulb-hub-commands#most-common-format-types)
  - [Notes about attributes](https://github.com/brokenphilip/bulb-hub-commands#notes-about-attributes)
- [Note 3 - Entity Properties](https://github.com/brokenphilip/bulb-hub-commands#note-3---entity-properties)
  - [Some commonly used entity properties](https://github.com/brokenphilip/bulb-hub-commands#some-commonly-used-entity-properties)
- [Note 4 - Roll the Dice](https://github.com/brokenphilip/bulb-hub-commands#note-4---roll-the-dice)
- [Note 5 - Give Weapon](https://github.com/brokenphilip/bulb-hub-commands#note-5---give-weapon)
- [Note 6 - Player Conditions](https://github.com/brokenphilip/bulb-hub-commands#note-6---player-conditions)
- [Note 7 - Wearit](https://github.com/brokenphilip/bulb-hub-commands#note-7---wearit)
- [Note 8 - Discord Whitelist](https://github.com/brokenphilip/bulb-hub-commands#note-8---discord-whitelist)
- [Syntax and examples for commonly used commands](https://github.com/brokenphilip/bulb-hub-commands#syntax-and-examples-for-commonly-used-commands)
  - [sm_addattrib/sm_addwepatt](https://github.com/brokenphilip/bulb-hub-commands#sm_addattribsm_addwepatt-two)
  - [sm_addcond](https://github.com/brokenphilip/bulb-hub-commands#sm_addcond-six)
  - [sm_addtime](https://github.com/brokenphilip/bulb-hub-commands#sm_addtime)
  - [sm_cvar](https://github.com/brokenphilip/bulb-hub-commands#sm_cvar-eight)
  - [sm_entprop](https://github.com/brokenphilip/bulb-hub-commands#sm_entpropentfloatstringvector-three)
  - [sm_fcvar](https://github.com/brokenphilip/bulb-hub-commands#sm_fcvar-one)
  - [sm_forcertd](https://github.com/brokenphilip/bulb-hub-commands#sm_forcertd-four)
  - [sm_givew/sm_gimme](https://github.com/brokenphilip/bulb-hub-commands#sm_givewsm_gimme-five)
  - [sm_listents](https://github.com/brokenphilip/bulb-hub-commands#sm_listents)
  - [sm_setclass/sm_sc](https://github.com/brokenphilip/bulb-hub-commands#sm_setclasssm_sc)
  - [sm_wearit1/2/3](https://github.com/brokenphilip/bulb-hub-commands#sm_wearit123-seven)
  - [sm_forcewearit/sm_wearit](https://github.com/brokenphilip/bulb-hub-commands#sm_forcewearitsm_wearit-seven)

# Full command list
- `ftz_cheats` - [not a command] grants you access to cheat commands. note that for several cheat commands you'll need to use sm_fcvar [:one:](https://github.com/brokenphilip/bulb-hub-commands#note-1---convar-faking)
- `sm_addattrib` - adds an attribute to a player or an entity [:two:](https://github.com/brokenphilip/bulb-hub-commands#note-2---item-attributes)
- `sm_addcond` - adds a condition to a player [:six:](https://github.com/brokenphilip/bulb-hub-commands#note-6---player-conditions)
- `sm_addtime` - adds (removes if negative number) seconds to the round timer
- `sm_addwepatt` - adds an attribute to a player's weapon [:two:](https://github.com/brokenphilip/bulb-hub-commands#note-2---item-attributes)
- `sm_ban` - bans a player
- `sm_bring` - teleports someone to you
- `sm_cancelvote` - cancels an ongoing vote
- `sm_cap_disable` - disable the objective
- `sm_cap_enable` - enable the objective
- `sm_create_toy` - creates a physics toy (given a custom model, otherwise spawns scout's soccer ball)
- `sm_csay` - prints a HUD message to the center of the screen. equivalent to prefixing your chat message with @@@
- `sm_cvar` - sets a server cvar. this command also works with "hidden" cvars like sv_airaccelerate. for a complete list of console commands, see <https://developer.valvesoftware.com/wiki/List_of_TF2_console_commands_and_variables> [:eight:](https://github.com/brokenphilip/bulb-hub-commands#note-8---discord-whitelist)
- `sm_entprop` - sets an entity's integer property [:three:](https://github.com/brokenphilip/bulb-hub-commands#note-3---entity-properties)
- `sm_entpropent` - sets an entity's entity index property [:three:](https://github.com/brokenphilip/bulb-hub-commands#note-3---entity-properties)
- `sm_entpropfloat` - sets an entity's float property [:three:](https://github.com/brokenphilip/bulb-hub-commands#note-3---entity-properties)
- `sm_entpropstring` - sets an entity's string property [:three:](https://github.com/brokenphilip/bulb-hub-commands#note-3---entity-properties)
- `sm_entpropvector` - sets an entity's vector property [:three:](https://github.com/brokenphilip/bulb-hub-commands#note-3---entity-properties)
- `sm_fcvar` - fakes a server cvar to a player :one:
- `sm_forcedecal` - force-sets a player's objector/cosmetic decal. sm_decal for the non-admin version. do sm_decalhelp for info on how to use
- `sm_forcertd` - force rtd on a player, also accepts an optional specific roll you want to apply and an optional time [:four:](https://github.com/brokenphilip/bulb-hub-commands#note-4---roll-the-dice)
- `sm_forcewearit` - force equip cosmetics on a player [:seven:](https://github.com/brokenphilip/bulb-hub-commands#note-7---wearit)
- `sm_freeze` - without arguments, freezes the entity you're pointing at. with arguments, freezes a player with an optional amount of time
- `sm_gag` - prevents a player from using text chat
- `sm_gimme` - given an item index, equips you with that weapon [:five:](https://github.com/brokenphilip/bulb-hub-commands#note-5---give-weapon)
- `sm_givew` - given an item index, equips a player with that weapon [:five:](https://github.com/brokenphilip/bulb-hub-commands#note-5---give-weapon)
- `sm_goto_auth_bypass` - [not a command] grants you access to sm_goto without needing confirmation by the target
- `sm_goto_ban` - bans a player from using the goto plugin
- `sm_goto_listbans` - lists goto plugin bans
- `sm_goto_unban` - unbans a player from using the goto plugin
- `sm_grab` - grabs an entity (players, dropped weapons and ammo packs, vehicles, some physics props and some projectiles are supported)
- `sm_gravity` - sets a player's gravity
- `sm_hsay` - prints a HUD message to the bottom of the screen
- `sm_kick` - kicks a player
- `sm_listents` - searches for all entities with the given classname. wildcard character `*` is supported
- `sm_listrounds` - list all the playable rounds/stages for the current map
- `sm_map` - changes the map
- `sm_move` - moves a player to a specified team (none, spec, red, blu)
- `sm_mute` - prevents a player from using voice chat
- `sm_noclip` - applies noclip to a player. it's preferrable to bind "sm_noclip @me" for convenience
- `sm_nominate_addmap` - forces a map nomination
- `sm_playround` - opens a menu with all the playable rounds/stages for the current map, or plays the round with the given name if provided
- `sm_rainbow` - gives a player a rainbow or custom colored glow
- `sm_remattrib` - removes a player's or an entity's attribute. only works for attributes that you've applied via commands, for static attributes see [:two:](https://github.com/brokenphilip/bulb-hub-commands#note-2---item-attributes)
- `sm_removecond` - removes a condition from a player [:six:](https://github.com/brokenphilip/bulb-hub-commands#note-6---player-conditions)
- `sm_remwepatt` - removes a weapon's attribute. only works for attributes that you've applied via commands, for static attributes see [:two:](https://github.com/brokenphilip/bulb-hub-commands#note-2---item-attributes)
- `sm_rename` - renames a player
- `sm_resize` - resizes a player
- `sm_resizehands` - resizes a player's hands
- `sm_resizehead` - resizes a player's head
- `sm_resizetorso` - resizes a player's torso
- `sm_resizereset` - resets all of a player's resizes
- `sm_respawn` - respawns a player
- `sm_rweapons` - remove all weapons from a player
- `sm_say` - admin chat say. equivalent to prefixing your chat message with @
- `sm_sbuildex` - opens the engineer building spawning menu
- `sm_sc` - set a player's class
- `sm_setclass` - set a player's class
- `sm_sethealth` - set a player's health
- `sm_settime` - sets the round timer in seconds
- `sm_silence` - gags and mutes a player
- `sm_slap` - slaps a player
- `sm_slay` - kills a player
- `sm_starttime` - starts the round timer if stopped
- `sm_stoptime` - stops the round timer
- `sm_throw` - throws a grabbed entity
- `sm_tpb` - teleports you back to where you were before your goto
- `sm_unban` - unbans a player
- `sm_ungag` - ungags a player
- `sm_unmute` - unmutes a player
- `sm_unsilence` - ungags and unmutes a player
- `sm_vehicle` - opens the vehicle spawning menu
- `sm_votealltalk` - casts a vote to disable/enable alltalk
- `sm_voteban` - casts a vote to ban a player
- `sm_voteff` - casts a vote to disable/enable friendly fire
- `sm_votegravity` - casts a vote to set gravity
- `sm_votekick` - casts a vote to kick a player
- `sm_votemap` - casts a vote whether to change the server map (or to one of the several maps)
- `sm_voteslay` - casts a vote to kill a player
- `sm_wearit` - equips 5 cosmetics, an unusual and sets them to the specified paint [:seven:](https://github.com/brokenphilip/bulb-hub-commands#note-7---wearit)
- `sm_wearit1` - equips a cosmetic on slot 1 [:seven:](https://github.com/brokenphilip/bulb-hub-commands#note-7---wearit)
- `sm_wearit2` - equips a cosmetic on slot 2 [:seven:](https://github.com/brokenphilip/bulb-hub-commands#note-7---wearit)
- `sm_wearit3` - equips a cosmetic on slot 3 [:seven:](https://github.com/brokenphilip/bulb-hub-commands#note-7---wearit)

###### [back to top](https://github.com/brokenphilip/bulb-hub-commands#contents)
# Notes about command usage
console and chat commands are formatted differently, for example if you want to kick a player named George you should do `sm_kick george` in the console, OR `!kick george` or `/kick george` in the chat

if a command argument requires you to use a space, for example when renaming "George" to "Geo Rge", you need to use quotation marks `"`. **quotation marks only work for console commands**, thus for this example you would do `sm_rename george "Geo Rge"`

some of these commands like `sm_voteff` do not require any arguments, but if you're unsure about the rest feel free to type out the command without any arguments and you'll see which arguments it takes

for most commands, you can use "magic targets" to specify specific players:
- `@all` - all players,
- `@bots` - all bots,
- `@alive` - all alive players,
- `@dead` - all dead players,
- `@humans` - all non-bot players,
- `@aim` - current player you're aiming at,
- `@me` - yourself,
- `@!me` - everyone but yourself,
- `@red` - all red players,
- `@blue` - all blu players.

**example:** if you want to set your class to scout you do `sm_sc @me 1`

###### [back to top](https://github.com/brokenphilip/bulb-hub-commands#contents)
# Note 1 - Convar Faking
`sm_fcvar` basically tells a player that a server cvar is set when in reality it isn't. for example, if a server has `sv_cheats 0`, doing `sm_fcvar george sv_cheats 1` will make George's game think the server has `sv_cheats 1`

this command doesn't have much use, but faking `sv_cheats 1` on a player basically grants them access to all the clientside cheat commands (same ones that you gained access to in the HUD exploit, including but not limited to `thirdperson`, excluding but not limited to `noclip` which would require the server itself to have `sv_cheats 1`)

###### [back to top](https://github.com/brokenphilip/bulb-hub-commands#contents)
# Note 2 - Item Attributes
`sm_addwepatt` and `sm_removewepatt` are used to add or remove attributes of a player's currently held weapon. `sm_addattrib` and `sm_remattrib` are used to add or remove attributes of a player or a specific entity

static attributes are the ones which came with the item already, the only way to disable them is to nullify them, see below

## Most common format types
**(not all of these examples apply, see section below)**

#N, where N is a number, indicates an attribute ID from the list linked below (for example, #1 is damage penalty, #15 is no random crits etc...)

- `additive` - simple number (example: for #16, it defines how much health you get back from a hit), but it can also act like `or`, see below
- `or` - acts as an on/off switch for an attribute (example: for #20, 1 means it will crit against burning players, 0 means it won't)
- `percentage` - decimal number which acts like a percentage:
  - 1.0 is 100%, use a really small number like 0.0001 for example **(but not 0)** if you want to nullify it (example: for #1, 0.5 is 50% damage and 2.0 is 200% damage. note that #2 also accepts a percentage, the difference between #1 and #2 is purely cosmetic in this case)
- `inverted_percentage` - decimal number which acts like an inverted percentage:
  - 1.0 is 0% (use this if you want to nullify it), -1.0 is -200%, 3.0 is 200% (example: for attribute #5, 1.2 is 20% slower and 0.85 is 15% faster. note that #6 is similar to #5 in the exact same way as the above example)
- `account_id` - given a steamid `[U:1:bla]`, the account_id would be `bla`. **make sure to pass as int** (example: for attribute #186, my steam id is `[U:1:120694876]` and thus setting it to 120694876 will show "Gift from: brokenphilip")
- anything with `index` - usually values taken from the item schema (items_game.txt) (example: for attribute #134, 701 is `weapon_unusual_hot`, which can be added to a weapon)

## Notes about attributes
some attributes will not apply until you visit a resupply locker or respawn

only on this server, some attributes will be overridden by another plugin (balancemod for example) once you visit a resupply locker or respawn. this shouldn't really be an issue most of the time, but let me know if it is

added attributes will be lost if you switch loadouts or classes (but not if you visit a resupply locker or respawn), but dropping weapons with modified attributes will preserve said attributes on the dropped weapon

please note that some attributes are purely cosmetic, and also not all attributes will work on all weapons in all cases, this is a tf2 limitation. if there's a specific combination you'd *really* like to try out, let me know and i'll look into making a custom plugin for it

string based attributes (such as #796 for minmode viewmodel offsets) can **NOT** be applied under any circumstance. doing so can potentially crash the server

**not all format examples from above apply.** for a list of all attributes, including seeing which weapon uses said attributes and what values they have said attributes said to, see https://wiki.teamfortress.com/wiki/List_of_item_attributes

for a list of all hidden attributes, see [tf2hiddenattribs.txt](https://github.com/brokenphilip/bulb-hub-commands/blob/main/tf2hiddenattribs.txt)

###### [back to top](https://github.com/brokenphilip/bulb-hub-commands#contents)
# Note 3 - Entity Properties
in layman's terms, entity properties are named variables attached to entities. for example, player entities have `m_iHealth` which represents their health. most of it is very technical, so please **don't use it unless you know what you're doing**, because it can very quickly lead to client and/or server crashes

use one of the commands depending on whether the entity property in question accepts an integer, an entity index, a float, a string or a vector. **please mind the types**, while they (most likely) won't crash the server, they will not succeed and no error message will be sent back - if after typing a command you don't get a response, chances are you used the wrong type

for a full list or entity properties, see [netprops.txt](https://raw.githubusercontent.com/brokenphilip/bulb-hub-commands/main/netprops.txt) (use the command with the `send` parameter) and [datamaps.txt](https://raw.githubusercontent.com/brokenphilip/bulb-hub-commands/main/datamaps.txt) (use the command with the `data` parameter) respectively

## Some commonly used entity properties
- `m_iHealth` (send for players, data for the rest) (integer) - for a bunch of entities (including but not limited to players, bosses and breakables), their current health
- `m_bGlowEnabled` (send) (integer) - for players and npcs, 0 = outline disabled, 1 = outline enabled
- `m_iDecapitations` (send) (integer) - for players, the amount of heads they have
- `m_nStreaks` (send) (integer) - for players, their killstreak
- `m_iFOV` (send) (integer) - for players, their FOV (0 to reset)
- `m_flRageMeter` (send) (float) - for players, their rage meter (phlog for example, 100.0 is 100%)
- `m_nCurrency` (send) (integer) - for players, the amount of MvM money they have
- `m_flChargeLevel` (send) (float) - for mediguns, their charge (1.0 is 100%)
- `m_vecOrigin` (send) (vector) - the entity's position
- `m_iName` (data) (string) - the entity's name (NOT classname, NOT the player name)

###### [back to top](https://github.com/brokenphilip/bulb-hub-commands#contents)
# Note 4 - Roll the Dice
for a list of rtd effects, see https://github.com/Phil25/RTD/blob/master/configs/rtd2_perks.default.cfg

please note that the Flying rtd is broken and has been removed from the server

###### [back to top](https://github.com/brokenphilip/bulb-hub-commands#contents)
# Note 5 - Give Weapon
for a list of item indexes, see https://wiki.alliedmods.net/Team_fortress_2_item_definition_indexes

###### [back to top](https://github.com/brokenphilip/bulb-hub-commands#contents)
# Note 6 - Player Conditions
for a list of conditions, see https://wiki.teamfortress.com/wiki/Cheats#addcond

###### [back to top](https://github.com/brokenphilip/bulb-hub-commands#contents)
# Note 7 - Wearit
**the wearit plugin has been disabled until further notice, if you'd like for it to be re-enabled for whatever reason please let me know**

for a list of paints, see https://docs.google.com/spreadsheets/d/1OzC4M_Vjj1BjdebQdlSn8JjnKywSUSayGNI6GH4EJIg/edit#gid=0

for example, slate is 1, purple is 2, greed is 22, debonair is 23, waterlogged is 29

values above 29 will be treated as integers, which you can use to set **custom colors** for items! to do this, [pick a color](https://www.google.com/search?q=color+picker), copy its RGB values and use an [RGB to int converter](https://www.checkyourmath.com/convert/color/rgb_decimal.php). due to the limitation that fixed colors use numbers from 0 to 29 inclusive, you can't use RGB values (0, 0, 0 to 29). If you wish to paint a cosmetic fully black (RGB (0, 0, 0)) for example, you will have to use 65793 instead (RGB (1, 1, 1))

for a complete list of cosmetics and effects, see items_game.txt (located in `Team Fortress 2\tf\scripts\items`)

most of the time you can find cosmetics by searching (CTRL+F) their name, for example:
```
"30036"
{
	"name"		"The Filamental"
...
```
The Filamental's ID is `30036`

unusual effects have their own names though, and as such might be harder to find, for example:
```
"702"
{
	"system"				"weapon_unusual_isotope"
...
```
the Isotope effect's ID is `702`

alternatively, you can also use bptf's particle list here: https://backpack.tf/developer/particles

###### [back to top](https://github.com/brokenphilip/bulb-hub-commands#contents)
# Note 8 - Discord Whitelist
use this to enable the whitelist: `sm_cvar sm_discord_whitelist 1` (likewise, set it to 0 to disable the whitelist)

1. whitelist disabled, no password: anyone can freely join
2. **whitelist enabled**, no password: only verified discord members can join
3. whitelist disabled, **with password**: only people with the password can join
4. **whitelist enabled, with password**: only verified discord members OR (not and) people with the password can join

###### [back to top](https://github.com/brokenphilip/bulb-hub-commands#contents)
# Syntax and examples for commonly used commands
for other generic sourcemod commands not listed here (such as `sm_kick`, `sm_slap` etc...), see https://wiki.alliedmods.net/Admin_commands_(sourcemod)

arguments in "< >" are required, while arguments in "[ ]" are optional

## sm_addattrib/sm_addwepatt [:two:](https://github.com/brokenphilip/bulb-hub-commands#note-2---item-attributes)
`sm_addattrib/sm_addwepatt <target> <attrib> <val> [pass]`

- target (addattrib) - pass the player name to set an attribute to the player OR `##index`, where index is the entity index (useful for items you can't set as your active weapon, ie. spy watches or cosmetics)
- target (addwepatt) - pass the player name to set an attribute to the player's currently held weapon
- attrib - `#num`, where num is the number of the attribute
- val - value to set this attribute to
- pass - `yes` if you want to pass as int, leave blank otherwise

**example:** implying entity with index 123 is a tf_weapon_invis, `sm_addattrib ##123 #35 1.5` will give it attribute 35 (cloak regen rate) and set it to +50%

## sm_addcond [:six:](https://github.com/brokenphilip/bulb-hub-commands#note-6---player-conditions)
`sm_addcond <target> <condition>`

- target - player name
- condition - the number of the condition

**example:** `sm_addcond george 27` will apply the mad milk effect to George

## sm_addtime
`sm_addtime <time>`

- time - adds to the round timer this many seconds. use negative values to deduct instead

**example:** `sm_addtime -20` will shave 20 seconds off the round timer

## sm_cvar [:eight:](https://github.com/brokenphilip/bulb-hub-commands#note-8---discord-whitelist)
`sm_cvar <cvar> [value]`

- cvar - name of the cvar to query
- value - if not passed, displays current value of cvar. if passed, sets the cvar's value to this

**example:** `sm_cvar sv_cheats` displays the server's current sv_cheats value. please note that, only on bulb hub, when the server has `sv_cheats 1` set, due to the limitation of the `ftz_cheats` plugin, NON-admins will STILL NOT be able to use commands such as `noclip` (you can grant them noclip using the command `sm_noclip <name>`, but they will not be able to toggle it freely)

**example:** `sm_cvar sv_password 123` sets the server's password to 123. if you want to remove the password, set it to `none`

## sm_entprop(ent/float/string/vector) [:three:](https://github.com/brokenphilip/bulb-hub-commands#note-3---entity-properties)
`sm_entprop(ent/float/string/vector) <entity> <send/data> <prop> [value1] [value2] [value3]`

- entity - the index of the entity
- send/data - `send` if using netprops.txt, `data` if using datamaps.txt
- prop - the name of the property, **case sensitive**
- value1 - leave blank to display the current value of the property. otherwise, uses an integer, entity index, float, string (remember to use quotation marks to include spaces, see above) or the first vector value
- value2 - second vector value, blank if not a vector
- value3 - third vector value, blank if not a vector

**example:** implying entity with index 1 is a player
- `sm_entprop 1 send m_iHealth` displays said player's current health
- `sm_entpropvector 1 send m_vecOrigin 0 0 0` sets the player's origin to the (0, 0, 0) point of the map

## sm_fcvar [:one:](https://github.com/brokenphilip/bulb-hub-commands#note-1---convar-faking)
`sm_fcvar <target> <cvar> <value>`

- target - player name
- cvar - the cvar to fake
- value - the value of the cvar to fake

**example:** `sm_fcvar george sv_cheats 1` fakes sv_cheats 1 to George

## sm_forcertd [:four:](https://github.com/brokenphilip/bulb-hub-commands#note-4---roll-the-dice)
`sm_forcertd <target> [perk] [time] [override]`

- target - player name
- perk - perk name, leave blank for random
- time - perk duration, leave blank for default (usually 20s)
- override - `1` override class restrictions, leave blank otherwise

**example** `sm_forcertd george smite` smites George

## sm_givew/sm_gimme [:five:](https://github.com/brokenphilip/bulb-hub-commands#note-5---give-weapon)
`sm_givew <target> <index>`

`sm_gimme <index>`

- target - player name
- index - the weapon's item index

**example:** `sm_givew george 0` gives George a Bat

## sm_listents
`sm_listents <query>`

- query - the classname to search for

**example:** `sm_givew tf_weapon_*` searches for all entities that start with `tf_weapon_`, the first number of every search will be the entity index, and more information might be available in the parenthesis (model name, entity name `m_iName`, position)

for a list of all supported entities, see https://developer.valvesoftware.com/wiki/List_of_Team_Fortress_2_Entities

## sm_setclass/sm_sc
`sm_setclass/sm_sc <target> <class>`

- target - player name
- class - class name, or a number from 1 to 9 representing said class. `random` or 0 picks a random class

**example:** `sm_sc george 7` sets George's class to Sniper

## sm_wearit1/2/3 [:seven:](https://github.com/brokenphilip/bulb-hub-commands#note-7---wearit)
`sm_wearit1/2/3 <item>, [effect], [paint]`

- item - sets the item for the 1st, 2nd or 3rd slot depending on the command. 0 to reset
- effect - unusual effect index
- paint - paint index, or int value of the rgb

**example:** `sm_wearit2 105, 248, 13` sets your 2nd cosmetic to a mann co. orange starfire brigade helm

## sm_forcewearit/sm_wearit [:seven:](https://github.com/brokenphilip/bulb-hub-commands#note-7---wearit)
`sm_forcewearit <target> <item1>, [item2], [item3], [item4], [item5], [effect], [paint]`

`sm_wearit <item1>, [item2], [item3], [item4], [item5], [effect], [paint]`

**mind the commas wherever you see them.** also, these commands work regardless of class cosmetic restrictions

- target - player name
- item1 - sets the 1st item, 0 to reset
- item2 - sets the 2nd item, 0 to leave blank
- item3 - sets the 3rd item, 0 to leave blank
- item4 - sets the 4th item, 0 to leave blank
- item5 - sets the 5th item, 0 to leave blank
- effect - the unusual effect, **applied to item1**, 0 to leave blank
- paint - paint index, or int value of the rgb, **applied to all items**, 0 to leave unpainted

**example:** `sm_wearit george 105, 30544, 30036, 162, 30551, 248, 13` applies
1. the brigade helm,
2. the north polar fleece,
3. the filamental,
4. max's severed head,
5. the flashdance footies,
6. the starfire effect on the brigade helm,
7. mann co. orange paint

in that order, to George

![image](https://github.com/brokenphilip/bulb-hub-commands/assets/13336890/558209cd-a170-456e-b971-bc058baee010)

###### [back to top](https://github.com/brokenphilip/bulb-hub-commands#contents)
