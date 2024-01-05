**Connect Four Game**
This repository contains the implementation of the Connect Four game in Java, following the Model-View-Controller (MVC) architecture. The project is divided into two main components: the model, representing the game logic, and the GUI, encapsulating the view and controller aspects.

Overview

The Connect Four game is a classic two-player connection game in which the players first choose a color and then take turns dropping one colored disc from the top into a vertically suspended grid. The pieces fall straight down, occupying the lowest available space within the column. The object of the game is to connect four of one's own discs of the same color consecutively in a line, either horizontally, vertically, or diagonally, before the opponent.

Features

-MVC Architecture: The project follows the Model-View-Controller architecture for a clean separation of concerns.
-JavaFX GUI: The graphical user interface is implemented using JavaFX, providing an interactive game board.
-Observer Pattern: The model uses the observer pattern to notify the GUI about updates in the game state.
-Responsive UI: The GUI dynamically updates to reflect the current player, number of moves, and game status.
-Resource Loading: Images for player discs are loaded from resources for a visually appealing UI.

How to play

-Launch the application.
-The game board is displayed with buttons representing each column.
-Players take turns clicking on a column to drop their disc.
-The GUI updates to reflect the current player, number of moves, and game status.
-The game continues until a player wins or the board is filled, resulting in a tie.
