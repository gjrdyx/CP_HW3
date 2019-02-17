# HW3
//What code draws the blades of grass?
  line(x, height-10, x+random(-10, 10), height-10-random(h));

//What code makes the "lawnmower" come by? How often does it come by?
  if (random() > 0.999) {
    fill(255);
    rect(0, 0, width, height-15);
    h = 10;
  random() is a random number between 0 and 1, when random() is larger than 0.999, the "lawnmower" will come by. 
  Accroding to: createCanvas(400, 200);
                x = x + 10;
                if (random() > 0.999)
  everytime a line of grass grows up, 1/25 chance the "lawnmower" will come by.
 
//What's the point of the h variable?
  3

//What does the -10 do in the second and fourth arguments of the line function, height-10-random(h)? Why is it there?
  make a range of the top end of the grass, so that the grass grows in random direction. 

# QUESTIONS
//What's the point of an object?
  the syntax of data.

//What's an example of a range you might use for the map function?
  map the mouse X to RGB color, even the number of the range is different.
  
//What line of code would give me a random year in the last century?
  x=random(1900, 2000);
