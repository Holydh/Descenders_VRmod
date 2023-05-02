# Descenders VR mod

Here's a VR mod I worked on for Descenders using Bepinex and HarmonyX.
Comfortable and fun to play from start to finish even for motion sickness sensible person with the 3rd person views.
And awesome for the thrill seekers in first person view !

Some footage : https://youtu.be/NcM7NJ8S4C4

Things I patched :
- All the original camera views are there but tweaked to match well with VR. X and Z axis are stuck to horizon for every views except first person, no more camera shake, no more fov changes. Same for the "cinematic" cameras at the begining of the levels in Carrier mod.
- The first person view is coded from scratch with the same improvements I mentionned for the other views plus some personal tweaks to be more reactive than the original one but also more comfortable.
- UI modified to appear in worldspace, it is completely usable (with a gamepad or keyboard, no mouse) in every game mods.
- Every mod maps (at least those I tried) works well. Beware though some are ressources hungry and every custom UI of these maps won't render in VR but will appear on the VR mirror view on desktop. Some will freeze the VR view a bit like in the Igloo bike park map but just pressing A to skip the popup will get it back to normal.
- All the post processing effects are enabled for the VR camera. Post processing in VR is really ressource hungry so I'll may upload a version without it if some of you want it.

The whole game should be playable. Everything I tried worked nicely but since I just bought the game, there's lots of stuff I haven't seen/tested yet.

Feel free to open issues on this github page if you have bugs. I can't say if I'll keep working on it for long but I'll try my best.

## Installation

### If you want to easily switch between VR and non VR, make a backup or simply rename the "globalgamemanagers" file before installing this mod. This file is in "Descenders\Descenders_Data\", you can simply rename it into "globalgamemanagers.old" for example.

- Download and extract Bepinex v5.4.21 in the game's root folder "Descenders" (in steam, right clic on the game / manage / browse local files).
Bepinex v5.4.24 DL link : https://github.com/BepInEx/BepInEx/releases/download/v5.4.21/BepInEx_x64_5.4.21.0.zip
- Launch the game once for Bepinex initialization then quit it.
- Download the VR mod and extract it in the game's root folder like for Bepinex, click yes when prompted to overwrite a file.
VR mod DL link : https://github.com/Holydh/Descenders_VRmod/releases/download/Release/DescendersVRmod_v1.0.zip

That's it. Now connect your HMD and launch the game. If the VR view doesn't launch, add "-vrmode Oculus" or "-vrmode OpenVR" in the steam launch settings or on a shortcut of the game exe.

To swap back to non VR version, swap the globalgamemanagers with the one you previously backuped and rename the file "DescendersVRmod.dll" to "DescendersVRmod.dll.old" in "BepInEx\plugins".


## Credits for the Flatscreen2VR Discord and all it's people who worked on some nice guides for getting into VR injection.
https://discord.gg/5c49tFYKtF

Enjoy !
