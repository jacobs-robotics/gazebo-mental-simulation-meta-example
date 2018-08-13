# gazebo-mental-simulation-meta-example
An example meta package for https://github.com/jacobs-robotics/gazebo-mental-simulation containing the ROS workspace configuration and launch files for the simulation.

This is only one example how to handle experiments in the Gazebo Mental Simulation environment using a PR2. It contains:
* a *.rosinstall* file which, in conjunction with the *Dockerfile* in https://github.com/jacobs-robotics/gazebo-mental-simulation, sets up the ROS workspace
* a stripped-down model PR2 without cameras (for faster computing), but additional arm/gripper poses for easy handling
* example launch files which start up an example world and launch one run of an experiment
* a number of Gazebo world files as used in `T. Fromm and A. Birk, Physics-Based Damage-Aware Manipulation Strategy Planning Using Scene Dynamics Anticipation, International Conference on Intelligent Robots and Systems, 2016, https://arxiv.org/abs/1603.00652` and `T. Doernbach, Self-Supervised Damage-Avoiding Manipulation Strategy Optimization via Mental Simulation, https://arxiv.org/abs/1712.07452`
