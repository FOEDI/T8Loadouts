# T8Loadouts

Project based on [shield-development](https://github.com/project-bo4/shield-development) repo.

## Infos
- I'm providing the DLL and additional files in the Releases section.
- I've set All Elixirs and Talismans to 999.
- Regarding the additional files in the ``saves`` directory, this is some presets loadouts for each map/diffculty. I'm providing this because you cannot edit loadouts as you want, same thing apply for weapons attachements it's because the profile is level 1.
- I've used a private DLL to unlock the ability to edit loadouts/attachements. Sadly I cannot provide it.

## Installation
> prereq : in order to play using this version you need to have publisher files under LPC folder of your game directory. If its not the case then start original game through battle.net launcher once to get those downloaded.

- Extract the ``d3d11.dll`` in the root directory of your game.
- Launch the game once and close it to create the player profile.
- Edit ``project-bo4.json`` to change your nickname.
- Copy the content of one of the subdirectory from the ``saves`` directory to ``game_directory/player/bnet-xxxxx/`` and replace everything. (you can change loadout by closing the game and replacing the file with an other preset)
- Start the game using the ``BlackOps4.exe`` and enjoy!

> in case you want to play online using official servers you will need to remove the d3d11.dll from the game directory.

## Special thanks
- [@xRoskary](https://twitter.com/xRoskary) - for making loadouts
