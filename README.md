A simple command line text editor that can be used to edit, modify and save text files.

## Setup

### On windows

You will need a Linux environment withing windows because this text editor interacts with the terminal at a low level using the <termios.h> header (which is not available on windows).

Gcc and make should come pre installed on linux but you can install it using: sudo apt-get install gcc make

## Using the editor

Download the text-editor.c on your system
Compile using: cc text-editor.c -o text-editor

Run the text editor using: ./text-editor

### Use these keyboard shortcuts to save and quit the editor
**CTRL-S: Save**

**CTRL-Q: Quit**
