# BattleShip-Game

A program that will play a limited battleship game in which the player must sink all of the ships with the fewest number of shots possible.

Battleship is usually played by two players, each of whom places five ships of varying sizes on a 10 x 10 grid. 

On a turn-by-turn basis, each player tries to place a shot where their opponent has placed a ship.

Of course, neither the opponent nor you are able to see where the other player has placed their ships.

Typically, the player will shout out shots to try to locate and sink each of the ships.

The player who sinks all of his opponent's ships.

The winner is the first player to sink all of the other ships.





The API will place 5 ships (lengths 2,3,3,4,5) on the board at random in this BattleShip instance.

A ship will be present in 17 of the 100 locations on the board.

You've solved the game when the player has 17 hits.

The goal is to achieve the lowest average number of shots when the game is played 10000 times. 






The Battleship API's public methods are listed below:



• BattleShip() - This function creates a battleship game instance.

• boolean shoot(Point shot) - This function points each shot in the game.
 
• int numberOfShipsSunk() - This function returns the total number of ships sunk at any point during the game. 

• boolean allSunk() - This function returns a boolean value that indicates whether all the ships have been sunk.

• int totalShotsTaken() - This function returns the total number of shots taken. 

• int[] shipSizes() - This function returns an array of the ship sizes. The number of ships present is indicated by the length of the array. For the game, this array is fixed, with ship sizes of 2,3,3,4,5. When a ship is sunk, it does not update.
