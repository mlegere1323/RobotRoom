Final Project
COS 452, Computer Graphics
University of Southern Maine
10/14/2016

This project is a simple room scene with a table, controllable robot with arm, 
and some interesting lighting effects. Also, there's a sphere mirror on the table
that animates on command in a circle.

Object collision (no including detection of walls in the scene) 
was not achieved successfully so as to allow the robot to manipulate objects in 
the 3d scene, but a basic framework exists for it to be done.

The only limiting of the robot's arm motion is in the forearm's grabbers. It
would seem for realistic rotation of the robots arm, one would need extensive 
study in inverse kinematics, something which could've been done with less time
contsraints.

EXTRA:
Also included is a sphere with a procedurally generated texture using 
perlin/simplex noise. See code comments for more details (specifically
do a CTRL-F on "perlin" and uncomment in animation function and elsewhere).

Spotlights (R,G, and B) will follow the robot when the mirror sphere is 
animating, otherwise they will move to random locations on the floor at
intervals you can specify in the code.
