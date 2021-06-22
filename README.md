# QMovement
Quake movement algorithm implementation for Unity game engine. By John Evans evans3d512@gmail.com

This is a simple first person movement controller, that uses the same core algorithm as Quake engines and their derivatives.
It uses the same logic, but the code is original, so it's not covered by Quake GPL licence, and is released as public domain.

Usage: Add an empty GameObject to the scene, add Character Controller component and this script to GameObject,
set the camera in the script field (do not parent Camera to anything). It should be ready to go.

To use crouch feature, you'll need to set up "Crouch" button in the input settings, and uncomment "#define USE_CROUCH" line at the top of the script.
