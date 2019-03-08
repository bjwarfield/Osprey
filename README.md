# Osprey Assault
QT C++ game project based on a similar [Java Game](https://github.com/bjwarfield/InvadersFromSpace) inspired by the Shoot'em up gmae[Ikaruga](https://en.wikipedia.org/wiki/Ikaruga)

Project implements Object Orientation, Forms, Event Handling, Draw Functions, Buffering, File Stream. 

Original project included High Score functinality using a remote sql connection and user login. Features removed for improve security and portability.

## Contols
+ For Menu: Arrow Keys and Enter.
+ For Gameplay:
	- Arrow keys: Movement
	- z: Laser
	- x: Swap Polarity
	- c: Fire Charge Beam

## Gameplay
Top-Down SHMUP (Shoot-em-up). Shoot enemies ships while avoiding incoming fire of opposite polarity and absorbing incoming fire of the same polarity (White or Black). Each absorbed shot fills charge gauge, which can be fired back at enemies. 

## Level Editor
+ Edits .enemies file in JSON Format.
+ SpawnTrigger: Distance in pixels from bottom of map fto trigger enemy to spawn.
+ enemeClassName: Type of enemy to spawn
+ rank: Difficulty modifier
+ spawnX/SpawnY: Position to spawn emeny
+ Associated with each entry is a path array, plotting x/y coordinates along which the entity follow. 

## Requirements
Windows 7+

## Release
Download and play [Here](https://github.com/bjwarfield/Osprey/releases)