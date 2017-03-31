# README #

This project is an implementation of the classic Battleship game.

Requirements:

* Windows machine or Mono installed
* Unix command line (use something like MSYS2 on Windows)

To get started:

1. Clone project
1. Open command line and cd to project root
1. Build using `build.sh`
1. Run using `run.sh` -- you can also find the executable in the bin folder, but this script makes it simpler to build and run from the command line.


Files:
~\

-"build.sh"
Shell script for building the code project

-"run.sh"
Shell script for running code project after building

-"out.txt"
Output log of program compiling

-"contributers.txt"
List of current Github contributers

src\

-"DeploymentController.vb"
Deployment of battleships when starting the game

-"DiscoveryController.vb"
Battleship player attack phase

-"EndingGameController.vb"
Actions for end of game

-"GameController.vb"
Links and controlls other code files to run the game

-"GameLogic.vb"
Sets up framework for playing the game

-"GameResources.vb"
Links all game resources required before the start

-"GameState.vb"
Enumeration to track which state the game is currently in

-"HighScoreController.vb"
High Score interface and display after game end

-"MenuController.vb"
Main menu interface

-"UtilityFunctions.vb"
Useful functions to be called by other code files

src\Model\

-"AIHardPlayer.vb"
AI for Hard Difficulty game

-"AIMediumPlayer.vb"
AI for Medium Difficulty game

-"AIOption.vb"
Interface for selecting AI difficulty in game

-"AIPlayer.vb"
Class which inherits from the player class to create a more complex AI player

-"AttackResult.vb"
Computing outcome of attack action from either player

-"BattleShipsGame.vb"
Controls a large chunk of the game including deployment, shooting and swaping turns 

-"Direction.vb"
Ship direction enumeration

-"ISeaGrid.vb"
Describes the grid which the game plays upon

-"Player.vb"
Player class which can see two grids and check on its ships

-"ResultOfAttack.vb"

-"SeaGrid.vb"
-"SeaGridAdapter.vb"
-"Ship.vb"
-"ShipName.vb"
-"Tile.vb"
-"TileView.vb"

