# AI_TurtleBot3Nav_task4
This repository is for task (4) of the AI track of my summer training at Smart-Methods

This is a collaborated work with my workmate: Maryam Alabdulhadi.  

-----------------------------------------------

**I Used the following code in this task:**

**Launch Simulation World**

    export TURTLEBOT3_MODEL=waffle_pi
    roslaunch turtlebot3_gazebo turtlebot3_world.launch
    
**Run Navigation Node in New Terminal**

    export TURTLEBOT3_MODEL=waffle_pi
    roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=$HOME/map.yaml
    
**TurtleBot3 has to be correctly located on the map with the LDS sensor data that neatly overlaps the displayed map, So:**

1- I will estimate Initial Pose Thtough pressing on 2D Pose Estimate button in the RViz menu.

2- I will click on the map where the actual robot is located and drag the large green arrow toward the direction where the robot is facing.

3- I repeated step 1&2 until I got the final result 

**In new terminal**

    export TURTLEBOT3_MODEL=waffle_pi
    roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch
    
4- After that I Move the robot back and forth a littl bit to collect the surrounding environment information and narrow down the estimated locatiton of m robot

5- Terminate the keyboard teleoperation node using Ctrl + C

**Set Navigation Goal**

Here I clicked on the 2D Nav Goal button in the RViz menu then I startes chosing the destinaion of my robor putting in mind what dirction it will be facing using the green arrow.

**Check the final results for more information.**

**Thank you for reading!!**
 



