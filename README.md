SkyWars - PocketMine plugin

skywars

About

This is a PocketMine-MP (or forks) plugin which allows you to simply create multiple SkyWars mini-games ! 😁

This plugin was tested (and works) on:

 PocketMine-MP
not tested doesn't mean not working
android devices are not supported

Donate

Making a donation is an act of generosity. Your support, however modest it might be, is necessary.
Your donations helps me to continue creating plugins and improve this project!
This plugin helped you? Do you like it? Support it by donating!

Benefits: You will be credited in the source code as a generous donor 😄

GOAL: 💰 €8 / €20

Paypal Paypal: Donate 💸
Releases - Downloads

pre-Release 0.6 (May 7, 2016)
Beautiful config file with descriptions.
Spectator mode when a player dies.
Economy support for money rewards.
Reward command.
/sw join & /sw quit.
New sign knockBack type.
More death messages.
An option to set the player max health.
An option to choose if a player can drop items.
Added COBBLESTONE & DIRT to chests.
Bug Fixes that you don't need to know because are a lot 😏
pre-Release 0.4 (April 24, 2016)
Added air generator option.
Added a config for signs format.
Better and faster world reset.
Bug Fixes.
pre-Release 0.3 (April 14, 2016)
Maybe fixed #3
Added a sound on arena join.
Click here for other releases.

How to use

Installation

1. Download a plugin release (the last is recommended) from above.
2. Choose the SW_svile_php*.phar file according to your php version.
3. Extract the file into the plugins/ folder of your server and restart it.
4. Done, you can now join the game and create arenas (SkyWars_mini-games).

How to create an arena

1. Teleport yourself in the world where you would like to create it (not default one).
2. Now you can use the command /sw create [SWname] [slots] [countdown] [maxGameTime] to create an arena.
3. Go back in the arena world and depending on its spawns/slots use the command /sw setspawn [slot] x times.
4. Place a sign with sw in the 1st line and SWname in the 2nd.
5. Done, now players can tap the sign to join the game!

Commands

These commands cannot be used in console.

Command	Description
/sw	SW main command, shows the usage (subcommands)
/sw create [SWname] [slots] [countdown] [maxGameTime]	It's used for creating arenas.
- SWname indicates the name of the arena, is used for distinguish arenas, for example on join signs.
- slots indicates the number of spawns of the arena
- countdown is the time in seconds before the game starts.
- maxGameTime is the time in seconds after the countdown, if go over this, the game will finish.
/sw setspawn [slot]	It's used to set each spawn using the CommandSender position.
- slot indicates the number of the slot. Example: an arena with 4 slots need 4 different spawns; to set these 4 spawns you need to run this command 4 times: /sw setspawn 1, /sw setspawn 2, /sw setspawn 3, /sw setspawn 4.
If you set spawns above glass, it will be broken once the game starts.
/sw list	Displays the list of loaded arenas with the corresponding world + players playing in them. Example: TestArena [5/16] => TestWorld etc.
/sw delete [SWname]	This command just deletes an arena.
- SWname is the name of the arena that you must give to delete it
/sw signdelete [SWname|all]	Do you want to delete a join sign but you forgot where you placed it? This command can help you.
- SWname is the arena name, if gived, all the signs pointing to the given arena will be deleted.
- all If used as the arena name like /sw signdelete all, all the SW signs wil be deleted.
Are you thinking this command is useless? You'll change your idea about it when you'll have the need.😆
/sw join [SWname] [PlayerName]	Anyone except ops can use this command to join SW games.
- PlayerName can be used only by CONSOLE to force the player to join the specified arena.
/sw quit	Anyone except ops can use this command to left the current SW game.
Here there are some videos that explains how to create an arena in different languages:

Deutsch no video yet
English no video yet
Español no video yet
Français no video yet
Italiano no video yet
Have you made a video? Contact me to put it here❗️

Contacts

Kik: _svile_
Telegram_Gruop: 🔗 https://telegram.me/svile
E-mail: thesville@gmail.com
fell free to make pull requests and to contact me for any help.

License

This plugin is licensed under the GPLv3

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program. If not, see http://www.gnu.org/licenses/
