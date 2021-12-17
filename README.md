# undertale-true-stats
Enemy and player stats are effectively the (usually completely false) stats displayed through "CHECK" and "STAT"

Almost all bullets with their own damage values (of which their are MANY) are set to the damage value of their parent monster's attack stat. Any mid-battle Attack and Defense changes are removed (e.g. Toriel and Papyrus will not die instantly if attacked after they stop fighting.)
All damage calculations are changed to behave as though the player's Attack and Defense are 10 lower than they actually are, effectively bringing them in line with the displayed values in the "STAT" menu. To the player's advantage, the player's defense is no longer divided by 5 in the damage calculation, and monsters no longer get damage bonuses based on current HP when the player's current HP is above 20.



Steps for patching:
1. Access your Undertale game files. On Steam, right click the game in the game list on the left, then select "properties", "local files", and "browse". Right click the "UNDERTALE" file that opens and select "show package contents".
2. Open a patching program, such as MultiPatch for Mac or "beat" for Windows. (I personally only have experience with MultiPatch.) Patch the patch file from here to the data.win or game.ios file
3. Move the resulting file to the opened game files. Then, rename the data.win / game.ios file to something else, such as "vanilla", and rename the patch file to data.win or game.ios (whichever the original file was named)



The four patch files are nearly identical, with the exception of how Asgore is handled.

utstatpatch.bps: Asgore does indeed have 80 Defense and 3500 HP. The maximum possible attack you can achieve is 87, letting you do 16 - 20 damage. Including the 8 turns of eating Legendary Heroes, this takes over 200 turns. You at least have room for error, as he leaves you on 1 HP and Temmie Armor (needed for the maximum possible attack) heals you every other turn. I have not beaten this and do not plan to, but this is the most authentic version of the mod.

recommendedstatpatch.bps: Asgore still has his 80 Attack and Defense, but only 440 HP (the same as Toriel). To compensate, he no longer leaves you on 1 HP on otherwise lethal hits. Still a difficult challenge you need to plan your entire run around (as reaching the highest possible level has surprisingly little margin for error), but it takes 30 turns rather than 200. In an unrelated quality of life change, the encounter rate does not drop as you kill encounters in an area, making the required grinding much less tedious.

easyasgorepatch.bps: Asgore starts with 3500 HP, 80 attack and 80 defense, but all of his scripts are nearly unchanged, meaning his defense will decrease over time, and can be dropped by the pie or (as a pacifist) talking. In case you think this mod idea is interesting but don't want to have to grind, the game can be beaten at any level this way. I personally don't like this as wanting to face the true power of Asgore's supposed stats was the reason I made the mod in the first place, but if anyone actually finds this page I'm sure someone will prefer this version.

dentistvisit.bps: Identical to stateditpatch.bps, except Asgore does not leave you on 1 HP. Can you face Asgore at his true power? You shouldn't, but can you? 



By the way, did you know that even though Doggo, Dogamy, Dogaressa and Greater Dog don't count towards the Snowdin kill counter, RG01, RG02 and Muffet do count towards the Hotland kill counter?
