# object-tracking-camera-control
The repository consists of a project that was aimed at developing a camera that automatically starts following a specific colored object once the object comes into its field

It consists of C++ source code with OpenCV library and Serial library
and a Arduino code for controlling 2 servos for 2 DOF horizontal and vertical directional motion of camera

the input from USB camera is directly connected to the Computer and processed the appropriate directional signal is created and sent to arduino through another USB to control the servos further

camcontrol.ino - arduino source code
main.cpp - testrun c++ source for controlling camera using keyboard arrow keys used for caliberating the arduino code
main2.cpp - integrated with opencv to perform autonomous function

youtube vedios of project
https://www.youtube.com/watch?v=-w4BVShdlUQ
https://www.youtube.com/watch?v=bQpqbJkos_w



Ball tracking FPV

initiated by-
Rohan V Dvivedi

materials used-
2 - micro servo motors to control the horizontal and verical motion of the CAmera
1 - USB webcam mounted over a servo co trolled base
1 - arduino

status -
complete

Aim:If the ball is found in the Screen of camera, the pixel coordinates are evaluated and the command is sent to arduino to make increment or decrement in servo angles to bring the center of ball at the center of screen.
