A simple command line text editor that can be used to edit, modify and save text files.

## Setup

### On windows

You will need a Linux environment within windows because this text editor interacts with the terminal at a low level using the <termios.h> header (which is not available on windows).

`Gcc` and `make` should come pre installed on linux but you can install it using: sudo apt-get install gcc make

## Using the editor

Download the text-editor.c on your system
Compile using: cc text-editor.c -o text-editor

Run the text editor using: ./text-editor

### Keyboard Shortcuts
| Shortcut   | Action |
| -----------| ------ |
| CTRL + S   | Save   |
| CTRL + Q   | Quit   |


Writing a text editor would not have been possible without an elaborate [tutorial](https://viewsourcecode.org/snaptoken/kilo/index.html) by [Pailey Quilts](https://github.com/paileyq) guiding me through each and every step. 
