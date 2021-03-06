# Maze-Generator-and-Solver-Depth-First-Search

This is a maze generator and solver coded in Java with Graphics too. A single class is responsible for both the generation of the maze and the solving. Both the generator and the solver are based on [Depth-first search](https://en.wikipedia.org/wiki/Depth-first_search) algorithms, particularly [Backtracking](https://en.wikipedia.org/wiki/Backtracking) algorithms. My implementation is iterative and uses a stack to backtrack efficiently. Images of different sizes of mazes below.

Jump into the code:
* *__MazeViewer.java__*: A very short class that just takes the maze and draws it. It also handles keyboard input.
* *__Maze.java__*: This class contains the maze and it's properties. The maze is generated and solved when you in instantiate it.

Instructions:
* Press the 'r' key to generate a new solved maze
* If you want to change the dimensions of the maze itself, you can also tweak the 3rd parameter in the constructor call of the *Maze* class in *__MazeViewer.java__*, which is the size of a single cell in pixels.
    ```java
    maze = new Maze(WIDTH, HEIGHT, 10); // size of 10 pixels for a cell
    ```
* To change the dimensions just go into *__MazeViewer.java__* and change the following lines of code to anything you want. They are dimensions in pixels, the code handles the size of the maze automatically. 
    ```java
    private static final int WIDTH = 1010; // width in pixels
    private static final int HEIGHT = 1010; // height in pixels
    ```
___

A few examples: 

50x50

![](maze50x50.jpg)

100x60

![](maze100x60.jpg)

190x100

![](maze190x100.jpg)