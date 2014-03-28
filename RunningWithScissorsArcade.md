# Running With Scissors Arcade

## Elevator Pitch
> **Running With Scissors Arcade ** is a 4 Player infinite runner where each player plays a kid running down the sidewalk with scissors and must dodge hazards that spawn ahead of them faster and more frequently over time.

## Design Goals
1. The game will be light hearted and goofy and urge players to do their best regardless of others.

2. The game should allow people to continue to interact with the game at all times considering that death can come quickly but rounds can last over 30 seconds.

## Details

#### Hazards
The game will have hazards that spawn on the sidewalks in random positions offscreen and then come towards the players.  The hazards will be smaller, 16x16 pixels, and of greater variety than the original Running With Scissors.  Hazard spawn rate will increase over time.

#### Environment
The game will take place on an infinitely scrolling sidewalk.  The speed of the scrolling will increase over time.  UI elements will exist on the top of the screen to keep track of the scores for the individual players as well as keep track of round wins.

#### Players
Each player will look the same but have different color shirts.  The rest of the animations will remain the same as the original game.  The winner of the previous round will also be wearing a crown or hat of some sort.

## Gameplay

The object of the game will be to win 3 rounds.  To win a round, you must be last person standing at end of each round.  Rounds will continue until there is a person with 3 won rounds.  Description of gameplay flow follows:

1. Before the main game begins, players will have an opportunity to join game by pushing button 1.  After 10 seconds or all 4 players starting, the first round will begin.

1. Before the first round begins a small set of instructions will be shown describing the joystick controls for moving the player and how to spawn self as hazard after death.

1. Players will be given a 3 second count before the round starts.  Players are unable to move from their pre designated spawn points until the game starts.  Each player will be shown their position on screen with some sort of marker which will disappear after start.

1. When the game starts, players will be allowed to use stick to move around the sidewalk.  Players cannot interact with other players in any way while alive.

1. Players attempt to dodge hazards as the game gets faster and hazards spawn more often.  For every hazard they pass, they will receive 1 point.

1. If a player hits a hazard, they will be killed. While dead, players will have small marker on side of screen where they will be able to use joystick to move marker and push button 1 to spawn themselves on screen as a hazard.

1. When there is one player left, that player is allowed to continue play to accrue score until they hit a hazard.

1. After all players are dead, the next round begins in the same way as mentioned in (3).  A small trophy icon will go under the winner's score to mark a round win and the last winner will get a crown or hat to wear for next round.

1. After there is a player with 3 rounds won, there will be a final tally screen showing stats.  Stats will include:
   * rounds won
   * score for each round
   * total score from all rounds combined

1. After 15 seconds, the game will go back to the title screen as mentioned in (1).

## Controls

#### Joystick
Moves the player in all directions in the game and will be the primary means of input for the player.  After death, moves the marker on the side of the screen where the player can spawn a hazard.

#### Button 1
Used in menus and also to spawn player as hazard on the track after death.
