# iBShow2
Rewrite of show_main.ino to work with Adafruit_ILI9340 and Adafruit_GFX.

Mostly fixed the use of cursor_x and cursor_y member variables.   Of course the Hardkernel guys modified  the original 
Adafruit_ILI9340 to add some fancy stuff.   There's some optimizations they made as well.  These aren't included in the 
Adafruit variant of the ILI9340 library.  

I was tired of hearing about how you HAD to use Arduino IDE 1.5.x versus 1.6.x   Plus this works out of the box without having to use the hardkernel modified code.   THey should submit a Pull Request and merge their changes.

