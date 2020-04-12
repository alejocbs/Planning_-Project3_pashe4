
# ENPM661 Project 3- Phase 3 and 4
## This project plans a path for the TurtleBot taking into consideration its holonomic constraints and uses Astar algorithm to solve the obstacle space
<img src="https://github.com/AkshayKurhade/ENPM661Project3Phase3and4/blob/master/Output/Map.png" width="480">

### Note-All Dimensions were considered to be in millimeters(mm)

# Output video Link-https://youtu.be/RoZN09WYEkI

# Required Libraries-
    1) Matplotlib
    2) Numpy
    3) Time
    4) Math
    5) heapq
    6) Opencv
    Warning - Use of 'heapq' may generate low memory or running out of memory error

## Files required in the source directory
    1) Are include in the work space

## How to run the code-
 ### System Requirements-
        Python v2.7.x or later
 ### Custom ros command
	Inside the work space folder.
      /Project_4/src$
	Type the following command to open gazebo
         roslaunch astar_gazebo map.launch
        
  Note: This launch application will execute gazebo with turtlebot 2 defined as default on the left bottom corner of the maze.
  inside the controller folder:
  Type
   rosrun controller controller.py
  
<img src="https://github.com/alejocbs/Planning_-Project3_pashe4/blob/master/Gazebo.PNG">

 
   
