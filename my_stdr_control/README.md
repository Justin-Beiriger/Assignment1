# my_stdr_control

This package includes just one executable cpp file, stdr_open_loop_commander.cpp. This code provides control commands for the stdr robot simulator to navigate through the predesigned maze and end up in the top left corner of the simulated environment. The commands were designed on a trial-and-error basis, using the grid on the simulation environment that demarcates 1-m gridlines as a reference. 

## Example usage

First, the robot simulator environment must be initialized using the launch command: "roslaunch stdr_launchers server_with_map_and_gui_plus_robot.launch". Then, run the open loop commander script in this package by executing the command: "rosrun my_stdr_control open_loop_commander". Notice that the name of the executable is open_loop_commander, which is not the same as the name of the cpp file. 

## Running tests/demos
    
The video file showing the demo can be found at the following link:

https://youtu.be/O9AdLQsAPnM
