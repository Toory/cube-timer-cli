# cube-timer-cli
Rubik's Cube Timer (command line interface)

## Dependencies

[pyTwistyScrambler](https://github.com/euphwes/pyTwistyScrambler) - Needed to generate scrambles

## Installation

	git clone 'https://github.com/Toory/cube-timer-cli'
	cd cube-timer-cli
	svn export https://github.com/euphwes/pyTwistyScrambler/trunk/pyTwistyScrambler  # Download pyTwistyScrambler
	pip install -r requirements.txt #Download all dependencies needed
	sudo python cubetimer.py
	
Note that on Linux the script needs root permissions (required by the python module [keyboard](https://github.com/boppreh/keyboard))

## [Usage](http://i.imgur.com/NWFjDx5.gifv)

In the file config.ini you can change each stat value to True/False (True = show, False = do not show)  

#### Main Menu:

	1.Timer.
	2.Print last solves.
	3.Exit.

1 - Go to the timer

2 - Print saved solves

3 - Exit the program

#### Timer:

	Choose cube type:
	2x2 (2),3x3 (3),4x4 (4),5x5 (5),6x6 (6),7x7 (7),Pyraminx (p),Square-1 (s1),Skewb (s),Clock (c)

You can choose the cube by inputting the number (or letter) on the parentheses.
This will be asked only on the first solve, after that the script will generate the scramble for the same cube,
until you go back to the main menu (ctrl+c) or exit the program.

After the scramble is generated you can:

    Start the Timer by pressing Enter
    Go back to the main menu by pressing ctrl+c

After starting the timer you can:

    Stop the Timer by pressing Spacebar
    Stop the Timer without registering the solve by pressing Esc
	

All your solves will be saved in 'times.csv'.

## Credits

   [pyTwistyScrambler](https://github.com/euphwes/pyTwistyScrambler),
   [reddit.com/user/Storbod](https://github.com/Storbod/Python-Cube-Timer),
   [reddit.com/user/yovliporat](https://www.reddit.com/user/yovliporat)


	
