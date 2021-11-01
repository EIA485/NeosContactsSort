# NeosContactsSort

A [NeosModLoader](https://github.com/zkxs/NeosModLoader) mod for [Neos VR](https://neos.com/) that sorts contacts Better™.

Relevant Neos issue: [#2596](https://github.com/Neos-Metaverse/NeosPublic/issues/2596).

## Sorting Order
1. Friends with unread messages
2. Ties broken by online status
   1. Online Friends
   2. Neos Bot
   3. Away Friends
   4. Sent Requests (background color changed from gray to yellow!)
   5. Offline Friends
   6. Incoming Friend Requests
3. Further ties broken by username

## Installation
1. Install [NeosModLoader](https://github.com/zkxs/NeosModLoader).
2. Place [NeosContactsSort.dll](https://github.com/zkxs/NeosContactsSort/releases/latest/download/NeosContactsSort.dll) into your `nml_mods` folder. This folder should be at `C:\Program Files (x86)\Steam\steamapps\common\NeosVR\nml_mods` for a default install. You can create it if it's missing, or if you launch the game once with NeosModLoader installed it will create the folder for you.
3. Start the game. If you want to verify that the mod is working you can check your Neos logs.
