# hw3

What code draws the blades of grass?
Line 13: line(x, height-10, x+random(-10, 10), height-10-random(h));

What code makes the "lawnmower" come by? How often does it come by?
line 23-27. Lawnomwer comes when the it has the random number of 100. 
/*
  if (random(100) > 99.9) {
    fill(255);
    rect(0, 0, width, height-15);
    h = 10;
  }
 */
 
What's the point of the h variable?
It's the height of the grass.

What does the -10 do in the second and fourth arguments of the line function, height-10-random(h) ? Why is it there?
-10 represents the thickness of the ground. 
height-10-random(h) represent the height of the grass. height-10 so it will grow above the ground. When the x reaches the end the of canvas, the grass will grow higher.
