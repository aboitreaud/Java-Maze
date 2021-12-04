Maze Project for INF 103.

It finds a path between the departure and the arrival box using the dijkstra algorithm.

For users, 
    
-  enter your maze in a text file using D for the departure, A for the arrival, E for empty boxes and W for walls.

- enter your number of lines and columns at line 15 of the class Main

- replace "data/labyrinthe.txt" by the name of your txt file at line 16 of the class `Main`

- run the class `Main`

A copy of your maze has been created in a txt file at the address : "data/labyrinthe2.txt".
The solution appears in the console. Every box used in the path is displayed with a "." instead of the initial "E".

The project is separated in two packages:

- the `maze` package gathers everything related to the maze obect: its boxes, the `Maze` class and a new type of exception
- the `dijkstra` package contains the classes that implement the dijkstra algorithm

Some classes from the `maze` package extend classes from the dijkstra package.

In the default package, there are two classes: `Main` and `MainTest`. Only `Main` should be used to run the project.
