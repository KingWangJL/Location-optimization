# Location-optimization
Marker-based joint Location-optimization
A solution to the optimization problem of joint positioning. Knowing the coordinates of a marked point (a point on the surface of the joint) and its direction vector, to get the 
approximate intersection of the axes of the two joints
First, get the circle at the joint port according to the direction vector and the axis length of the joint (the joint is a cylindrical shape).
First obtain the circle at the joint port (the joint is a cylindrical shape) according to the direction vector and the axis length of the joint,
then obtain the sampling coordinate points of the circle at the port (99), and calculate the sampling point of the circle at the two joint ports distance.Get the two points with 
the smallest distance, we think that the center point is similar to the intersection of the axis.
