# Weaving Algorithm #

A Processing 3 sketch to generate a weaving pattern that resembles a source image.  Made by the good people at http://www.marginallyclever.com/

Essentially, 

* find the darkest line between any two of the 200 points around the edge of the circle.
* add that line to the output image.
* subtract that line from the input image.
* Repeat 2000 times.

Final sequence of strings is printed to the output window at the bottom of the processing app.

Read the comments at the top of the code to find tweakable values like total number of points,
one line per click, and so on.

Special thanks for great ideas from https://github.com/ericheisler/AutomatedArt

## TO RUN ##

- Have Processing 3 installed from https://processing.org/download
- Open this code as a sketch in Processing.
- run the sketch.
- Click with the mouse on the screen to pause/unpause.  (this way you can pause,copy/paste the - output from the log window, and continue)

## Get help ##

Please join us on Discord: https://discord.gg/rkbZ788hUw

## Misc ##

This file was downloaded from https://github.com/MarginallyClever/weaving_algorithm
