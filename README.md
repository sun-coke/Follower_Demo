# follower_Demo
Note!



   This instructions were tested on Ubuntu 16.04 and ROS Kinetic Kame.



   This instructions are supposed to be running on the remote PC. Please run the instructions below on your Remote PC. However, the part marked [TurtleBot] is the content that runs on SBC of TurtleBot3.



   Make sure to run the Bringup instructions 







1.The follower demo was implemented only using a 360 Laser Distance Sensor LDS-01. a classification algorithm is used based on previous fitting with samples of person and obstacles positions to take actions. It follows someone in front of the robot within a 50 centimeter range and 140 degrees.


2.Running the follower demo in an area with obstacles may not work well. Therefore, it is recommended to run the demo in an open area without obstacles.
