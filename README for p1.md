Program 1
=========


Changelog
---------
* make the probability that a cars does not stop at the red light.<br>
* Some functions are made to shorten the main function.<br>
* The function will stop when the cars crash.<br>
* The Ex.2 is completed.<br>
* The plate of all cars are generated and At the end of the game the plate of all the cars that did not stop at the traffic light are displayed.<br>
* Optimize the random function used to determine the cars of each road.<br>
* Cars outside the cross road now will be hidden.<br>


Variable explanation
--------------------
* cars: The number of cars in each road.Cars(1) refers to cars from left to right,cars(2) from right to left, cars(3) from From top to bottom cars(4) from bottom to top. <br>
* left: To print the cars from left to right <br>
* right: To print the cars from right to left <br>
* up: To print the cars from top to bottom <br>
* down: To print the cars from bottom to top <br>
* t: Time for the whole process.<br>
* pl: The cross road.<br>
* all: The plate of all cars.<br>
* Notstop: The cars that did not stop at the traffic light.<br>
* Type: To determine whether a car will stop at the red light.<br>
* LR/UD: The variable used to determine whether the cars crash.<br>


Ex.2
----
* a): It is done in the 'ex2a' file.<br>
   
* b):e=input('','s');<br>
     l=input('');<br>
     n=input('');<br>
     f=recursive('','',e,l,1,m);<br>


     function f=recursive(a,b,e,L,y,n)<br>
     d=length(e);<br>
     flag=0;<br>
     a(y)=e(randi(d));<br>
     if y==L <br>
       if   a doesn't equal to every line in b<br>
            b=[b;a];<br>
       end <br>
       if   size(b,1)<n <br>
            a=recursive(a,b,e,L,1,n); <br>
       end <br>
     end <br>
     if y<L <br>
        a=recursive(a,b,e,L,(y+1),n); <br>
     end <br>
     f=b; <br>
end <br>

