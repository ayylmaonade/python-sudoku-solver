# Python Sudoku Solver

This is a simple and lightweight build of Sudoku written in Python. It can be played in a working terminal, or with the simple UI I've provided. Both the CLI and GUI version use the exact same code, so you may re-write or create your own GUI, if you wish. Or simply use your IDE of choice to run the code. 

... That's it... Yeah. But it'll berate you with insults when you choose the incorrect number!

# Installing & running

You _must_ have Python3 installed. 

The UI depends on **PyGame** to function, you _must_ have it installed or the UI will simply not run.

**Installing PyGame:**

- Arch/Arch based: ```sudo pacman -S python-pygame```

- Debian & Ubuntu/debian based distros: ```sudo apt-get install python3-pygame```

- Fedora/RHEL: ```sudo yum install python3-pygame```

- OpenSUSE: ```sudo zypper install python3-pygame``` (for all 10 people who use it)

- Windows & Mac: No idea, I don't use either.

**Running Soduku Solver:**
- Make sure both **solver.py** & **GUI.py** are in the same directory.
- cd into the directory using your terminal - e.g. `cd ~/python-soduku-solver`
- Run the game from **GUI.py** using `python3 -m GUI.py`

Alternatively, you can change the GUI file into a direct executable.

To do this, add `#! /usr/bin/python` to the top of **GUI.py** and then run `chmod +x GUI.py`

Run the script using `./GUI.py` in terminal.
