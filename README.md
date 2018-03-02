# gazebo-mental-simulation-meta-example
An example meta package for https://github.com/jacobs-robotics/gazebo-mental-simulation containing the ROS workspace configuration and launch files for the simulation.

This is only one example how to handle experiments in the Gazebo Mental Simulation environment using a PR2. It contains:
* a *.rosinstall* file which, in conjunction with the *Dockerfile* in https://github.com/jacobs-robotics/gazebo-mental-simulation, sets up the ROS workspace
* a stripped-down model PR2 without cameras (for faster computing), but additional arm/gripper poses for easy handling
* example launch files which start up an example world and launch one run of an experiment
