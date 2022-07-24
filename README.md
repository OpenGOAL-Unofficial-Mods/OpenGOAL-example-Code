# OpenGoal-CheckpointRandomizer
Gives a random checkpoint after X amount of collectables (cells/orbs/scout flies), uses OpenGOAL project by the OpenGOAL team.

[Download latest](https://github.com/zedb0t/opengoal-checkpointrandomizer/releases/latest/download/OpenGoal-CheckpointRandomizer.zip)  

[![Github All Releases](https://img.shields.io/github/downloads/zedb0t/OpenGoal-CheckpointRandomizer/total.svg)]()

Tips/Notes:

- If you load a fresh file (0 cells), the checkpoint list is regenerated from the random/set seed when you collect the first cell.
- There is only one checkpoint list at a time, so if you load between different files don't expect it to switch back to a previous checkpoint list.
- If you reboot/close/crash the game, just be sure to load the right file. We backup the number of checkpoints used from the list every time you collect a cell, and use it to regenerate the checkpoint list/state in this scenario.