# Chrome T-Rex Game Clone

<div align="center">
  <img src="./readme_img/t-rex.png">
</div>

## Table of Contents

- [Description](#description)
- [How to Play](#how-to-play)
- [How to build and run](#how-to-build-and-run)
  - [Linux](#linux)
  - [Windows](#windows)
- [Screenshots](#screenshots)

## Description

This is a clone of the T-Rax game that is available on Google Chrome when you are offline. The game is built using C++ and the SFML library. The game is a 2D side scroller where the player controls a T-Rex that has to jump over cacti and avoid flying pterodactyls. The game is endless and the player's score is based on how long they can survive.

## How to Play

Player controls are simple. The player can press the spacebar to jump and the down arrow key to duck. The player can also press the up arrow key to jump and the down arrow key

## How to build and run

### Linux

1. Clone the repository
2. Install SFML with vcpkg:

```bash
git clone
cd vcpkg
./bootstrap-vcpkg.sh
./vcpkg install sfml
```

3. Run the following commands in the terminal:

```bash
cd path/to/repo
./build.sh
```

4. Run the executable:

```bash
./build/bin/main
```

### Windows

1. Clone the repository
2. Install SFML from [here](https://www.sfml-dev.org/download/sfml/2.5.1/)
3. Check the compiler path in the ```.vscode/tasks.json``` file
4. Run ```ctrl + shift + b``` to build the project
5. Run the executable

## Screenshots

![Screenshot 1](./readme_img/start.png)
![Screenshot 2](./readme_img/run.png)
![Screenshot 3](./readme_img/dead.png)
