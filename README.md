Conway's Game of Life - JavaScript Implementation
=================================================

Welcome to **Conway's Game of Life**, a cellular automaton game created by the mathematician John Conway. This implementation allows you to interact with the grid, simulate the game's evolution, and explore the fascinating behavior of cells in various patterns.

Features
--------

-   **Interactive Grid**: Click on cells to toggle their state between alive and dead.
-   **Play/Pause**: Start and stop the simulation at any time.
-   **Speed Control**: Adjust the speed of the simulation using a slider.
-   **Next/Previous Frame**: Move step-by-step through each generation.
-   **Dynamic Grid Size**: Change the grid size and update it in real-time.
-   **Cell Animations**: Cells have animations for when they come to life, die, or get reborn.

Rules of Conway's Game of Life
------------------------------

-   **Any live cell with fewer than two live neighbors dies** (underpopulation).
-   **Any live cell with two or three live neighbors survives** to the next generation.
-   **Any live cell with more than three live neighbors dies** (overpopulation).
-   **Any dead cell with exactly three live neighbors becomes a live cell** (reproduction).

Live Demo
---------

Check out the live demo of this project [here](https://anthonydinunzioswe.github.io/gameOfLifeJS).

Technologies Used
-----------------

-   **HTML**: For structuring the page.
-   **CSS**: For styling the grid, buttons, and animations using TailwindCSS.
-   **JavaScript**: For the logic of the Game of Life, including grid management, cell state transitions, and animation effects.

How to Run the Project Locally
------------------------------

To run this project on your local machine:

1.  Clone the repository:

bash

Copy code

`git clone https://github.com/yourusername/gameOfLifeJS.git`

1.  Open the `index.html` file in your browser.

bash

Copy code

`open index.html`

1.  Enjoy exploring Conway's Game of Life on your local machine!

Controls
--------

-   **Play/Pause**: Click to start/stop the simulation.
-   **Next Frame**: Step to the next generation.
-   **Previous Frame**: Go back one generation.
-   **Speed**: Use the slider to control the speed of the simulation.
-   **Grid Size**: Change the grid size between 3x3 and 20x20 cells by entering a number and clicking "Update."

License
-------

This project is open-source and available under the MIT License.

Contributing
------------

If you'd like to contribute to this project, feel free to fork the repository, make your changes, and submit a pull request. Contributions are always welcome!

* * * * *

Enjoy exploring Conway's Game of Life and have fun simulating the evolution of cells!
