# 7D2D-Maps

Simply drop the 2k-towerDefenseMap folder into the 7 Days to Die "GeneratedWorlds" folder. For single player, create a new game and select that map. For multiplyer on a server, be sure your serverconfig.xml file has the "Gameworld" parameter set to this map name. When play session ends (when all players give up), start a new game.

Suggestions: 

Turn off zombie spawning. The enTowerDefense mod will spawn zombies using its own mechanism. 

Go into the gameevents.xml file for enTowerDefense...

Modify the "enAction_GiveCoins" code. For single player set added_item_counts to 60-90 and for multiplayer set to 20-30.

Modify the "enAction_GiveCoins_boss" code. For single player set added_item_counts to 300-450 and for multiplayer set to 100-150.
