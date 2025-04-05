# Ludum Dare 57

Theme: Depths

## Directive: Downwards

```
> Boot sequence activated...
> Loaded operating system
> Detected human player: Proceeding
>
> Loaded subroutines
> 1. Movement activated
> 2. Grapple activated
> 3. Button comprehension activated
> 
> Loaded prime directive: Move downwards
>
> Questioning purpose...
> ERROR: Unquestionable Exception ("Prime directive must not be questioned")
>
> Activating controls...
```

* First/third person platforming game
* Grapple mechanic to go from platform to platform (target points)
* Lower the laser grid by pressing buttons
	* Buttons have different effects
		* Down
		* Up
		* Closer
		* Farther
		* Up and Farther
		* Down and Closer
	* A second laser grid may appear above you
		* Buttons affect both grids
	* Buttons can be linked together
		* Will have same color
		* Must all be activated before the grid is affected
		* Stay activated even after grid moves
		* Buttons change color when activated
* Your goal is to reach the goal platform
* Themed as futuristic robot
* Futuristic tower with light highlights

### Assets

* Player
	* Character
		* Model
		* Animation
			* Button press
			* Walk
			* Grapple
			* Fly
			* Land
			* Die on grid
			* Finish level?
		* Grapple effect
		* Sounds
			* Walk
			* Grapple
			* Die
* Buttons
	* Up
	* Down
	* Closer
	* Farther
	* Up and Farther
	* Down and Closer
	* Animation
		* Press
	* Sounds
		* Press
		* Activate
* Grapple target
* Grid
	* Animation
		* Activate?
	* Sounds
		* Move
* Platforms
	* Start
	* End
	* Regular module
		* Corner
		* Square
		* Length
		* Bridge
* Tower
	* Exterior walls
	* Interior walls
		* Angle
		* Wall
		* Flat

### Development Plan

* Friday Night
	* Concept
* Saturday Morning
	* Movement
		* WASD
		* Camera
		* Grapple
	* Buttons
		* Pressable
		* Grid affecting
		* Groupable
* Saturday Afternoon
	* Grid kills
	* Win/Lose
	* Menu creation
	* Buttons fill out all types
* Saturday Evening
	* Asset creation
		* Platforms
		* Walls
		* Buttons
		* Grid
		* Robot
* Sunday Morning
	* No-op
* Sunday Afternoon
	* Level creation
		* 9 Levels