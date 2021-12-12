# undertale-true-stats
Enemy and player stats are effectively the (usually completely false) stats displayed through "CHECK" and "STAT"

Steps for patching:
1. Access your Undertale game files. On Steam, right click the game in the game list on the left, then select "properties", "local files", and "browse". Right click the "UNDERTALE" file that opens and select "show package contents".
2. Open a patching program, such as MultiPatch for Mac or "beat" for Windows. (I personally only have experience with MultiPatch.) Patch the patch file from here to the data.win or game.ios file
3. Move the resulting file to the opened game files. Then, rename the data.win / game.ios file to something else, such as "vanilla", and rename the patch file to data.win or game.ios (whichever the original file was named)



Beating the game from a fresh save file with the main "StatEditPatch" is nearly impossible, since Asgore has 80 defense. The highest possible achievable player attack is 87 (LV16, Worn Dagger, Temmie Armor, 8 Legendary Heroes), allowing the player to do 16 - 20 damage per turn against Asgore's 3500 HP. If you want a less authentic but more bearable challenge, use the "fairasgorepatch" patch file instead. This is identical, except that Asgore's defense will drop over time, as well as when talked to as a pacifist or when you eat the pie, as it does in the normal game (though it will not decrease below 0).
