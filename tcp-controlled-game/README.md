# About this fork:

## This is a fork of the "tetris-on-terminal" project that uses C sockets to implement a remote joystick. The game can be controlled remotely by an joystick sending the commands through TCP protocol.

Original description of the project:

# Hello on tetris-on-terminal
Tetris-on-terminal is a tetris game with CLI interface. I offer you classic tetris and cool "rainbow" mode. Try it out.

![Classic mode in tetris-on-terminal](./image.png)

## How to install.

To get the tetris-on-terminal you need this dependencies:

1. Unix-like environment.
2. Ncurses library.
3. C++11 compiler (for example g++).

### Step 1: download sources.
```sh
    $ git clone https://github.com/cdkrot/tetris-on-terminal
    $ cd tetris-on-terminal
```

### Step 2: compile.
```sh
    $ make
```

### Step 3: run.
```sh
    $ ./bin/tetris-on-terminal <current IPv4 address>
```

### Step 4: enjoy!
