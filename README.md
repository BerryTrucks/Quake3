Build/Deploy using BlackBerry Native SDK
====================================
Below are the  instructions for building the Quake3 (id tech 3) game engine for BlackBerry 10 and PlayBook devices. 
The game engine source code included in this repository was ported from the open-source (under GPL license) directly from id Software.
The Quake3 maps/data files are not covered under the open-source agreement and must be provided by the developers wishing
to use the code.

Download the BlackBerry Native SDK 10
-------------------------------------
http://developer.blackberry.com/native/download/

Add your Quake Maps
-------------------
1. Create an `/accounts/1000/shared/misc/quake3/baseq3` directory / subdirectory 
2. Transfer your pak0.pk3 from the installation cd (found in /baseq3) into it. You can use the demo .pk3 found [here](https://www.mediafire.com/file/c2hd5n749ir7agp/pak0.pk3/file)
3. Start the game

Building from Momentics IDE
---------------------------
- Run BlackBerry Momentics IDE.
- Import the project from the repo directory "Quake3".
- Build the project.
- Debug or Run the project.
