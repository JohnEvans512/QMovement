# QMovement
Quake style first person movement controller for Unity game engine.

Usage: Add an empty GameObject to the scene, add Character Controller component and this script to GameObject,
set the camera in the script field (do not parent Camera to anything). It should be ready to go.
To use crouch feature, you'll need to set up "Crouch" button in the input settings, and uncomment "#define USE_CROUCH" line at the top of the script.
This code was made and only tested on Unity 5.6.7, so it most likely not gonna work right away on newer versions.
