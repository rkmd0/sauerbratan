# flowerbraten
> [!NOTE]
> This is a WIP Project. Please be aware that the functionality and features are still under development. You will run into bugs or problems

I found the popular clients to be just not as much vanilla orientated as i wished them to be so, so basically decided to create my own one with features that i both missed from other games/found in other clients. I added more and more features over the time though.
This list is most likely imcomplete (or maybe not, its really not that much and I like to stay mysterious about it) but ive tried to make every feature as optional as possible.

this client was initially based on p1xbraten but got more and more features over the time. Please refer to the credits if you are interested in what work was involved here.
Note that the following feature list is a work in progress, some features couldnt get added to the main repository due to time reasons (and me needing to rework on some them).

## Features

- **Scoreboard:**
   - `showfrags` 0-1
   - `showdeaths` 0-1
   - `showkpd` 0-1
   - `showaccuracy` 0-1
   - `showdamage` 0-2
   - show spectators modelicon: `showspecicons 0-1`
   - show/hide all playericons: `showplayericon 0- 1`
   - show current flagholder: `showctfflagicons 0-1`
   - `alternativescoreboard 0-1`
   - show bot level instead of their clientnum: `showbotskill 0-1`
   - possibility to change text color: `scoreboardtextcolor`
   - `showteamsize 0-1`
   - show all clientnumber while respecting duplicates: `showclientnum 2`
   - option to use p1xbraten's scoreboard
   - option to delete all seperator lines
   - option to set scoreboard space
   - advanced highlightname possibility: `highlightname 2`
   - ~~show specific models only (dont draw other icons)~~

- **HUD:**
   - fragmessages (currently only for player1): `fragmsg 0-1`
   - opt to switch player1 coloring from white to yellow: `advancedfragmsgcoloring 0-1`
   - Eventmessages (currently only for QUAD & HB): `eventmsg 0-1`
   - display for team names and 'flagtaken' symbol: `playercounter 0-1`
   - basic and advanced weapon and game stats: `hudstats 0-1`
   - turn off advanced weaponstats: `showweaponstats 0-1`
   - session length displayed next to fps/time: `sessionlendisplay 0-1`
   - option to hide hud but not crosshair (for movie purposes): `hidehud 0-2`
   - flagtimer (for flagrun purposes)
   - ~~velocity display~~
   - ~~lagometer display -> pj,  standard deviation pj, ping and packetloss display, with different colors (note that the pj is accumulated from all players) -> option to display pj on hudplayer~~
   - ~~ (advanced) eventmsg for flags with different outputs for score and take~~

- **Serverbrowser:**
   - server search possibility (mode, map or description)
   - ~~extinfo based serverpreview (with stats)~~
   - ~~hideserver possibility~~

- **Game:**
   - mod specific config to differ between vanilla and mod stats
   - screenshot output message
   - spectators able to use teleports and move while game paused
   - possibility to set/force specific playermodels: `setplayermodel -1-4`
   - opt. renameprotection with console warning: `renameprotection 0-1`
   - sessionlength - how long is the client running
   - automatic, mod specific, menu creation: `bratanmenu 0-1`
   - clientsided weaponstats command (no input:player1 stats): `stats -1|cn|""`
   - ~~nextteamfollow, TODO: eventfollow, flagfollow~~
   - ~~opt to show custom backgrounds ~~
   - ~~advanced teamstats bounded into a gui, average and accumulated ping, damage, flags stolen, frags~~
   - ~~option to save localstats into global and reset local -> txt creation that saves these stats with timestamp and opt reason~~
   - ~~stats config~~
   - ~~ave all used names, save it in a txt file~~
   - ~~clientsided duel and cw stats~~

- **Console**
   - chat only logfile (pm's might not get included since those are servermessages): `allowchatonlylog 0-1` and `allowchatonlylogdemo 0-1`
   - console input history: `savehistory 0-1` 
   - dated, unique logfiles for each session (.bat change needed, also: additional feature missing)
   - added color-loop: `frequencymultiplier 0-10` (0 -> no changes)
   - consearch possibility: `consearch <input>`

- **Weapon:**
   - option to change trail colors for all weapons
   - option to change rifle trail color (on loop) and change to lighting (with or without colorloop)

- **planned, but never added:**
   - [] clientsided demos
   - [] demobrowser, with extended possibilities






