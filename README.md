# skript-mc
simple commands in skript for my private minecraft server (in french)

## versions
- [Skript](https://github.com/SkriptLang/Skript) 2.5.3 (latest current version)
- [SkBee](https://github.com/ShaneBeee/SkBee) 1.10.2 (for the completion suggest)
- [skRayFall](https://dev.bukkit.org/projects/skrayfall) 1.9.25 (for the title in broadcast)

## Commands & Features
- /skr -> Reload main skript.
- /forceexecute -> Forces a player to execute a command.
- /broadcast <message> (or /bc) -> Make an announcement. (30s cooldown)
- /skull <joueur> (or /head, /tete) -> Drop a player's head.
- /clearchat (or /cc) -> Clear the chat history for everyone. (1mn cooldown)
- /sethome [nom] -> Define a teleportation point. (e.g. your house)
- /delhome [nom] -> Removes a teleportation point.
- /home [nom] -> Teleports you to a teleportation point.
- /listhome -> List of your teleportation points.
- /afk -> Announce that you are going to afk.
- /gmc [joueur] -> Change the game mode to creative.
- /gms [joueur] -> Change the game mode to spectator.
- /top -> Teleports you to the top of the block above you.
- /killall -> Kills all entities in the world except: player, armour stand, arrow, paint, item frame, boat, villager and entity with a name.
- /feed [joueur] -> Fills a player's food bar.
- /nickname [joueur] <surnom|off> (or /nick) -> Change your name or another player's name. (max 15 characters) - Put `off` as an argument to delete the nickname.
- /msg <joueur> <message> (or /whisper, /w, /tell, /t) -> Send a private message to a player.
- /reponse <message> (or /rep, /r) -> Sends a reply to a player.
- /rename <nom> -> Rename an item.
- /quelbloc -> Activate or deactivate the name of the block in front of you.
- /deacoudre -> Start a game of thimble (it teleports everyone to the platform, repeat the command to stop playing, the wools land by themselves) - if you use that for you, you should first build the platform and change the coordinates
- /casque (or /hat) -> Put the item in your hand on your head.
<br><br>
- It never rains.
- Home commands got autocompletion.
- Custom first join, join and quit message.
- Custom chat.
- Custom motd and max player
- The /clear command does not remove the equipment, to remove it use /clearall.
