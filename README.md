# Anti-ORfix
A program that deactivates "ORfix" in your mods.

**How to use:**
just put the file in your "mods" folder and launch it. The program automatically finds where "ORFix" is used and deactivates it, if you agreed to it.

**Output example:**
*Found "run = CommandList\global\ORFix\ORFix" in "*path to the file where it was found*"
Deactivate it? (y/n):* (Just type "y" if your mod is broken (**JUST possibly** due to this fix) and type "n" if your mod is working with this fix)

**Confirming changes:**
When all your .ini files is done, the program will ask you "Apply changes?", so you can undo all changes.

**Possible problems:**
1. The program found this line in the file, but you do not understand which mod this file belongs to.
2. At the end of the program you agreed to the changes, but then you changed your mind, and it’s too late.

**Solutions:**
1. Name the folder in which your mod is located in a convenient way (best of all - the name of what exactly the mod changes, as indicated in my example output in the console), then run the program again.
2. No backups dude. Life is hard :D (i'll add it in future, maybe. As for now just be carefull)
