# Animated bricks!

Animation for [brick-by-brick](https://github.com/nypl-spacetime/brick-by-brick).

![bricks](bricks.gif)

To create animated gif, run:

    convert -reverse -delay 10 -loop 0 frames/*.png bricks.gif

To resize, using [Gifsicle](https://www.lcdf.org/gifsicle/):

    gifsicle -o bricks-small.gif --resize _x40 bricks.gif    
