# ROS_Bootcamp
Introduction to ROS 


# ROS

Robot Operating System(ROS) is robotics middle-ware. Although ROS is not an operating system, it provides services designed for a heterogeneous computer cluster such as hardware abstraction, low-level device control, implementation of commonly used functionality, message-passing between processes, and package management. Running sets of ROS-based processes are represented in a graph architecture where processing takes place in nodes that may receive, post and multiplex sensor data, control, state, planning, actuator, and other messages.

#### <u>**MERITS**</u>

##### 1. ROS is general

The same base code and knowledge can be applied to many different kinds of robots like robotic arms, drones, mobile bases, … etc

**2. ROS is language-agnostic**

we can easily communicate between a Python node and a C++ node. It means a lot of re-usability and possibilities of co-working. Many libraries also allow you to use other languages (because ROS has mainly targeted C++ and Python).

##### 3. we can control multiple robots with ROS

ROS can work with multiple ROS masters. It means that you can have many independent robots, each with its own ROS system, and all robots can communicate between each other.
