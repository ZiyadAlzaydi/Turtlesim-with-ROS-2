# Turtlesim-with-ROS-2
This project demonstrates how to control a simulated turtle robot using the turtlesim package in ROS 2 (Humble Hawksbill distribution). The simulation is run in an Ubuntu virtual machine using Oracle VirtualBox, and the turtle is teleoperated via keyboard input.
<img width="1920" height="1001" alt="ubunto  Running  - Oracle VirtualBox 05_02_47 02_20_11 ص" src="https://github.com/user-attachments/assets/91dc1833-3383-4fb0-bff4-677f83e3220a" />

Objectives:

Set up and run the turtlesim_node in ROS 2.

Use keyboard commands to control the turtle's movement and orientation.

Understand the basics of ROS 2 nodes, topics, and message publishing.

Tools & Technologies:

ROS 2 (Humble)

Ubuntu Linux (Virtualized in Oracle VirtualBox)

turtlesim package

turtle_teleop_key node for keyboard control

Key Features:

Manual Control: Use arrow keys to move the turtle forward, backward, left, and right.

Absolute Orientation: Rotate the turtle using G, B, V, C, D, E, R, T keys to specific angles.

Topic Communication: Real-time control is achieved by publishing to /turtle1/cmd_vel topic.

Execution Commands:

Launch the turtlesim node:

ros2 run turtlesim turtlesim_node

Run the keyboard teleoperation:

ros2 run turtlesim turtle_teleop_key

Educational Purpose:

This project helps beginners in robotics and ROS 2 understand how nodes interact, how topics are used to communicate between nodes, and how real-time control can be implemented in a simulation environment.

