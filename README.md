# GUI Snake Game

A classic implementation of the Snake game using Java's Swing library for the graphical user interface (GUI).

The objective is to control a snake to eat apples that appear on the screen. Each apple eaten makes the snake grow longer, and the game gets progressively harder. The game ends if the snake collides with the walls or with its own body.



## Features

-   **Graphical Interface:** Clean and simple UI built with Java Swing.
-   **Keyboard Controls:** Use the arrow keys to control the snake's direction.
-   **Score Tracking:** Your score increases for every apple you eat.
-   **Game Over Detection:** The game stops when the snake collides with a boundary or itself.
-   **Dynamic Growth:** The snake grows longer with each apple consumed.

## How to Play

-   The **Green** rectangle is your **snake**.
-   The **Red** circle is the **apple**.
-   Use the **Arrow Keys** (`Up`, `Down`, `Left`, `Right`) to move the snake.
-   Guide the snake to the apple to eat it and grow longer.
-   Avoid running into the edges of the screen or into the snake's own body.

## How to Compile and Run

You need the Java Development Kit (JDK) installed to compile and run the game. No external libraries are required.

1.  **Save the Code:**
    Save the Java code into a file named `SnakeGame.java`.

2.  **Open a Terminal or Command Prompt:**
    Navigate to the directory where you saved the file.

3.  **Compile the Code:**
    ```bash
    javac SnakeGame.java
    ```

4.  **Run the Game:**
    ```bash
    java SnakeGame
    ```

A new window will open with the game running. Enjoy!
