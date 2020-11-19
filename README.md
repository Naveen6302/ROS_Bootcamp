# ROS_Bootcamp
Introduction to ROS 


# ROS

Robot Operating System(ROS) is robotics middle-ware. Although ROS is not an operating system, it provides services designed for a heterogeneous computer cluster such as hardware abstraction, low-level device control, implementation of commonly used functionality, message-passing between processes, and package management. Running sets of ROS-based processes are represented in a graph architecture where processing takes place in nodes that may receive, post and multiplex sensor data, control, state, planning, actuator, and other messages.

#### *MERITS\*

##### 1. ROS is general

The same base code and knowledge can be applied to many different kinds of robots like robotic arms, drones, mobile bases, … etc

**2. ROS is language-agnostic**

we can easily communicate between a Python node and a C++ node. It means a lot of re-usability and possibilities of co-working. Many libraries also allow you to use other languages (because ROS has mainly targeted C++ and Python).

##### 3. we can control multiple robots with ROS

ROS can work with multiple ROS masters. It means that you can have many independent robots, each with its own ROS system, and all robots can communicate between each other.

### *Limitations\*

1. ROS does not support multiple robots with the same master node.

2. ROS inherently does not support real-time operation and thus not preferred for time-critical applications.
3. ROS needs high-compute resources and network connectivity on-board for the best performance.
4. Package management on deployed robots is limited.
5. Monitoring, logging, analytics and maintenance tasks for multiple robots are difficult in commercial settings.
6. Multi-robot/fleet management and interaction is not possible.

### **Basic ROS terminology**

1. **WORKSPACE:** A workspace is a folder where you modify, build, and install  packages. 
2. **ROS package:** It is the main organizational software which contains ROS nodes,ROS-independent library,dataset,configuration files etc.
3. **NODES:** A *node* is a process that performs computation. Nodes are combined together into a graph and communicate with one another using streaming topics RPC services, and the Parameter Server.
4. **ROS topics**: Such a node is said to publish information that can be received by other nodes. The information in **ROS** is called a **topic**. A **topic** defines the types of messages that will be sent concerning that **topic**. The nodes that transmit data publish the **topic** name and the type of message to be sent. 
5. **ROS MESSAGES**:  ROS uses a simplified *messages* description language for describing the data values that *ROS* nodes publish.
6.  **ROS service**: it is a client/server system. Here are some of the main characteristics of a **ROS service**: It is synchronous. The client sends a requests, and blocks until it receives a response. You should use **ROS services** only for computations and quick actions.
