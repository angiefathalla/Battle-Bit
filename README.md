# battlebit
Battle ship video game using a Pic18f452 microcontroller
Battleship is a game that has been around for generations where traditionally 2 players have
opposing symmetric layouts of the sea and place their battleship pegs in different places on their
layout in either vertical or diagonal directions. Each player guesses the location of their
opponent’s battleship and deduces, by their guesses, to sink all the ships and ultimately win the
game. 
With that premise in mind, we derived a micro version or more appropriately worded “Bit
version” of battleship for a single player instead. Our version is scaled back due to limited visual
space on a 16-bit LCD Display screen, but effectively able to entice and instruct the user to enjoy
playing our Battle Bit game.
The Random Number Generator for placing the 3 chosen bit locations of the battleships are
hiding from the user to guess their locations. As the user inputs their guess as a binary number between 0-15
on logic switches. In addition to this the user has a visual display of proximity of their guesses to the actual ship locations.
Our intention is to encourage the user to learn binary numbers through this interactive microcontroller game.
