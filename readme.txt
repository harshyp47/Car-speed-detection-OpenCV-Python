In this tutorial, you will learn how to detect the speed of a car using Python OpenCV library and some basic mathematical calculations. In the area of traffic management, checking the speed of a vehicle passing through a road becomes very crucial when there is the rule of speed limitations. This Python program exactly checks the speed of the car passing through a specified lane and prints it on the console window.

To do this, you need the footage of cars passing through the road or you can directly take input from any camera device. The camera must be fixed at a specific position so that it can not move in any direction.

In this tutorial, we are using a trained model that can detect the car. These type of files contains the features of a car and provides the advantage to detect a car.

Speed= distance/time. We all know this little formula. Now we are going to implement that in our code. We need to draw a polygon in our footage and we must know the distance (In our case it is 3 meters)  between the two horizontal lines provided in the image link below.

When (x,y) coordinate of detected car strikes to the first line the program will be going to print “Car Entered.” in the console and start to calculate time till (x,y) of a car reaches to the second horizontal line and prints “Car left.” and also prints the speed by using simple formula distance covered(3m in our case)/time taken(which is being calculated). Here (x,y) refers to the coordinate of the top left corner of the rectangle which is being drawn after a successful detection of a car.

See image for better understanding.