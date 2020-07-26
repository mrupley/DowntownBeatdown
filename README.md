# DowntownBeatdown

## About
Fight to the beat of the music in a rogue-like beat 'em up!

## How to play:
1. Open in UE4 Editor
2. Double click on the level "Main Menu" in Maps folder to open the level
3. Hit Play

## What is implemented:
The changelog will provide the most updated information, but currently the game has:
- 4 player couch co-op
- health bars, damage system, and a mock UI
- Paper2D animations for 2D characters in a 3D environment
- Camera system for 4 player movement, keeping the players centered and zooming the camera in and out as necessary
- Blueprint controlled animation system using a built in combat state machine
- 3D models from the UE4 marketplace, borrowing assets for 2D models as well
- A timing system used in animations, where the character can only attack or jump based on a 120 BPM timer with a built-in buffer
- Sample temporary music created by me that is available. It is located in Content/Music

## TODO in the near future:
- improve the UI, make connections to the name and current cash values
- create sample beatable levels

## TODO larger projects
- randomly generated level creation
- Bosses
- rogue-like system implementation for items, powerups, and new moves
- creation of different characters, all based on a different genre of music
