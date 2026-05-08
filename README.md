# SCP-CB RTX Files
These are the RTX Remix Project files for SCP - Containment Breach RTX Remaster, a fan-made mode updating the visuals 
of SCP - Containment Breach as well as adding RTX Compatiblity for Ray-traced PBR textures, shadows and realtime Lighting through RTX Remix. 
RTX Remix has project files that rely on what are called "Captures" as their title suggests they are captures of several rooms from the game that
we take and attach lights and materials to the **hashes** of these captures that appear in the mod.. normally all you need to run the game with RTX 
is a packaged mod .usda file, so this repository is less about what is played in game, and more for if you wanted to edit lighting yourself or access
the project files for said lighting process inside the RTX Remix toolkit and software.
## Installation Guide
If you download the mod of the game from this github repository for [SCP-CB RTX Remaster](https://github.com/SCPCB-RTX-Remaster/scpcb-rtx) You should have the latest version of the game and the 
files necessary for running RTX ingame, delete the "rtx-remix" folder to have fresh capture folder for remix. Go into game with RTX, start a new game and once you're in a playable room press `Alt` + `X` 
to open up the RTX Options menu, go into "Developer Menu" then the "Captures" tab, and create a new capture (you may need to untick Enhancements if they are checked on) once the capture is captured, close the game,
and go into RTX Remix Toolkit found in the Nvidia App, you'll want to start a new proejct from a rtx-folder, choose your mod/game directory, and RTX Remix will prompt you to choose a spot to create the project folder, 
this can be anywhere but remember that RTX Remix doesn't like whitespaces so if you have a space in your Windows Username such as `C:\Users\Inward 3D\Desktop` (like I did :D) it won't be able to use that as a directory
for the project files.. just something to keep in mind.. after that, create your project. Close the RTX Remix Toolkit and copy over the files found in this reponsitory to your project folder. 

Any changes you make to the mod in said project will now automatically update in your version of the mod and game.. that being said you can package the mod as well which will just be found in the "package" folder of
your project folder.

## Frequently Asked Questions

Need to write this :P

### **Why make this?**

Ray-tracing is awesome :D     But also.. 

SCP-CB is an amazing indie horror game, probably one of the best of its time and even still today.. but this game is severely outdated due to the engine it was built upon
Blitz3D but also the fact that this engine (*was* up until v1.3.12) DirectX 7. I actually created a parady of the Portal RTX Trailer when that was released to parady SCP-CB having Ray-tracing 
compatibility, I say parady because at the time it seemed impossible.. but serveral people commented and asked if I would ever work on a mod if **did** become possible, and I said I would.. 
If you want to watch this parady video it can be found on my YouTube Channel as well as updates to this mod and other stuff I work on:
[SCP Containment Breach with RTX Parody Trailer](https://www.youtube.com/watch?v=faGr7dCYDQg)

Two years after I made that video; I found a discord server with people tinkering with wrappers to make RTX Remix run with DirectX 7 games.. and the rest is history. 

