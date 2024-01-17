# flowerbraten
I found multiple clients to be just not as much vanilla orientated as i wished them to be so, so basically decided to create my own one with features that i both missed from other games/found in other clients. I added more and more features over the time though.
This list is most likely imcomplete (or maybe not, its really not that much and I like to stay mysterious about it) but ive tried to make every feature as optional as possible.

this client was initially based on p1xbraten but got more and more features over the time. Please refer to the credits if you are interested in what work was involved here.
Note that the following feature list is a work in progress, some features couldnt get added to the main repository due to time reasons (and me needing to rework on them).

## Features

- **Scoreboard:**
    [x] showfrags
    [x] showdeaths
    [x] show kpd
    [x] show accuracy
    [x] show damage (dealt and received)
    [x] show spectator's modelicon
    [] hide icons option
    [x] show current flagholder
    [] alternative scoreboard possibility (no teamname backgrounds)
    [] show level next to bots name 
    [] show specific models only (dont draw other icons)
    [] possibility to change text color
    [x] show teamsize
    [] always show all clientnumbers (while also respecting the duplicate names)
    [] option to use p1xbraten's 'clean' scoreboard
    [] option to delete all seperator lines
    [] option to set scoreboard space
    [] highlightname 2 possibility

- **HUD:**
    [x] fragmessages (currently only for the player1)
    [] advancedfragmsgcoloring (player1 gets colored)
    [] event messages (HB, QUAD, FLAGSCORE, FLAGRETURN, FLAGTAKE, etc.., FRAGS, SUICIDES)
    [x] show team names and 'flagtaken' display
    [x] players alive display (htop-style bars) if teammode/ctf 'good' and 'evil' -> else just a 'alive' counter
    [] lagometer display -> pj,  standard deviation pj, ping and packetloss display, with different colors (note that the pj is accumulated from all players) -> option to display pj on hudplayer
    [x] basic and advanced weapon and game stats (damage, accuracy, frags, kpd..)
    [x] session length displayed next to fps/time
    [x] option to hide hud but not crosshair (for movie purposes)
    [x] flagtimer, for flagrun purposes
    [] velocity display

- **Serverbrowser:**
    [] extinfo based serverpreview (with stats)
    [x] server search possibility (mode, map or description)

- **Game:**
    [x] mod specific config to differ between vanilla and mod stats
    [] option to save localstats into global and reset local -> txt creation that saves these stats with timestamp and opt reason
    [] stats config
    [x] screenshot output message
    [x] spectators able to use teleports and move while game paused
    [x] possibility to set/force specific playermodels
    [x] chat only logfile - pm's might not get included since those are servermessages sometimes
    [] dated, unique logfiles for each session (.bat change needed)
    [] save all used names, save it in a txt file
    [x] renameprotection
    [x] sessionlength - how long is the client running
    [x] console history 
    [x] automatic, mod specific, menu creation
    [] nextteamfollow, TODO: eventfollow, flagfollow, etc..
    [] opt to show custom backgrounds..
    [x] clientsided /stats command, -1 -> all player, no arg -> player, "cn" -> specific cn stats, TODO: -2 -> everyones but spectators stats
    [] advanced teamstats bounded into a gui, average and accumulated ping, damage, flags stolen, frags -> todo: add more events, names etc
    
- **Weapon:**
    [x] option to change trail colors for all weapons
    [] option to set rifle trail to lighting (also color setable)

- **planned, but never added:**
    [] clientsided demos
    [] demobrowser, with extended possibilities






