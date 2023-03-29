# Maze Generator 
[![forthebadge](http://forthebadge.com/badges/built-with-love.svg)](https://github.com/fianekame/Maze-Project)

A Simple Program That Makes Random Maze Using Opengl Api With C++ Language. This Program Was Made On My Current Computer Graphics Courses Finish In 2017. 
View Release [Here]
> Thanks : Mr.Yonathan Ferry Hendrawan

## Introduction
 #### Data Structures
- Graph data structure: The maze is represented as a graph, where each cell in the maze is a node in the graph and the edges represent the possible paths between the nodes.

- Stack data structure: The depth-first search algorithm used to solve the maze is implemented using a stack data structure.

- Queue data structure: The breadth-first search algorithm used to solve the maze is implemented using a queue data structure.

- Disjoint-set data structure: The Kruskal's algorithm used to generate a maze is implemented using the disjoint-set data structure.

- Priority queue data structure: The A* algorithm used to solve the maze is implemented using a priority queue data structure.

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
- **Windows**  
    - Required ... 
To Run This Program In Windows You Can Use The Codeblock IDE ([Get Here](https://www.google.co.id/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwjIp8ONmr3TAhVBNpQKHQfJDUQQFggkMAA&url=http%3A%2F%2Fwww.codeblocks.org%2Fdownloads&usg=AFQjCNGin5_gzph-iFTEZ-NsXkpwypBBNQ&sig2=L7-9vYIUSTwdC01iQdkVJQ)) After That Follow The Instructions The Installation With The Addition Of The Opengl Api ([Learn Here](http://www.sci.brooklyn.cuny.edu/~goetz/codeblocks/glut/)).  
    - _How To Run :_  
        ```sh
        - Create A New Project Glut/Opengl Project
        - Just Copy Paste The Code In Your main.Cpp Has Been Made
        - Build & Run
        ```
- **Linux**  
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
        gcc -o excecutebin filename.cpp -lglut -lGL -lm -lGLU -lstdc++
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



License
----
[![npm](https://img.shields.io/npm/l/express.svg?style=plastic)](https://github.com/fianekame/Maze-Project/blob/master/LICENSE)
Copyright (c) 2017 Sofian Eka Sandra

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so

[Here]: <https://github.com/fianekame/Maze-Project/releases>
