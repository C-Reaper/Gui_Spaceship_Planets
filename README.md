## Overview
This project appears to be a simple GUI application showcasing a spaceship and planets in a space-like environment. It uses C programming language, SDL for graphics, and makes use of custom headers and functions.

## Features
- Spaceship movement control.
- Multiple planets displayed in the screen.
- Rendering and updating of the scene.
- Basic user interface with FPS counter display.

## Project Structure

### Prerequisites
- C/C++ Compiler (GCC)
- Make utility
- Standard development tools
- SDL library for graphics and window management

## Build & Run

To build and run the project on Linux, follow these steps:

1. Navigate to the project directory.
2. Use make with the appropriate OS-specific Makefile:
   - For Linux: `make -f Makefile.linux all`
3. Execute the application with:
   - For Linux: `make -f Makefile.linux exe`

The build process will compile the source code and link it with the necessary libraries, resulting in an executable file located in the `build` directory.

---

Project Organization:

```
Gui_Spaceship_Planets/
├── build/
├── src/
│   ├── Main.c
│   └── *.h
├── Makefile.linux
└── README.md
```