This repository contains some of the task that was carried on using ROS2 Jazzy. I have created some python based nodes that use the turtlesim and its parameters to publish and subcribe values. Kinldy understand, you need to install respective ROS positories and to have knowledge of command links to use these files. 


Take a look at 'turtle_controller.py' file. It is a closed loop system that has single node with both publisher and subscriber. The node subsribes to the turtlesim's pose message to get the current pose values of the turtle, and based on the values publishes to turtlesim such a way the turtle does not hit the wall. So, hence a closed loop system with single node. Feel free to play with the values.
