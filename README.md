# Pacman-Simulator
A 3D Simulator for Pacman game in Unity which includes AI for Pacman itself.

The project consists of two parts: 
The first one comes with an implementation of a fitness function used each time to calculate the best possible next move for the player (Pacman) and it is written entirely in C#. 
The second part has its main system written in C#, while the functions that define the moving strategies for Pacman and ghosts are described in separate Javascript scripts that can be easily exchanged with other similar scripts by the end-user (Javascript's eval function used to let built system read user written scripts and make them part of it).
