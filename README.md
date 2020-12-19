# Castle Defense Mod for Quake 2

This mod works to implement a king of the hill style of game in quake 2. It will be a free for all
where players accumulate points for spending time on the hill.

## How to set the mod up:
1. Download this repository
2. Switch to the koh-mod-main branch
3. Open the quake2.sln file (if needed, allow visual studio to update to a mode it is compatible with)
4. Switch the solution configuration to `Release`
5. Build the game part of the solution
6. Copy the gamesx86.dll that was just made from the release folder of this repository and replace the
version in the KOH_Mod folder with the newly built version
7. In the root folder of your installation of Quake 2 (if you don't own Quake 2, you will need to 
buy and install it), create a copy the baseq2 folder and rename it KOH_Mod.
8. Copy everything in the repository version of KOH_Mod to the KOH_Mod folder you just created. 
Replace any files with the same name.
9. Create a fresh shortcut to launch Quake 2 and rename it to whatever you want to call this mod
10. Right-click on that shortcut and open its properties. In the target line, after the closing quote, 
add (not the space between the existing closing quote and what you add): `" +set game KOH_Mod`
11. After saving those changes, use the shortcut and enjoy my mod!

## Weapon changes
The weapons in here have been changed to imitate fantasy weapons and spells
1. Blaster -> Arrow
2. Shotgun -> Flame blast
3. Super Shotgun -> Flame wave
4. Machine Gun
5. Chain Gun
6. Grenade Launcher -> Summon spell
7. Rocket Launcher
8. HyperBlaster
9. Rail Gun
10. BFG10K -> Spawn Turret
11. Grenades -> 
