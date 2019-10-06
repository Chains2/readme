Program2 Milestone2
===================

Changelog
---------
* change the code'x=-w:-2;y=2:w;'(w is the width of the road) which will report an error when w<2 to 'x=(-w-2):-2;y=2:(w+2);' <br>
* Making the cars by using 'patch' and using 'pause' to make them move <br>
* Use some variables to push the cars which will overcome the stop line when the light is red or orange a unit back.


Variable explanation
--------------------
* cars: The number of cars in each road.Cars(1) refers to cars from left to right,cars(2) from right to left, cars(3) from From top to bottom cars(4) from bottom to top. <br>
* left: To print the cars from left to right <br>
* right: To print the cars from right to left <br>
* up: To print the cars from top to bottom <br>
* down: To print the cars from bottom to top <br>
* t: Time for the whole process.

problems
--------
* The t may not be accurate for all cars to leave the cross road  for some cars are pushed back at the stop line.
* The code is too long.
* haven't make the probability that a cars does not stop at the red light yet 
