<a href="https://www.cprogramming.com"><img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" height="25em" alt="C"/></a>

# So_Long

## Goal

Create a 2D game using the MinilibX graphics library where the player must collect all items and exit the map while avoiding obstacles. The project focuses on handling map parsing, rendering graphics, and managing player movement.

## Key Features

- Map Parsing: Reads a text file to generate the game map, ensuring it meets specific rules (walls, player, exit, and collectibles).
- Rendering: Uses the MinilibX library to display the map, player, items, and exit.
- Player Control: Allows the player to move around the map using keyboard inputs.
- Collectibles: Requires the player to gather all items before reaching the exit.
- Victory Condition: Ends the game when the player reaches the exit after collecting all items.

## Implementation Details

- Map Validation: Ensures the map is rectangular, enclosed by walls, and contains one player, one exit, and at least one collectible.
- Graphics: Renders sprites and updates the display dynamically as the player moves.
- Movement: Processes arrow key inputs to update the player's position on the map.
- Counters: Tracks and displays the number of moves made by the player.

## Challenges

- Map Errors: Handling invalid maps (e.g., missing walls, incorrect elements).
- Memory Management: Preventing leaks when loading and unloading resources.
- Rendering Optimization: Ensuring smooth graphics updates without lag.

## Skills Developed

- Graphics Programming: Learning to use the MinilibX library for 2D rendering.
- Map Parsing: Validating and reading complex data structures from text files.
- Game Logic: Implementing rules for movement, collection, and victory conditions.

## Installation

Clone the repository:
```sh
git clone git@github.com:casomarr/42-So_Long.git
``` 

Navigate to the project directory:
```sh
cd so_long  
```
Compile the program:
```sh
make  
```
Run the program with a valid map file:
```sh
./so_long maps/map1.ber  
```
