# rgb2launchpadcolor
A small header file for converting an RGB value to a Novation Launchpad color code. Uses a list of colors from kaskade.com

# Usage
Include the header file in your code and use this function:
```C++
int rgb2launchpadcolor(int r, int g, int b);
```

It returns a color code between 0 and 127 that can be passed to a Novation Launchpad (Tested with Mk2 only) as a Midi signal.

# What in the hell
I know, there are probably better options to do this (please don't look at the code).
