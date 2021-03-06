# Simple Arm Mover Simulation With ROS
Ros Nodes are a key abtraction that allows a robot system to be build modularly.
This [Udacity clone project](https://github.com/udacity/simple_arm) is an example of writing ROS nodes in Python.


## Wiki Contents
1. [**ROS Node and Topics**](https://github.com/fouliex/SimpleArmMoverWithROS/wiki/A.-ROS-Node-and-Topics)
2. [**ROS Message Passing**](https://github.com/fouliex/SimpleArmMoverWithROS/wiki/B.-ROS-Message-Passing)

##  Project Nodes
* simple_mover-publish joint angle to simple_arm
* arm_mover-provides a service called safe_mode
* safe_move-allows the arm to be moved to any position within its workspace.
**The safe zone is bounded my minimum and maximum joint angles, and is configurable via the ROS' parameter server

###### Simple Arm Mover 
![Simple Arm](https://github.com/fouliex/SimpleArmMoverWithROS/blob/master/misc/simple_arm.gif)
