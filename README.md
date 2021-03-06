# deadcell ![image](https://img.shields.io/github/issues/EternityX/DEADCELL-CSGO.svg)

## Preface
Full CS:GO project files for [deadcell.cc](https://deadcell.cc/), for the OSHGui project, please see the [OSHGui repository](https://github.com/EternityX/DEADCELL-OSHGUI).

If you want a clean base without any features, please see the [deadcell SDK](https://github.com/alpine971/DEADCELL-SDK).

## Known issues
- Crashes and lots of them.
- Game will crash when using -d3d9ex as a launch option.
- Lots of code is unoptimized.
- Visuals will not rescale if you change resolution while injected.
- If you come across any more issues, please notify us via the issue tracker.

We are accepting any pull requests that fix any of the aforementioned issues.

## FAQ
### How do I add a hitmarker sound?
Create a **hitsounds** folder inside the **base** Counter-Strike Global Offensive directory.
Place as many **.wav** sound files as you want inside of it. Load the cheat and they will be under the hitsounds combobox.

### Where are config files stored?
Profiles are stored inside the **base** Counter-Strike Global Offensive directory under a folder named **profiles**.

You can share profiles with friends by navigating to the configuration tab inside the cheat and selecting **Export**. This will copy all profile data to the clipboard which you can then paste to a friend.

To import a profile, just copy all of the profile data and press **Import**. Make sure to save your profile by entering a name and pressing **Save**.

### How do I open the menu?
Press `INSERT`.

### How do I unload the cheat?
Press `END`.

## Credits 
- dex and maddie for their address, hash, module, netvar, pattern, pe, and vmt classes
- kn4ck3r for OSHGui
- nlohmann for a modern C++ implementation of JSON

## License
Licensed under the MIT License. See **LICENSE** for more details.

## Media
![image](https://i.imgur.com/DdAL0kC.png)
![image](https://i.imgur.com/0wAOPPj.png)
![image](https://i.imgur.com/b76kQH2.png)
![image](https://i.imgur.com/4ucjwAg.png)
![image](https://i.imgur.com/q5M8Qx4.png)
