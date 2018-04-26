## Name

Name your quiz: `CIS2013_Week14_Quiz1`

## Game Class

Make a game class with the following attributes & methods

### Attributes

* name (private)
* score (private)

### Methods

* A constructor that sets the game name
* get_name
* get_score
* set_score
* set_name

## Mine Sweeper Class

Create an mine_sweeper class that inherits from `game` with the following attributes & actions

### Attributes

* board_size
* board_rows
* board_columns
* selected_squares
* bomb_squares

### Actions

* A constructor that sets name, board size, and number of mines
* print_board
* get_square

### Behavior 

Calling get_square should check `bomb_squares` and set the appropriate `selected_squares` and return a value for bomb or no bomb.

## UI

Main will ask for columns, rows, and bombs. Then create a new object of type `mine_sweeper` with those attributes.  Then create a loop that:

* Prints the board
* Asks for a square
* Prints a message indicating if it was a bomb or not.
* Repeats until a bomb is discovered.




