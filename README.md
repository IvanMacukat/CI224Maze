# CI224 Semester 2 Project 

To create a simple world in OpenGL and generate objects that could obstruct the players vision and movement. The world could be interactive and be controlled with mouse or the keyboard. The aim of the project would be to create similar game to minecraft, that allows the player to roam freely and jump on objects and hit them to create a path.

# Proposed Technology 

- Collision dection
- Simple ballistics 
- Level genertion and storage
- Visual graphical design

# Pre-Requisites

- GNU Autotools

- OpenGL 3.0

- C++11 compiler

`$ yum groupinstall "Development Tools" -y
`$ yum install gcc-c++ glew-devel freeglut-devel -y

# Marking Scheme 

- 25% - For well commented code and indentation. 
- 25% - Implementation of game idea - you may wish
to provide original sketches of your idea as evidence
for this.
- 50% - Working game level and ability to move around in the world freely

# Installing the Project

This is a simple C++ application which uses OpenGL to demostrate movement, hit dection and level generation. In order to execute the program, you'll need to copy the repository from Github, through Eclipse. Follow these simple steps:

- Clone from git 
`$ git clone https://github.com/IvanMacukat/CI224Maze.git
- Start eclipse
- File import
- Projects from Git
- Existing local repository
- Import existing projects

Then to build the project, you would have to do the following in Eclipse:

- right-click project -> Build configurations -> Set active -> Release

- right-click project -> Build Project

Sometimes, the .bmp files aren't located properly, which means when the game is executed, you won't be able to see anything. To solve this issue, you'll need to: 

- Copy the 2 bmp into Release folder (Walls.bmp, Sky.bmp)

Final step is to run the application: 

- right-click CI224Maze under Release folder -> Run as -> Local C/C++ Application

- Or go to Release directory with terminal program and execute with ./CI224Maze