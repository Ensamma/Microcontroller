# Mass Release

**Related Programs:**
- **Microcontroller:** [MassRelease](https://github.com/PokemonAutomation/Microcontroller/blob/master/Wiki/Programs/NintendoSwitch/MassRelease.md) (this program)
- **Computer Control:** [Mass Release](https://github.com/PokemonAutomation/ComputerControl/blob/master/Wiki/Programs/NintendoSwitch/MassRelease.md)

The microcontroller and computer-control versions of this program are functionally identical.


## Program Description

MassRelease will release entire boxes of Pokémon. The main use case is getting rid of breedjects, non-shiny fossils, and other hunts.

<img src="images/MassRelease-0.jpg">

### Setup of Settings

1. Text Speed: Fast
2. Casual mode: Off

### Box Setup

1. Place entire boxes filled with Pokémon to be released consecutively.
2. All boxes marked for deletion must be full.
   1. This program does not tolerate partial boxes.

### Instructions

1. You must in the box system.
2. The cursor must be over the 1st Pokémon in the box. (top-left corner)
3. The cursor must be red. (not blue or green)
4. Start the program in the [Change Grip/Order Menu](https://github.com/PokemonAutomation/SwSh-Arduino/wiki/Appendix:-ChangeGripOrderMenu).

   > Once started, this program will release the specified number of boxes consecutively starting from the current box.

### Required Parameters:
- `BOXES_TO_RELEASE`: You must specify the number of boxes to release.

### Safety Recommendations:
See [Maximizing Switch Stability](https://github.com/PokemonAutomation/SwSh-Arduino/wiki/Appendix:-MaximizingSwitchStability).


## Options

Most of the options here are self-explanatory.
This program does not use the global setting to bypassing the system update window. It has its own setting for that. (See below.)

<img src="images/MassRelease-1.png">

### Dodge System Update Window:

When enabled, the program will dodge the system update window. Do not set this option if the system update window is not present. Unlike other programs, MassRelease will not be able to tolerate the extra button presses if they land in the box system.


<hr>

**Discord Server:** 

[<img src="https://canary.discordapp.com/api/guilds/695809740428673034/widget.png?style=banner2">](https://discord.gg/cQ4gWxN)
