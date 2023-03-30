# Maze Generator 
- The repository is a maze project that uses various data structures and algorithms to generate and solve mazes.

## Introduction
 #### Data Structures
- Graph data structure: The maze is represented as a graph, where each cell in the maze is a node in the graph and the edges represent the possible paths between the nodes.

- Stack data structure: The depth-first search algorithm used to solve the maze is implemented using a stack data structure.

- Queue data structure: The breadth-first search algorithm used to solve the maze is implemented using a queue data structure.

- Disjoint-set data structure: The Kruskal algorithm (It is used to discover the shortest path between two points in a connected weighted graph.) used to generate a maze is implemented using the disjoint-set data structure.

- Priority queue data structure: The  algorithm used to solve the maze is implemented using a priority queue data structure.

- **Maze Feature**
    - Generate new layout "C"
    - Change Object player "P"
    - Change view "V" (2 Dimension, 3 Dimension, Fps)
    - Move the player **Up:"W" | Down:"S" | Left:"A" | Right:"D"**
    - Rotate maze **-YAxis:"J" | -XAxis:"K" | XAxis:"I" | XAxis:"L"** (Only In 3dimension)
    - Action For Key --> **1,2,3,4,5**
        -  Key 1 -> Active/Deactive Ambient Light
        -  Key 2 -> Active/Deactive Diffuse Light
        -  Key 3 -> Active/Deactive Specular Light
        -  Key 4 -> Change The Day (Background)
        -  Key 5 -> Change Wall Transparant or Not
    - Change Maze size , **"+" to Increase and "-" to Decrease**
    - Arroy Key To Walk Inside Maze While in Fps Mode (ArrowKeyUP , ArrowKeyDOWN , ArrowKeyLEFT, ArrowKeyRIGHT) 
    - Change Nim (ID) Rotation Using Mouse Click (Left,Center,Right)
    - Space to Run/Stop another one player.
 
### Build & Run 
- **Linux/Ubuntu**  
    - You Can Use The Codeblock For Linux As Well.  
    - You Can Execute Your Code Using A Text Editor That You Love. Like Atoms, Sublime,Geany Or Another.  

  Before Executing, You Must Install Some Dependenci Of Glut On Linux. What You Need To Do Is (Installation Via Terminal):  
    - Install The Compiler And Necessary Tools.A Fairly Complete Compiler You Can Use G++, How to : 
        ```sh
        sudo apt-get install g++ cmake 
        ```
    - Install Freeglut :
        ```sh
        sudo apt-get install freeglut3 freeglut3-dev
        ```
    - Run Using Terminal : 
        ```sh
        gcc -o excecutebin main.cpp -lglut -lGL -lm -lGLU -lstdc++
        ```
### Documentation  
- **V-1.0**  
    - In This Version, The Object The Player Can Still Penetrate The Wall  
    - Object Player Running (Right, Left, Bottom, Top) With Magnitude 0.1.  
    - The Shape Of The Maze Randomed By Using Button C & Player Can Walk A = Left, S = Down, D = To, W = Up  
    - Still 2 Dimensional Maze Form
- **V-2.0**  
    - Object cant penetrate the wall
    - Have two object player (cube and cone) 
    - Have 2 different view, 2d and 3d
    - When 3dviewmode, maze can rotation by I,J,K,L
    - Nim rotation can change by mouse click (left,center,right)
    - Change maze size using **"+"** to increase and **"-"** to decrease
- **V-3.0**  
    - Have 3 different view, 2d, 3d, Fps
    - Can walk inside the maze using arrowKey when fps viewmode 
    - Active / Deactive 3 Light usign 1,2,3 Key
    - Tranparant Wall usign the 5 Key
    - Day or Night usign the 4 key
    - Spaace to Run/Stop another one player.