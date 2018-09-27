# hw3
Comp Practice Homework 3

-----

Lawn Sim questions:

1) What code draws the blades of grass?

function draw() {
  stroke(random(60, 70), 100, 90);
  line(x, height-10, x + random(-10, 10), height-10-random(h));

2) What code makes the "lawnmower" come by? How often does it come by?

  if (random() > 0.999) {
    noStroke();
    fill(255);
    rect(-1, -1, width+2, height-15);
    h = 10;
  }
  
  It comes at random intervals.

3) What's the point of the h variable?

To set the height for the blades of grass.

4) What do the three numerical arguments of colorMode do?

To literally set the Hue (specific color), Saturation (how contrast-y the color is), and the Brightness (how light or dark the color is).

5) What does the -10 do in the second and fourth arguments of the line function, height-10-random(h)? Why is it there?

They set the grass location to be on the brown ground.

-----

Loops and Arrays questions:

1) If an array has 5 elements in it, what are the valid index values for the array? (Hint: what's always the first index value?)



2) What is the difference between a for loop and a while loop?



3) Use Google or your favorite search website to figure out what the three parts of a for loop are called in JavaScript.



4) How does code refer to the number of elements (aka "entries") in an array? (Hint: it shows up in the code you modified!)

