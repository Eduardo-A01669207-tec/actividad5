# memory.py modified
How to run the game: python3 memory.py

List of changes for this file:

The grid was changed to a 4x4 layout.

A tap counter is now displayed on the screen to track the player's clicks.

Standard digits were replaced with Greek letters and mathematical symbols.

The symbols are perfectly centered inside each tile.

Change 1
A counter for the number of taps was implemented, and the board size was adjusted. A count_tap variable was added to the state dictionary to keep track of clicks. Every time the tap() function is called, this counter increases by 1, and the total is drawn in red text at the top left corner of the screen (-190, 180). Additionally, the grid was reduced from 64 tiles to a 16-tile (4x4) grid, increasing the tile size to 100 pixels.

Author: Alejandro Rodriguez Brito

Change 2
The visual design and difficulty of the game were improved. The standard number array was replaced with a custom list of 32 Greek letters and math operators (like α, β, ∑, ∞) to provide a better memory challenge. Furthermore, the drawing logic in the draw() function was updated to correctly center these new symbols inside the larger 100x100 tiles by adjusting the goto() coordinates and adding the align='center' parameter.

Author: Eduardo Arteaga Camacho 
