# Spaceman Splink and the Gravity Engine
A puzzle platformer where you can't jump, but you can change the direction of gravity.

## Features (TODO)
- Loading tiles
- Player movement
	- Arrow keys
	- Collision with tiles
	- Gravity
- Change gravity
	- WASD
	- Rotates player sprite
	- Can't change while in midair
- Level editor
	- Tiles
	- Player & portal location
	- Mechanical connections
	- Palette
- Portals
	- Advance to next level
- Spikes
	- Kill you, restart level
	- Don't hurt if you walk through from the side?
- Crates
	- Follow player's changed gravity
- Mechanical parts
	- Levers
		- Toggle something when switched (walk or fall over)
	- Buttons
		- Activate something only while pressed (walk or fall on)
	- Doors
		- Open when activated, close when deactivated
	- Conveyor belts?
		- Move things on top of them 
- Palette swapping
- Menus
- Moonlings
	- Walk side to side
	- Fall with gravity
	- Turn when reaching block or edge
- Water?
- Ice?
	- Can't stop moving on it

## Assets (TODO)
### Art
- Tiles
- Player
	- Stand, walk frames, fall, die
	- Light switches color based on gravity direction
		- Darker when falling (can't use it)
		- Brightens with sparkle particles when landing
- Spikes
- Portal
- Crate
- Door
- Button
- Lever
- Moonling

###Sound
- Player walk
- Switch gravity
- Fall (humming)
- Land on ground (gravity refill)
- Can't switch gravity (player tried to switch to current direction or while in midair)
- Die
- Enter portal
- Lever switch on/off
- Button press/release
- Door open/close
- Moonling shuffle

## Puzzles
- Move during midair fall (avoid spikes)
- Land crate & self simultaneously
- Land crate on own head
- Pass crate over button while passing through door
- Time jump off of middle of ice
- Moonling flips on and off a switch

## Credits

Color palette: [Endesga 36](https://lospec.com/palette-list/endesga-36) by Endesga

Sound effects created using [SFXR](http://www.drpetter.se/project_sfxr.html)